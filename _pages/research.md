---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<style>
.research-section {
    display: flex;
    align-items: center;
    gap: 30px;
    margin-bottom: 50px;
    padding: 20px;
    background: transparent;
    border-radius: 10px;
    border: 1px solid rgba(128, 128, 128, 0.2);
}

.research-section img {
    width: 300px;
    height: 300px;
    object-fit: contain;
    object-position: center;
    border-radius: 10px;
    flex-shrink: 0;
}

.research-section .text {
    flex: 1;
}

.research-section h3 {
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 22px;
}

.research-section .text p {
    font-size: 0.9em;
    line-height: 1.5 !important;
    margin-bottom: 15px;
}

.research-section.reverse {
    flex-direction: row-reverse;
}

.research-intro {
    margin-bottom: 35px;
}

.research-intro p {
    font-size: 0.95em;
    line-height: 1.6 !important;
}

@media (max-width: 768px) {
    .research-section,
    .research-section.reverse {
        flex-direction: column;
    }

    .research-section img {
        width: 100%;
        height: auto;
    }

    .research-section h3 {
        font-size: 20px;
    }

    .research-section p {
        font-size: 15px;
    }
}
</style>


<div class="research-intro">
<p>My research lies at the intersection of <strong>attention, early visual processing, and visual perception</strong>. I am particularly interested in how cognition shapes what we see—and how early in the visual system these influences emerge.</p>
</div>


<!-- Attention -->
<div class="research-section">
    <img src="{{ '/images/attention.jpg' | relative_url }}" alt="Attention">
    <div class="text">
        <h3>Attention</h3>
        <p>I am interested in how attention changes the way visual information is processed, particularly when attention is directed covertly, without accompanying eye movements. My work examines how attentional selection affects physiological responses such as pupil size and neural activity, and how early in the visual processing hierarchy these effects emerge.</p>
    </div>
</div>


<!-- Early Visual Processing -->
<div class="research-section reverse">
    <img src="{{ '/images/visual-processing.png' | relative_url }}" alt="Early visual processing">
    <div class="text">
        <h3>Early Visual Processing</h3>
        <p>A central question in my research is how early cognitive influences on vision emerge. Can processes such as attention alter sensory processing already at the level of the eye, or do these effects arise only later in the brain? I address this question using converging physiological measures, including pupillometry, electroretinography (ERG), and electroencephalography (EEG).</p>
    </div>
</div>


<!-- Visual Perception -->
<div class="research-section">
    <img src="{{ '/images/visual-perception.jpg' | relative_url }}" alt="Visual perception">
    <div class="text">
        <h3>Visual Perception</h3>
        <p>I am interested in the relationship between physical visual input and our subjective perceptual experience. Using phenomena such as perceptual fading and afterimages, I investigate what happens when what we consciously see diverges from the information that remains physically present in the environment, and how attention interacts with these perceptual representations.</p>
    </div>
</div>
