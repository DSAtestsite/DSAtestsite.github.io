---
title: ""
layout: splash
permalink: /home/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/mm-home-page-feature.jpg
  actions:
    - label: "Learn more about us"
      url: "/about"
excerpt: "We organize to build workplace democracy, demand a right to housing, confront immigration detention profiteers, stand up to Amazon, ensure a just transition, and fight fascism."
intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Get involved!"
    excerpt: "Learn how to get involved with our campaigns and other actions."
    url: /structure-and-campaigns
    btn_label: "Get Involved"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Upcoming Events"
    excerpt: "Happy Hours, Working Group meetings, Socialist Night Schools - look through our upcoming events."
    url: "https://www.meetup.com/mdcdsa/events/"
    btn_label: "Upcoming Events"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "What is Democratic Socialism?"
    excerpt: "Democratic socialists advocate for a radical restructuring of our economic and political systems to value people over profits."
    url: "/structure-and-campaigns"
    btn_label: "Upcoming Events"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
