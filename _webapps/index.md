---
topic: "Webapps"
desc: "A quick and dirty way to get a navigation bar"
permalink: /webapps/index.html
---

<div data-role="collapsible" data-collapsed="false">
  <h3>Web Apps</h3>
  <ul>
    {% for item in site.webapps %}
    <li {% if item.indent %} class="indent" {% endif %} ><a href="{{item.url}}">{{item.topic}}&mdash;{{item.desc}}</a></li>
 {% endfor %}
  </ul>
</div>



