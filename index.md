---
layout: default
title: "Lisha Li"
---

I am currently a third year graduate student at UCLA working with [Ameet Talwalkar](http://www.cs.cmu.edu/~atalwalk/).  I will be transferring to [Carnegie Mellon University](https://www.ml.cmu.edu/) in January 2018.

## Research Interests
My research interests encompass the following areas:
* automated machine learning
* hyperparameter optimization
* active learning
* bandits
* gaussian processes
* deep learning 

## Recent Updates
* October 2017: Poster at [SCMLS](https://sites.google.com/view/socalml17/home)
	* Parallelizing Hyperband for Large-Scale Tuning
* Summer 2017:  Intern at Google Research
	* Worked with [Afshin Rostamizadeh](https://research.google.com/pubs/author36233.html) and Jean-Fran&#x00E7;ois Kagy on active learning.
* April 2017: Poster at ICLR
	* [Hyperband: Bandit-Based Configuration Evaluation for Hyperparameter Optimization](https://openreview.net/pdf?id=ry18Ww5ee)
	* Student Volunteer
	* Awarded Travel Grant
* November 2016: Poster and talk at SCMLS
	* Best Student Talk Award


<div class="toc">
  <h2>Blog Posts</h2>
  <ul class="texts">
  {% for item in site.texts %}
  
    <li class="text-title">
      {{ item.date | date: "%B %-d, %Y" }}
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
