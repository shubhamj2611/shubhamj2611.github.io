---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
**Journal articles**

<ol>

{% assign pubs = site.data.publications.references | sort: "year" | reverse %}
{% for pub in pubs %}
   {% if pub.article == "Journal" %}
      <li>
         <b> {{ pub.title }} </b>
         <br>
         {% for name in pub.author %}
            {{ name.given }} {{ name.family }},
         {% endfor %}
         <br>
         <i> {{ pub.journal }} </i>,
         {{ pub.year }},
         DOI: <a target="_blank" href="{{ pub.DOI }}"><span class="tag is-danger">{{ pub.DOI }}</span></a>
      </li>
   {% endif %}
{% endfor %}

</ol>

**Book Chapters**

<ol>

{% assign pubs = site.data.publications.references | sort: "year" | reverse %}
{% for pub in pubs %}
   {% if pub.article == "Book" %}
      <li>
         <b> {{ pub.title }} </b>
         <br>
         {% for name in pub.author %}
            {{ name.given }} {{ name.family }},
         {% endfor %}
         <br>
         <i> {{ pub.book }} </i>,
         {{ pub.year }},
         DOI: <a target="_blank" href="{{ pub.DOI }}"><span class="tag is-danger">{{ pub.DOI }}</span></a>
      </li>
   {% endif %}
{% endfor %}

</ol>


**Thesis**

<ol>

{% assign pubs = site.data.publications.references | sort: "year" | reverse %}
{% for pub in pubs %}
   {% if pub.article == "Thesis" %}
      <li>
         <b> {{ pub.title }} </b>
         <br>
         {% for name in pub.author %}
            {{ name.given }} {{ name.family }}
         {% endfor %}
         <br>
         <i> {{ pub.University }} </i>,
         {{ pub.year }},
         DOI: <a target="_blank" href="{{ pub.DOI }}"><span class="tag is-danger">{{ pub.DOI }}</span></a>
      </li>
   {% endif %}
{% endfor %}

</ol>
