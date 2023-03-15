---
layout: archive
title: " "
permalink: /research/
author_profile: true
---
<p style="text-align:center; color:Blue; font-size:30px; font-weight:bold;"> Projects </p>

<p style="text-align:left; color: Green; font-size:20px; font-weight:bold;"> I. Postdoctoral Research Fellow, Civil Engineering Department, The University of British Columbia </p>

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research: Cement-based/geopolymer composites for bio-corrosion resistance in sewage pipelines (Jan-Dec 2023) </p>

* Developing low-carbon materials and their placement technologies as a repair coating, which can cost-effectively prolong the lifespan of sewer infrastructure through enhanced resistance to Microbial Induced Corrosion (MIC)






<p style="text-align:left; color: Green; font-size:20px; font-weight:bold;"> II. Doctor of Philosophy, Materials Engineering Department, The University of British Columbia </p>

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research: Fly ash-based geopolymers for immobilization of nuclear waste containing cesium (2016-2022) </p>

 *	Investigated the effects of process parameters on the geopolymer’s synthesis, microstructure, phase compositions, and cesium immobilization using factorial experimental design and ANOVA
 *	Studied the kinetics of zeolite crystallization in FA-GP systems and established its relation to Cs immobilization
 *	Achieved significantly enhanced Cs immobilization via a one-step synthesis and chemical route 
 






<p style="text-align:left; color: Green; font-size:20px; font-weight:bold;"> III. Junior Research Fellow, Materials Research Center, Indian Institute of Science (IISc), Bangalore, India </p>

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 1: Salicylic acid–PCL based biodegradable polymeric implant for cancer therapy and anti-cancer applications (Dec 2015-May 2016) </p>

   * Prepared and evaluated salicylic acid-based polymer delivering an anticancer drug for post-surgical chemotherapy against cancer xenografts
   * Assessed its in vitro drug release profile
   * Analyzed the post degradation products

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 2: Development of particulate reinforced boron carbide-based composites for high temperature application, in collaboration with Bhabha Atomic Research Center, India (Dec 2015-May 2016) </p>

   * Synthesized materials for neutron absorbance in nuclear reactors
   * Characterized the thermal, themo-electrical, electrical and mechanical properties of these materials 

<p style="text-align:left; color: black; font-size:18px; font-weight:bold;"> Research 3: BrahMos Project; Ultra high temperature ceramics for hypersonic vehicle applications (Dec 2015-May 2016)</p>

 * Assisted in synthesizing ZrB<sub>2</sub> based ultra-high temperature ceramics








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
