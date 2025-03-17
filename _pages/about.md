---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! 👋 I'm **Ziming Li**, currently a Ph.D. candidate in Computing and Information Sciences at Rochester Institute of Technology (RIT), advised by Dr. [Roshan Peiris](https://www.roshanpeiris.com/).

My research focuses on integrating Large Language Model (LLM)-driven agents within Virtual Reality (VR) environments. I explore their potential applications in everyday communication scenarios and training programs, particularly targeting individuals with intellectual and developmental disabilities (IDD).

I'm a member of the [CAIR](https://cair.rit.edu) (Center for Accessibility and Inclusion Research) Lab and the [AIR](https://www.ritairlab.org) (Accessible and Immersive Realities) Lab. I am passionate about applying cutting-edge technology to develop accessible and inclusive tools, especially in VR.

Beyond academia, I’m also a digital media artist, designer, and Chinese-language writer. I enjoy crafting immersive narratives, interactive experiences, and digital artworks.

## Publications

{% if site.author.googlescholar %}
  <div class="wordwrap"><i>You can also find my articles on my Google Scholar <a href="{{site.author.googlescholar}}">profile</a>.</i></div>
  <br>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
    {% for post in site.publications reversed %}
      {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Projects

<div class="wordwrap"><i>Visit my <a href="https://www.ritairlab.org/team/ziming-li" target="_blank" rel="noopener noreferrer">profile</a> on our lab website to learn more about my projects.</i></div>
