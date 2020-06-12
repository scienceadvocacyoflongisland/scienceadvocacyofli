---
layout: splash
title: ""
permalink: /splash-page2/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_filter: "0.50"
  overlay_image: /assets/images/homepage/longislandSplash.png
  actions:
    - label: "Learn More"
      url: "/about/"
excerpt: "We bring together scientists and supporters of science from all backgrounds to advocate for scientific education and legislation."
feature_row0:
  - image_path: assets/images/homepage/eventsExample.png
    alt: "Events"
    title: "Events"
    excerpt: "See our upcoming and past events"
    url: /events/
    btn_label: "More Info"
    btn_class: "btn--primary"
  - image_path: /assets/images/homepage/resourceCenter.jpg
    alt: "Resource Center"
    title: "Resource Center"
    excerpt: "We've compiled a list of reputable resources on various topics you've asked about. We've also compiled resources for kids, as well as books, podcasts, and general items of interest."
    url: "/resources/"
    btn_label: "View Resources"
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

{% include feature_row id="feature_row0" type="center"%}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}