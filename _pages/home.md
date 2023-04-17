---
layout: splash
permalink: /splash
hidden: true
header:
  # overlay_color: "#5e616c"
  overlay_image: ../assets/img/splash-page-banner.jpg
  # actions:
  #   - label: "<i class='fas fa-download'></i> Install now"
  #     url: "/docs/quick-start-guide/"
title: " 👋 Hi, I'm WJ"
excerpt: >
  I'm a robotics engineer and hobby tinkerer passionate about combining technology and creativity.<br> 
  Join me as I share my projects, insights, and some fun things here.
feature_row:
  - image_path: assets/img/shibabo/shibabo.JPG
    alt: "customizable"
    title: "SHIBABO"
    excerpt: "A one-of-a-kind keyboard, crafted with love for my beloved."
    url: "/wip/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  # - image_path: https://picsum.photos/200/150
  #   alt: "fully responsive"
  #   title: "Project 002"
  #   excerpt: "Something's cooking..."
  #   url: "/wip/"
  #   btn_class: "btn--primary"
  #   btn_label: "Learn more"
  # - image_path: https://picsum.photos/200/150
  #   alt: "100% free"
  #   title: "Project 003"
  #   excerpt: "Anytime now..."
  #   url: "/wip/"
  #   btn_class: "btn--primary"
  #   btn_label: "Learn more"      
---

## Check out some of my projects

{% include feature_row %}

## Latest Articles

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in posts %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

{% include paginator.html %}
