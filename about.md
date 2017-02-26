---
layout: page
title: About
permalink: /about/
---

<img class="col one right" src="/img/jasmin.jpg" style="padding:25px">

<div>
Hello, my name is Jasmin Rubinovitz. I'm <span class="changing"></span>
<br>
<br>
I'm a cross disciplined researcher, designer and engineer - currently a Research Assistant and a Graduate Student in the Viral Communications group at MIT Media Lab.
<br>
In the past I worked as a software engineer at Google.  
<br>
<br>
I hold a B.Sc in Computer Science from the Hebrew University of Jerusalem, with a B.F.A in Ceramic Design from Bezalel Academy of Art and Design.  
<br>
<br>
I'm interested in exploring the ways we communicate with people and objects in our surrounding environment.


 <a class="page-link" target="_blank" href="{{ '/jasmin_rubinovitz_cv_2016.pdf' | prepend: site.baseurl }}">Resume</a>
</div>

<br/>
<hr/>
<br/>
<span class="contacticon center">
	<a href="mailto:jasrub@media.mit.com"><i class="fa fa-envelope-square"></i></a>
	<a href="https://github.com/jasrub" target="_blank"><i class="fa fa-github-square"></i></a>
	<a href="https://il.linkedin.com/pub/jasmin-rubinovitz/a5/a91/9b1" target="_blank"><i class="fa fa-linkedin-square"></i></a>
	<a href="https://www.facebook.com/jasmin.rubinovitz" target="_blank"><i class="fa fa-facebook-square"></i></a>
</span>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>

<script type="text/javascript">
	{% include js/typed.js %}
</script>
<script>
  $(function(){
      $(".changing").typed({
        strings: ["a maker.", "a developer.", "a designer.", "an artist.", "a researcher."],
        typeSpeed: 50,
				backDelay: 2000,
				showCursor: false,
				loop: true
      });
  });
</script>
