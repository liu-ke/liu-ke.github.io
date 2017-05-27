---
layout: page
title: About
description: Coding changes the world
keywords: Liu, Ke/刘珂
comments: true
menu: 关于
permalink: /about/
---

努力从不辜负，成长总能开掘

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
