---
title: Home
nav:	
  order: 1
  
carousels:
  - images: 
    - image: /images/carousel/Mito.gif
    - image: /images/carousel/er-rearrangement.gif
    - image: /images/carousel/fit_Vapb.gif
    
---

<!--
# **<u>Microscopy and beyond</u>**
-->
The <b>Obara Lab</b> is a team of creative, open-minded individuals working together, trying to address the big questions in cell biology and biophysics. <i>What is life? How does metabolism work? What causes aging? </i> We believe living systems are dynamic, responsive, and inherently complex—and this makes them perfect for quantitative, live cell imaging and high-resolution ultrastructural analysis. Our strategy is developing and integrating the <b>next generation of imaging technologies</b> with classical techniques in <b>biochemistry, statistical physics, and structural biology</b>. We are proud to perform most of our work collaboratively with amazing colleagues and are committed to sharing our tools freely with the wider scientific community.
{% include carousel.html height="40" unit="%" duration="12" %}

{% include section.html %}
# **<u>Philosophy</u>**

<ul>
<li>We believe that the truth is inherently worth pursuing, even when inconvenient.</li> 
<li>We believe that the scientific method is the most reliable way to pursue truth—though our experiments or interpretation can be flawed, the process is inherently self-correcting (eventually).</li>
<li>We believe that diverse experiences, backgrounds, and perspectives make us stronger, so we strive to bring new perspectives to the fundamental cellular systems we study.</li>  
<li>We believe our field is made up of colleagues, not competitors—so we are committed to sharing our data, reagents, and ideas as freely as possible. </li> 
<li>We believe that thoughtful, open discussion and careful experiments can help us solve many of humanity’s great health challenges—aging, cancer, neurodegenerative diseases—and far beyond.</li>
</ul>


{% include section.html %}


{% capture text %}

Overview of research projects 
{: style="font-size: var(--xl); text-align: center;"}

{%
  include button.html
  link="projects"
  text="Projects"
  icon="fa-solid fa-arrow-right"
%}

{% endcapture %}



{%
  include feature.html
  image="images/hela.png"
  link="projects"
  text=text
%}


{% capture text %}

Overview of tools and technology 
{: style="font-size: var(--xl); text-align: center;"}

{%
  include button.html
  link="technology"
  text="Technology"
  icon="fa-solid fa-arrow-right"  
%}

{% endcapture %}



{%
  include feature.html
  image="images/microscope-colored.jpg"
  link="projects"
  text=text
  flip=true
%}


{% capture text %}

Published works from our lab. 
{: style="font-size: var(--xl); text-align: center;"}


{%
  include button.html
  link="publication"
  text="Publications"
  icon="fa-solid fa-arrow-right"
   
%}

{% endcapture %}

{%
  include feature.html
  image="images/ER-coloredZ.jpg"
  link="research"
  text=text
%}


{% capture text %}

Familarize yourself with our group.
{: style="font-size: var(--xl); text-align: center;"}

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  
%}

{% endcapture %}
{%
  include feature.html
  image="images/LAB/trio.png"
  link="team"
  text=text
  flip=true
%}

