---
layout: page
title: About
permalink: /about/
myname: jamil
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

we have the following staff members

{% for staff_member in site.staff_members %}

 <h2>{{ staff_member.name }} - {{ staff_member.age }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}

<ul>
{% for member in site.data.members %}
  <li>
    <a href="https://github.com/{{ member.github }}">
      {{ member.name }}
    </a>
  </li>
{% endfor %}
</ul>
