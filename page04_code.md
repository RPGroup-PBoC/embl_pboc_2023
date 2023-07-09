---
layout: page
title: Code
img: code.png # Add image post (optional)
permalink: code
sidebar: true
---

---

During this course, you will develop a computational prowess that will aid in
your understanding of physical biology.  These will
be done using Jupyter notebooks through [Google
Colab](https://colab.research.google.com/), so you will need to sign into a
Google Account to create new notebooks.  

We will post links to Jupyter Notebooks hosted on Colab of the tutorial
sessions here. 


{% for topic in site.data.code %}
# {{topic[0]}}
{% for script in topic[1] %}

* {%if script.colab %}{%if script.colab %}<a href="{{script.colab}}" target="_blank">**{{script.title}}**</a>
  {%else%}**{{script.title}}**{%endif%}\|
  {{script.description}}   {%if script.links %} <br/>  {%for l in script.links
  %} <i> <a href="{{l[1]}}" target="_blank">**{{l[0]}}**</a> </i> <br/>{%endfor%}   {%endif%}
{%endfor%}
{%endfor%}