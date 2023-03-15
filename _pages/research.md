---
layout: archive
title: " "
permalink: /research/
author_profile: true
---
<p style="text-align:center; color:Blue; font-size:30px; font-weight:bold;"> Projects </p>

<p style="text-align:left; color: Green; font-size:20px; font-weight:bold;"> Postdoctoral Research Fellow, Civil Engineering Department, The University of British Columbia, Jan 2023 till current </p>

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 1: Cement-based/geopolymer composites for bio-corrosion resistance in sewage pipelines </p>

* Developing low-carbon materials and their placement technologies as a repair coating, which can cost-effectively prolong the lifespan of sewer infrastructure through enhanced resistance to Microbial Induced Corrosion (MIC)
   

<p style="text-align:left; color: Green; font-size:20px; font-weight:bold;"> Junior Research Fellow, Materials Research Center, Indian Institute of Science (IISc), Bangalore, India </p>

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 1: Salicylic acid –PCL based biodegradable polymeric implant for cancer therapy and anti-cancer applications </p>

   * Prepared and evaluated salicylic acid-based polymer delivering an anticancer drug for post-surgical chemotherapy against cancer xenografts
   * Assessed its in vitro drug release profile
   * Analyzed the post degradation products

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 2: Board of Research in Nuclear Sciences (BRNS) project; “Development of particulate reinforced boron carbide-based composites for high temperature application” in collaboration with Bhabha Atomic Research Center, India </p>

   * Synthesized materials for neutron absorbance in nuclear reactors
   * Characterized the thermal, themo-electrical, electrical and mechanical properties of these materials 

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 3: BrahMos Project; Ultra high temperature ceramics (UHTC’s) for hypersonic vehicle applications </p>

 * Synthesized ZrB<sub>2</sub> based ultra-high temperature ceramics
 * Studied the thermal, electrical and mechanical properties of these materials

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
