---
layout: page
title: About
description: 
img: corona_virus_goodsell.jpg 
caption: "Courtesy of David S. Goodsell"
permalink: index.html
sidebar: true
---

# {{site.data.about.title}}
{{site.data.about.authors}}

{% for entry in site.data.about %}

{% if entry[0] != 'title' %}
{% if entry[0] != 'authors' %}
## {{entry[0]}}
{{entry[1]}}
{% endif %}
{% endif %}
{% endfor %}

## Where and When?

Each day, the course will roughly proceed as outlined below. On occasion, we may insert computation sessions during the daytime based on the flow of discussion throughout the course. 

<table>
<tr>
    <th style="width:130px"><b>Time</b></th>
    <th><b>Session</b></th>
</tr>
<tr>
    <td>09h00 - 12h30</td>
    <td>Rob/Jane lecture (with coffee break) </td>
</tr>
<tr>
    <td>12h30 - 14h00</td>
    <td>lunch</td>
</tr>
<tr>
    <td>14h00 - 16h00</td>
    <td>Rob/Jane lecture </td>
</tr>
<tr>
    <td>16h00 - 18h00</td>
    <td>guest speaker and meet the speaker </td>
</tr>
<tr>
    <td>18h00 - 19h30</td>
    <td>dinner</td>
</tr>
<tr>
    <td>19h30 - 21h30</td>
    <td>Computational Session with Tom</td>
</tr>
</table>