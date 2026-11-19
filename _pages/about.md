---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! 👋 I'm **Ziming Li**, an Assistant Professor in the Game Design Programme, School of Culture and Creativity at Beijing Normal-Hong Kong Baptist University (BNBU). I received my Ph.D. in Computing and Information Sciences from Rochester Institute of Technology (RIT), advised by Dr. [Roshan Peiris](https://www.roshanpeiris.com/){:target="_blank" rel="noopener noreferrer"}.

I work in Human-Computer Interaction (HCI), Game Design, Extended Reality (VR/AR/MR), and Accessibility. I build LLM-driven VR systems for everyday communication and workplace training, especially for people with intellectual and developmental disabilities (IDDs). More recently, I have also been designing mixed reality games and studying player experience.

During my time at RIT, I was a member of the [CAIR](https://cair.rit.edu){:target="_blank" rel="noopener noreferrer"} (Center for Accessibility and Inclusion Research) Lab and the [AIR](https://www.ritairlab.org){:target="_blank" rel="noopener noreferrer"} (Accessible and Immersive Realities) Lab, developing accessible and inclusive tools across VR and games.

Beyond academia, I’m also a web and VR/game programmer 🎮, designer 🎨, and Chinese-language writer ✍️. I enjoy crafting immersive narratives and interactive experiences.

## Publications

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap"><i>You can also find my articles on my Google Scholar <a href="{{site.author.googlescholar}}" target="_blank" rel="noopener noreferrer">profile</a>.</i></div>
  <br>
{% endif %} -->

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
    {% for post in site.publications reversed %}
      {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Research Projects

<!-- <div class="wordwrap"><i>Visit my <a href="https://www.ritairlab.org/team/ziming-li" target="_blank" rel="noopener noreferrer">profile</a> on our lab website to learn more about my projects.</i></div> -->

<div></div>

{% include base_path %}

<!-- New style rendering if publication categories are defined -->

<div class="grid-container">
  {% for post in site.projects reversed %}
    {% include archive-single-project.html %}
  {% endfor %}
</div>

## Creative Works

> Non-academic creative projects

### Games

{% include base_path %}

<div class="grid-container">
  {% for post in site.game_projects reversed %}
    {% include archive-single-project.html %}
  {% endfor %}
</div>


### Apps

{% include base_path %}

<div class="grid-container">
  {% for post in site.side_projects reversed %}
    {% include archive-single-project.html %}
  {% endfor %}
</div>

