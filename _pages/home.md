---
layout: splash
permalink: /
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
  - image_path: https://raw.githubusercontent.com/vstoneofficial/amir740_ros/master/images/amir-1.png
    alt: "amir-740"
    title: "AMIR 740"
    excerpt: "From Vision to Reality: My Journey as First-Time Developer & Project Manager"
    url: "/amir/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: assets/img/ros.png
    alt: "ros"
    title: "ROS implementation"
    excerpt: "Powering robots of all shapes and sizes with my versatile ROS toolkit."
    url: "/ros/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: assets/img/shibabo/shibabo.JPG
    alt: "customizable"
    title: "SHIBABO"
    excerpt: "A one-of-a-kind keyboard, crafted with love for my beloved."
    url: "/projects/shibabo/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---

## Check out some of my projects

{% include feature_row %}

<!-- ## Latest Articles

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

{% include paginator.html %} -->
