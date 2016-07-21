---
layout: default
title: Phan Quoc Huy
---

# Recent News

<ul>
{% for post in site.posts limit:5 %}
  <li>
    {{ post.date | date: "%b %d, %Y"  }} &mdash; <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

---

# Research Projects

---

<table class='project-list'>
  <tr>
    <th>Image</th>
    <th>Title and Summary</th>
  </tr>
{% for project in site.projects %}
  <tr> 
      <td> <img src="{{ project.image }}" class="project-rep-image"> </td>
      <td>  <p class="project-title"> {{ project.title }} </p>
      		<p class="project-doi"> <b> URI: </b> {{ project.doi }} </p>
      		<p class="project-authors"> <b> Authors: </b> {{ project.authors }} </p>
      		<p class="project-abstract"> <b> Abstract: </b> {{ project.abstract }} </p>
      </td>
  </tr>
{% endfor %}
</table>