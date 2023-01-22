---
layout: archive
title: "Working Papers"
permalink: /workingpapers/
author_profile: true
---

{% if author.googlescholar %}
 You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}

**Optimal**. 2022. <br/>
<small>[ <a href="#/" onclick="visib('identifying-prediction-mistakes')">Abstract</a> | [Draft][identifying-prediction-mistakes] | [Supplement][identifying-prediction-mistakes-supplement] ]</small>


<div id="identifying-prediction-mistakes" style="display: none; text-align: justify; line-height: 1.2" ><small>
optimal
</small><br><br/></div>
[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
