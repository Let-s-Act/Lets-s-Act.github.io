---
title: 'Conversations'
subtitle: ''
date: 2018-06-30 00:00:00
description: Board is a stylish full-width masonry grid theme. Made for designers, artists, photographers and developers to show off their best work.
featured_image: '/images/Conversations.jpeg'
---

![](/Lets-s-Act.github.io/images/Conversations.jpeg)

## Conversations

<div class="gallery" data-columns="3">
    {% for convo in site.data.poetry.conversations %} 
        <div class="item">
        <img src="/Lets-s-Act.github.io/{{convo.image}}" alt="{{ convo.title }}"/>
        <audio src="https://lets-act.s3.us-east-2.amazonaws.com/{{convo.audio}}" type="audio/mpeg">
        </div>
    {% end %}
</div>