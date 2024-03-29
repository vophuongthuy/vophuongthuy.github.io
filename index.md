---
layout: base
css:
  - "/css/reading.css"
  - "/css/activity.css"
  - "/css/post-list.css"
---

{% include header.html type="page" %}

<!-- intro -->
<section class="alt-color">
  {% include sections/sec-front-md.html %}
  <p class="text-justify" style="margin: 0;" markdown="1">
  I am **Thuy**, a Mathematician and a Math teacher. My research focuses on the field of random graphs, in particular, random networks with applications in Statistics. I am also interested in the probabilistic models, deep learning networks for the study of Epidemic and Biology.
  </p>
  {% include sections/sec-back.html %}
</section>

<!-- research -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Research Experiences"
    source=site.data.research
    ref="research"
  %}
  {% include sections/sec-back.html %}
</section>

<!-- publications -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-publications.html
    heading="Publications"
    source=site.data.publications
    ref="publications"
  %}
  {% include sections/sec-back.html %}
</section>

<!-- teaching -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-teaching.html
    heading="Teaching"
    source=site.data.teaching
    ref="teaching" %}
  {% include sections/sec-back.html %}
</section>

<!-- education -->
<section class="alt-color">
  {% include sections/sec-front-lg.html %}
  {% include sections/sec-timeline.html
    heading="Education"
    source=site.data.education
  %}
  {% include sections/sec-back.html %}
</section>

<!-- contact -->
<section class="alt-color">
  {% include sections/sec-front-md.html %}
  {% include sections/sec-contact.html %}
  {% include sections/sec-back.html %}
</section>
