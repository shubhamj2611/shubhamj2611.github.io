---
layout: archive
title: " "
permalink: /research/
author_profile: true
---
# Projects

1. **Project-1**
   * laskhsaldkhg
   * asgsadgsag
   * asdgsagdsadg


2. **Project-2**
   * laskhsaldkhg
   * asgsadgsag
   * asdgsagdsadg

# Conference Presentations

<ol>

{% assign pubs = site.data.publications.references | sort: "year" | reverse %}
{% for pub in pubs %}
   {% if pub.article == "Conference" %}
      <li>
         <b> {{ pub.title }} </b>
         <br>
         {% for name in pub.author %}
            {{ name.given }} {{ name.family }},
         {% endfor %}
         <i> {{ pub.conference }} </i>,
         {{ pub.year }}
      </li>
   {% endif %}
{% endfor %}

</ol>


<!-- # xxx

1. **xxx-1**
   * laskhsaldkhg
   * asgsadgsag
   * asdgsagdsadg


2. **xxx-2**
   * laskhsaldkhg
   * asgsadgsag
   * asdgsagdsadg -->
