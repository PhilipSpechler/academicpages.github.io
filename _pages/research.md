---
layout: archive
title: "Projects"
permalink: /research/
author_profile: true
---
Hello, World of Research!

My time in grad school has been spent working on neuroimaging and data scientific approaches to substance abuse in vulnerable populations.

## Cannabis Use in Adolescence
1. What is different about the brains of teens who use cannabis compared to teens who don't?

To answer this question, we selected teens (age 14) from the IMAGEN project who reported using any amount of cannabis by age 14. We then 
selected a matched group of teens who never used cannabis. We examined what their brains looked like while processing emotional stimuli 
while undergoing an fMRI brain scan. When comparing the two groups, we found the brains of the cannabis users 
reacted differently when viewing angry and neutral faces.

Conclusions: Teens who use cannabis show higher reactivity of a key brain region involved in threat monitoring (the amygdala)

[Click here to read the paper!](https://philipspechler.github.io/publication/Publication1_Spechler_DCN_2015)

2. Why do some teens use cannabis and others don't? Is there something about their brains, genetics, or behaviors that might predict their 
cannabis use before it even begins?


## Cigarette Use in Adults & Vulnerable Populations
*coming soon*

## Programming Projects
I dabble quite a bit in computer programming (mostly python & some bash) and have written scripts to do a million and one things. Here is 
just a sampling of what I put up on my github.  
* Wrote a little command line tool to quickly display info about csvfiles.
  * Make wondering what's inside all your data matrices <a href="https://github.com/PhilipSpechler/csvnome">a thing of the past.</a>.
* Set up neuroimaging processing streams (HCP pipelines) on the <a hrefs=https://www.uvm.edu/vacc>uvm high performance computing cluster.
</a>  
* Check out <a href="https://github.com/PhilipSpechler/fMRI-HeadMotion-Checker">this script</a> that piggy backs of the HCP pipelines to 
  give you fMRI headmotion estimates and nice graphs.  
  * Wrote this python wrapper around AFNI to help partially <a href="https://github.com/PhilipSpechler/Visual_QC_for_MRI_Datasets">automate 
 visual QC</a> of large data sets.
  * Automatically displays brain scans and logs QC notes.
  * Makes visual QC a breeze for any and all staff members. 


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
