---
layout: default
---
{% assign sorted = (site.portfolio | sort: 'date') | reverse %}
{% for project in sorted %}
{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}
        <span>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
    <p class="caption"> {{ project.title }}</p>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}
        <span>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
    <p class="caption"> {{ project.title }}</p>
</div>

{% endif %}

{% endfor %}