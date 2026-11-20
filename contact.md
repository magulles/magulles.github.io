---
layout: default
title: Contact
permalink: /contact/
---

<section class="container page-intro">
  <p class="eyebrow">Contact</p>
  <h1>Get in touch.</h1>
  <p class="lead">For research collaborations, technical studies or operational forecasting systems, email is the best way to reach me.</p>
</section>

<section class="container contact-grid">
  <div class="contact-item"><span class="label">Email</span><a href="mailto:{{ site.email }}">{{ site.email }}</a></div>
  <div class="contact-item"><span class="label">Location</span><span class="value">Dénia, Spain</span></div>
  <div class="contact-item"><span class="label">LinkedIn</span><a href="{{ site.linkedin }}">Miguel Agulles Gámez</a></div>
  <div class="contact-item"><span class="label">Publications</span><a href="{{ site.orcid }}">ORCID 0000-0003-3501-2899</a></div>
  {%- if site.google_scholar != "" %}
  <div class="contact-item"><span class="label">Citations</span><a href="{{ site.google_scholar }}">Google Scholar</a></div>
  {%- endif %}
</section>
