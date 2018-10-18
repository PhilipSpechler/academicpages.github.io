---
layout: archive
title: "Projects"
permalink: /research/
author_profile: true
---
{% for post in site.research reversed %}
  {% include archive-single-research.html %}
{% endfor %}

Hello, World of Research!

My time in grad school has been spent working on neuroimaging and data scientific approaches to substance abuse in vulnerable populations.

## Cannabis Use in Adolescence
1.) What is different about the brains of teens who use cannabis compared to teens who don't?

To answer this question, we selected teens (age 14) from the IMAGEN project who reported using any amount of cannabis by age 14. We then 
selected a matched group of teens who never used cannabis. We examined what their brains looked like while processing emotional stimuli 
while undergoing an fMRI brain scan. When comparing the two groups, we found the brains of the cannabis users 
reacted differently when viewing angry and neutral faces.

Conclusions: Teens who use cannabis show higher reactivity in a key brain region involved in threat monitoring (the amygdala).
<a href="https://philipspechler.github.io/publication/Publication1_Spechler_DCN_2015">Click here to read the paper!</a>

2.) Why do some teens use cannabis and others don't? Is there something about their brains, genetics, or behaviors that might predict 
their cannabis use before it even begins? 

To answer this question, we selected teens from the IMAGEN project who were cannabis-naive at age 14 and then go on to report using 
cannabis by age 16. We then analyzed a massive ammount of data collected at their age 14 assessment to see if anything might
predict their cannabis use later in life. Males and females were analyzed separately, and then the predictors for one sex were tested on 
the other. A similar attempt was made to see if the predictors of cannabis use generalize to other drug use behaviors (binge drinking).

Conclusions: Machine learning methods uncovered a sparse set of sex-specific predictors of cannabis use that predicted out of sample 
observations for one sex, but failed to predict use in the other sex or predict use in a related sample of same-sex binge drinkgers. 
<a href="https://philipspechler.github.io/publication/Publication2_Spechler_EJN_2018">Click here to read the paper!</a>

## Cigarette Use in Adults & Vulnerable Populations
*coming soon*

## Programming Projects
I dabble quite a bit in computer programming (mostly python & some bash) and have written scripts to do a million and one things. Here is 
just a sampling of what I put up on my github.  
* Wrote a little command line tool to quickly display info about csvfiles.
  * Make wondering what's inside all your data matrices <a href="https://github.com/PhilipSpechler/csvnome">a thing of the past.</a>.
* Set up neuroimaging processing streams (HCP pipelines) on the <a hrefs="https://www.uvm.edu/vacc">uvm high performance computing cluster
</a>.
  * Check out <a href="https://github.com/PhilipSpechler/fMRI-HeadMotion-Checker">this script</a> that piggy backs of the HCP pipelines to 
  give you fMRI headmotion estimates and nice graphs.  
* Wrote this python wrapper around AFNI to help partially <a href="https://github.com/PhilipSpechler/Visual_QC_for_MRI_Datasets">automate 
 visual QC</a> of large data sets.
  * Automatically displays brain scans and logs QC notes.
  * Makes visual QC a breeze for any and all staff members.
