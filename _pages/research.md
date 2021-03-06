---
layout: single
title: "Projects"
permalink: /research/
author_profile: true
---
{% for post in site.research reversed %}
  {% include archive-single-research.html %}
{% endfor %}

Hello, World of Research!

My time in grad school has been spent working on neuroimaging and data scientific approaches to substance abuse research.
Here are some projects that kept me busy, and some links to my github for some of my code I've developed along the way.

## Cannabis Use in Adolescence
<div style="text-align: justify">
<p>
  1.) What is different about the brains of teenagers who use cannabis?</p>
<p>To answer this question, we selected teenagers from the IMAGEN project who reported using any amount of cannabis by age 14. We then 
selected a matched group of teens who never used cannabis. We examined what their brains looked like while processing emotional stimuli 
while undergoing an fMRI brain scan. When comparing the two groups, we found the brains of the cannabis users 
reacted differently when viewing angry and neutral faces.</p>
<p>Conclusions: Teens who use cannabis show higher reactivity in a key brain region involved in threat monitoring (the amygdala).  
<a href="https://philipspechler.github.io/publication/Publication1_Spechler_DCN_2015">Click here to read the paper!</a></p>
</div>

<div style="text-align: justify">
<p>
2.) Why do some teenagers use cannabis and others don't? Is there something about their brains, genetics, or behaviors that might predict 
their cannabis use before it even begins? </p>
<p>To answer this question, we selected teens from the IMAGEN project who were cannabis-naive at age 14 and then go on to report using 
cannabis by age 16. We then analyzed a massive ammount of data collected at their age 14 assessment to see if anything might
predict their cannabis use later in life. Males and females were analyzed separately, and then the predictors for one sex were tested on 
the other. A similar attempt was made to see if the predictors of cannabis use generalize to other drug use behaviors (binge drinking).
</p>
<p>Conclusions: Machine learning methods uncovered a sparse set of sex-specific predictors of cannabis use that predicted out of sample 
observations for one sex, but failed to predict use in the other sex or predict use in a related sample of same-sex binge drinkers. 
<a href="https://philipspechler.github.io/publication/Publication2_Spechler_EJN_2018">Click here to read the paper!</a></p>
</div>

## Cigarette Use in Adults & Vulnerable Populations
<div style="text-align: justify">
<p>
  1.Does varying the amount of nicotine in cigarettes have an effect on the brain?</p>
<p>We are currently collecting data for a large study on tobacco regulatory science, funded by the FDA. In this study of three specific 
vulnerable populations (low-SES women, opioid use disorder, and mood disorders), we will be giving fMRIs to individuals before and after 
12-weeks of smoking very low nicotine content cigarettes. We hypothesize to identify changes in the brain that correlate with a 
reduction in smoking behaviors.</p>
</div>

## Programming Projects
<div style="text-align: justify">
<p>
I dabble quite a bit in computer programming (mostly python & some bash) and have written scripts to do a million and one things. Here is 
just a sampling of what I put up on my github.  
<ul>
  <li>Wrote a little <a href="https://github.com/PhilipSpechler/csvnome">command line tool</a> to quickly display info about csvfiles.
    <ul><li>Make wondering what's inside all your data matrices a thing of the past</li></ul>
</li>
<li>Set up neuroimaging processing streams (HCP pipelines) on the <a href="https://www.uvm.edu/vacc">UVM computing cluster</a>.
  <ul><li>Check out <a href="https://github.com/PhilipSpechler/fMRI-HeadMotion-Checker">this script</a> that piggy backs of the HCP
    pipelines to give you fMRI headmotion estimates and nice graphs.
    </li></ul>
    </li>
<li>Wrote this python wrapper around AFNI to help partially <a href="https://github.com/PhilipSpechler/Visual_QC_for_MRI_Datasets">automate 
 visual QC</a> of large data sets.
  <ul><li>Automatically displays brain scans and logs QC notes.</li></ul>
   <ul><li>Makes visual QC a breeze for any and all staff members.</li></ul>
   </li>
</ul>
</p>
