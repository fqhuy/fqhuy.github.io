---
layout: default
title: Phan Quoc Huy
---

# Recent News

<section style="max-width:1000px;margin:auto;">
<ul style="list-style-type:none;">
{% for post in site.posts limit:5 %}
  <li>
    {{ post.date | date: "%b %d, %Y"  }} &mdash; <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
</section>

# Research Projects

<section style="max-width:1000px;margin:auto;">
<table class='project-list'>
{% for project in site.projects %}
  <tr> 
      <td width="30%"> <img src="{{ project.image }}" class="project-rep-image"> </td>       
      <td width="70%">  <p class="project-title"> <a href="{{ project.url }}"> {{ project.title }} </a> </p>
      		<p class="project-doi"> <b> URI: </b> {{ project.doi }} </p>
      		<p class="project-authors"> <b> Authors: </b> {{ project.authors }} </p>
      		<p class="project-abstract"> <b> Abstract: </b> {{ project.abstract }} </p>
      </td>
  </tr>
{% endfor %}
</table>
</section>