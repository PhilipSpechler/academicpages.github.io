---
layout: archive
title: "Projects"
permalink: /research/
author_profile: true
---
My time in grad school has been spent working on neuroimaging and data scientific approaches to substance abuse in vulnerable populations.

# Programming Projects
I dabble quite a bit in computer programming (mostly python & some bash) and have written scripts to do a million and one things. Here is 
just a sampling of what I put up on my github.  
* Wrote a little command line tool to quickly display info about csvfiles.
  * Make wondering what's inside all your data matrices [a thing of the past](https://github.com/PhilipSpechler/csvnome).
* Set up neuroimaging processing streams (HCP pipelines) on the [uvm high performance computing cluster](https://www.uvm.edu/vacc)
  * Check out [this script](https://github.com/PhilipSpechler/fMRI-HeadMotion-Checker) that piggy backs of the HCP pipelines to give you 
  fMRI headmotion estimates and nice graphs.  
* Wrote this python wrapper around AFNI to help partially [automate visual QC](https://github.com/PhilipSpechler/Visual_QC_for_MRI_Datasets) of large data sets.
  * Automatically displays brain scans and logs QC notes.
  * Makes visual QC a breeze for any and all staff members. 


Hello, World of Research!


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
