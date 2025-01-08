---
layout: home
permalink: /
title: ""
image:
  feature: NYC.PNG
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<figure>
    <img src="/images/me.jpg"
         alt="Kyle" width = 300> 
    <figcaption>Kyle Ford, circa recently.</figcaption>
</figure>

# Hi there
If you're on this site, you're probably trying to learn a bit more about me. I'm currently the head of AI at a stealth biotechnology startup ([pi.bio](https://www.pi.bio/)) focused on targeting protein-protein interactions therapeutically. I previously worked as a scientific advisor at Eli Lilly, and prior to that I have held various academic research positions. 

My work focuses on using computational and synthetic biology to accelerate the development of next-generation medicines. I have had a long interest in developing parallelized methods for screening biotherapeutics, and have been lucky enough to work across many interesting modalities (ex. small molecules, recombinant proteins/peptides, gene therapies, etc.). We can move a lot faster if we test things in parallel, and drug development definitely needs speeding up.

# Brief bio
I received a BS in [chemical engineering](https://che.utexas.edu/) in 2016 from the University of Texas at Austin, and a 
PhD in [bioengineering](https://be.ucsd.edu/) in 2022 from the
University of California, San Diego; My PhD advisor was [Prashant Mali](http://mali.ucsd.edu/). I grew up in central Texas, and currently live in New York City with my wife Mia. 

# Research interests
I am broadly curious, and am not particularly focused on any one disease. At work, I largely focus on questions like:
- How do we design better protein therapeutics for hard to drug targets? How can we test them with greater throughput (ideally in a pooled format)?
- How do we analyze and model large scale screening datasets, which often have millions of observations from each animal/condition?
- What targets/diseases are the most in need of innovative new medicines?
- How can we accelerate the commercialization of a novel medicine?

Outside of my day job:
- I'm deeply interested in art, economics, and human behavior (sometimes the intersection of these).
- I am most likely reading, riding my bike, or playing tennis/basketball.
