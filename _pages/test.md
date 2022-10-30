---
layout: schedule
permalink: courses/6170/22/lec
sidebar:
  nav: "courses"
classes: wide
title: CS6170 - Randomized Algorithms
description: Lecture schedule
---

{% assign tut_num = 0 %}
{% assign mq_num = 0 %}
{% assign q_num = 0 %}
{% assign endsem = 0 %}

{% for item in site.data.lec6170-22 %}
{% assign lecture = item %}
{% if lecture.tutorial %}
{% assign tut_num = tut_num | plus:1 %}
{% elsif lecture.miniquiz %}
{% assign mq_num = mq_num | plus:1 %}
{% elsif lecture.quiz %}
{% assign q_num = q_num | plus:1 %}
{% elsif lecure.endsem %}
{% assign endsem = endsem | plus:1 %}
{% endif %}
<tr>
<td>
{% if lecture.contents %}
<strong>Lecture #{{ forloop.index | minus:tut_num | minus:q_num | minus:mq_num | minum:endsem }}</strong>
<br/>
{% elsif lecture.tutorial %}
<strong style="background:Aquamarine;"> Tutorial #{{ tut_num }}</strong>
<br/>
{% elsif lecture.miniquiz %}
<strong style="background:LightSalmon;"> Mini-quiz #{{ mq_num }}</strong>
<br/>
{% elsif lecture.quiz %}
<strong style="background:Salmon;"> Quiz #{{ q_num }}</strong>
<br/>
{% elsif lecture.endsem %}
<strong style="background:Salmon;"> End-sem </strong>
{% endif %}
{{ lecture.date }} </td>
<td>
{% if lecture.tutorial %}
{{ lecture.tutorial }}
{% elsif lecture.miniquiz %}
{{ lecture.miniquiz }}
{% elsif lecture.quiz %}
{{ lecture.quiz }}
{% elsif lecture.endsem %}
{{ lecture.endsem }}
{% endif %}
{{ lecture.contents }}
{% if lecture.slides %}
<br> [<a href = "{{ lecture.slides }}">slides</a>]
{% if lecture.notes %}
[<a href = "{{ lecture.notes }}">notes</a>]
{% endif %}
{% endif %}
</td>
<td>
{% for ref in lecture.references %}
<ul>
<li>{{ ref }}</li>
</ul>
{% endfor %}
</td>
<td>{{ lecture.misc }}</td>
</tr>
{% endfor %}
