---
layout: reports
permalink: /fall2020/reports/
title: Completed Student Projects
description: Computational resources for student projects were generously provided by <a href="https://aws.amazon.com/education/awseducate/" target="_blank">AWS Educate</a>.
---

{% for project in site.data.reports %}

<tr>
    <td align="left">{{ forloop.index }}</td>
    <td align="left">
    <strong>{{ project.title }}</strong><br/>
    {% for author in project.authors %}
    {%   if author.url %}
    <a href="{{author.url}}">{{author.name}}</a>{% unless forloop.last %},{% endunless %}
    {%   else %}
    {{author.name}}{% unless forloop.last %},{% endunless %}
    {%   endif %}
    {% endfor %}
    </td>
    <td align="left"><a href="{{ project.path | relative_url }}">report</a></td>
</tr>

{% endfor %}
