---
layout: archive
title: " "
permalink: /research/
author_profile: true
---
<p style="text-align:center; color:Blue; font-size:30px; font-weight:bold;"> Projects </p>

<p style="text-align:left; color:Dark Green; font-size:22px; font-weight:bold;"> Junior Research Fellow, Materials Research Center, Indian Institute of Science (IISc), Bangalore </p>

<i><b>Research 1</b>: Salicylic acid –PCL based biodegradable polymeric implant for cancer therapy and anti-cancer applications</i>
   * Prepared and evaluated salicylic acid-based polymer delivering an anticancer drug for post-surgical chemotherapy against cancer xenografts
   * Assessed its in vitro drug release profile
   * Analyzed the post degradation products

<i><b>Research 2</b>: Board of Research in Nuclear Sciences (BRNS) project; “Development of particulate reinforced boron carbide-based composites for high temperature application” in collaboration with Bhabha Atomic Research Center, India, Supervisors: Prof. Bikramjit Basu, Dr. Tarashankar Mahata, Dr. T.S.R Ch Murthy and Dr. Sairam</i> 
   * Synthesized materials for neutron absorbance in nuclear reactors
   * Characterized the thermal, themo-electrical, electrical and mechanical properties of these materials 

<i><b>Research 3</b>: BrahMos Project; Ultra high temperature ceramics (UHTC’s) for hypersonic vehicle applications, Supervisors: Prof. Bikramjit Basu, mentors: Ms. Ragini Mukherjee, Mr. Gopinath and Mr. Anupam Purwar</i>  
 * Synthesized ZrB<sub>2</sub> based ultra-high temperature ceramics
 * Studied the thermal, electrical and mechanical properties of these materials



**Project-2**
   * laskhsaldkhg
   * asgsadgsag
   * asdgsagdsadg

<p style="text-align:center; color:Blue; font-size:30px; font-weight:bold;"> Conference Presentations </p>

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
