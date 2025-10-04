---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! 👋 I'm **Ziming Li**, currently a Ph.D. candidate in Computing and Information Sciences at Rochester Institute of Technology (RIT), advised by Dr. [Roshan Peiris](https://www.roshanpeiris.com/){:target="_blank" rel="noopener noreferrer"}.

My research lies in the domains of Human-Computer Interaction (HCI), Virtual Reality (VR), and Accessibility. I focus on integrating Large Language Model (LLM)-driven agents into VR environments and exploring their potential in everyday communication scenarios and training programs, particularly for individuals with intellectual and developmental disabilities (IDDs).

I'm a member of the [CAIR](https://cair.rit.edu){:target="_blank" rel="noopener noreferrer"} (Center for Accessibility and Inclusion Research) Lab and the [AIR](https://www.ritairlab.org){:target="_blank" rel="noopener noreferrer"} (Accessible and Immersive Realities) Lab. I am passionate about applying cutting-edge technology to develop accessible and inclusive tools, especially in VR.

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

## Projects

<div class="wordwrap"><i>Visit my <a href="https://www.ritairlab.org/team/ziming-li" target="_blank" rel="noopener noreferrer">profile</a> on our lab website to learn more about my projects.</i></div>
