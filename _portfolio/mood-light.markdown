---
layout: post
title: Mood Light
description: Light changing according to room atmosphere
img: /img/mood_light/thumb.jpg
---
<img src="{{ site.baseurl }}/img/mood_light/mood_light2.gif" style="width:100%">
<br/>
This project is based on the ideas that our frame of mind is always influenced by our environment, and the intensity of light in a room has a strong influence on the atmosphere. So why not make the light act according to the atmosphere in a conversation?<br/><br/>I used an SVM algorithm, to train a model with tagged conversation sound samples, indicating how relaxed the conversation is.<br/>The sound in the room is recorded all the time and sent to the trained model every 3 seconds for classification.<br/>The light is then changed according to the how intimate or angry the conversation in the room is.