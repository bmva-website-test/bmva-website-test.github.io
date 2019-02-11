---
layout: news
title: News
sidebar: twitter
year: 2019
---

<div class="col-12 col-sm-12 col-lg-12 news">

  {% assign news = site.categories.news | sort:"date" %}
  {% for n in news reversed %}

    <div class="panel panel-default bottom3">
        <div class="panel-heading">
            <h2 class="panel-title"><a href="{{ site.url }}{{ n.url }}">{{ n.title }}</a></h2>
            <p>{{ n.date | date: "%B %d, %Y" }}</p>
        </div>
        <div class="panel-body">
            {{ n.content }}
        </div>
    </div>
	{% endfor %}

</div><!--/span-->
