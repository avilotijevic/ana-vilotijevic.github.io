---
layout: archive
title: ""
permalink: /outreach/
author_profile: true
---

<style>

.outreach-intro {
    margin-bottom: 35px;
}

.outreach-intro h1 {
    margin-bottom: 12px;
}

.outreach-intro p {
    font-size: 0.95em;
    line-height: 1.6;
    max-width: 850px;
}


/* CARD GRID */

.outreach-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
    margin-top: 30px;
    margin-bottom: 50px;
}

.outreach-card {
    border: 1px solid rgba(128, 128, 128, 0.25);
    border-radius: 10px;
    overflow: hidden;
    background: transparent;
    display: flex;
    flex-direction: column;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.outreach-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 18px rgba(0,0,0,0.08);
}


/* IMAGE */

.outreach-card img {
    width: 100%;
    height: 190px;
    object-fit: cover;
    display: block;
}


/* CARD CONTENT */

.outreach-content {
    padding: 20px;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
}

.outreach-content h3 {
    margin-top: 10px;
    margin-bottom: 10px;
    font-size: 20px;
}

.outreach-content p {
    font-size: 0.88em;
    line-height: 1.5;
    margin-bottom: 20px;
}


/* TAGS */

.outreach-tag {
    display: inline-block;
    align-self: flex-start;
    padding: 4px 11px;
    border-radius: 15px;
    font-size: 0.78em;
    font-weight: 500;
}

.podcast-tag {
    background: #dcefff;
    color: #12639b;
}

.blog-tag {
    background: #e1f4df;
    color: #34733a;
}

.thesis-tag {
    background: #eee5ff;
    color: #6244a6;
}


/* LINKS */

.outreach-link {
    margin-top: auto;
    font-weight: 600;
    font-size: 0.9em;
    text-decoration: none !important;
}

.outreach-link:hover {
    text-decoration: underline !important;
}


/* MOBILE */

@media (max-width: 1000px) {
    .outreach-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 650px) {
    .outreach-grid {
        grid-template-columns: 1fr;
    }

    .outreach-card img {
        height: 220px;
    }
}

</style>


<div class="outreach-intro">

<h1>Public Outreach</h1>

<p>
I enjoy communicating science beyond academia and making research accessible to a broader audience. Here you can find some of my science communication, interviews, and other work aimed at sharing research beyond scientific publications.
</p>

</div>


<div class="outreach-grid">


<!-- PODCAST -->

<div class="outreach-card">

<img src="{{ '/images/open-science-bites.jpg' | relative_url }}" alt="Open Science Bites podcast">

<div class="outreach-content">

<span class="outreach-tag podcast-tag">Podcast</span>

<h3>Open Science Bites</h3>

<p>
In this episode, I talk about my experience with open research and registered reports, and discuss how preregistration can shift the emphasis in science from exciting results toward asking good questions and conducting rigorous research.
</p>

<a class="outreach-link"
   href="https://podcasts.apple.com/us/podcast/open-research-award-case-study-a-registered-report/id1677625886?i=1000789553851"
   target="_blank">
   Listen to the podcast →
</a>

</div>
</div>



<!-- BLOG -->

<div class="outreach-card">

<img src="{{ '/images/seeing-the-unseen.jpeg' | relative_url }}" alt="Seeing the Unseen blog">

<div class="outreach-content">

<span class="outreach-tag blog-tag">Blog</span>

<h3>Seeing the Unseen</h3>

<p>
Can your pupils reveal what you are paying attention to—even when you can no longer consciously see it? In this Mindwise article, I explain how attention, perception, and pupil size interact, and what perceptual fading can tell us about the mind.
</p>

<a class="outreach-link"
   href="https://mindwise-groningen.nl/seeing-the-unseen/"
   target="_blank">
   Read the blog →
</a>

</div>
</div>



<!-- THESIS -->

<div class="outreach-card">

<img src="{{ '/images/cover-AVILOTIJEVIC.png' | relative_url }}" alt="The Eye's Mind PhD thesis">

<div class="outreach-content">

<span class="outreach-tag thesis-tag">PhD Thesis</span>

<h3>The Eye's Mind</h3>

<p>
My PhD dissertation, <em>The Eye's Mind: Cognitively driven pupil-size changes</em>, explores how cognition—particularly attention—shapes pupil size and what these changes reveal about the interaction between cognition, visual perception, and sensory processing.
</p>

<a class="outreach-link"
   href="https://research.rug.nl/en/publications/the-eyes-mind-cognitively-driven-pupil-size-changes/"
   target="_blank">
   View the thesis →
</a>

</div>
</div>


</div>
