---
layout: single
title: Gallery
permalink: /gallery/
collection: portfolio
header:
  overlay_image: /assets/images/photo9.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
entries_layout: grid
author_profile: false

gallery1:
  - url: /assets/images/jr-korpa-1.jpg
    image_path: /assets/images/jr-korpa-1.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/jr-korpa-2.jpg
    image_path: /assets/images/jr-korpa-2.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/jr-korpa-3.jpg
    image_path: /assets/images/jr-korpa-3.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"

gallery2:
  - url: https://flic.kr/p/8a6Ven
    image_path: https://farm2.staticflickr.com/1272/4697500467_8294dac099_q.jpg
    alt: "Black and grays with a hint of green"
  - url: https://flic.kr/p/8a738X
    image_path: https://farm5.staticflickr.com/4029/4697523701_249e93ba23_q.jpg
    alt: "Made for open text placement"
  - url: https://flic.kr/p/8a6VXP
    image_path: https://farm5.staticflickr.com/4046/4697502929_72c612c636_q.jpg
    alt: "Fog in the trees"
# class: full
---

<!-- {% include gallery id="gallery1" caption="This is a sample gallery with **Markdown support**." %} -->

{% include gallery id="gallery1" caption="This is a sample gallery with **Markdown support**." %}

{% include gallery id="gallery2" caption="This is a second gallery example with images hosted externally." %}

{% include gallery id="gallery1" layout="half" caption="This is a half gallery layout example." %}

