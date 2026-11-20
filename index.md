---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-inner">
    <p class="eyebrow">Coastal engineer · PhD in Physical Oceanography</p>
    <h1>Understanding the coast to design for it.</h1>
    <p class="hero-lead">I combine numerical modelling, satellite remote sensing and observational data to assess coastal risk, for scientific research and for coastal and port engineering projects.</p>
    <div class="btn-row">
      <a class="btn btn-light" href="{{ '/consulting/' | relative_url }}">Consulting services</a>
      <a class="btn btn-outline" href="{{ '/research/' | relative_url }}">Research</a>
    </div>
  </div>
</section>

<section class="band" aria-label="Key figures" style="border-top:0">
  <div class="container figures">
    <div class="figure"><span class="figure-num">19</span><span class="figure-label">Publications in JCR journals</span></div>
    <div class="figure"><span class="figure-num">10+</span><span class="figure-label">Years in coastal and port engineering</span></div>
    <div class="figure"><span class="figure-num">15+</span><span class="figure-label">Consulting projects</span></div>
    <div class="figure"><span class="figure-num small">IMEDEA</span><span class="figure-label">Postdoctoral researcher (UIB-CSIC)</span></div>
  </div>
</section>

<section class="container about">
  <img src="{{ '/assets/img/profile.jpg' | relative_url }}" alt="Portrait of Miguel Agulles" width="300" height="300">
  <div class="about-text">
    <h2 class="section-title">About me</h2>
    <p>I am a civil engineer specialised in coastal engineering, with a PhD in Physical Oceanography from the University of the Balearic Islands. I am currently a postdoctoral researcher at IMEDEA (UIB-CSIC), working on sea-level variability, extreme sea levels, shoreline dynamics and satellite-derived bathymetry.</p>
    <p>In parallel, I carry out applied studies for engineering firms and port authorities: maritime climate, harbour agitation, beach dynamics and operational wave forecasting systems.</p>
  </div>
</section>

<section class="container split">
  <div class="split-card">
    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#1B5E9E" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2 12c2-2 4-2 6 0s4 2 6 0 4-2 6 0"/><path d="M2 17c2-2 4-2 6 0s4 2 6 0 4-2 6 0"/><path d="M2 7c2-2 4-2 6 0s4 2 6 0 4-2 6 0"/></svg>
    <h3>Research</h3>
    <ul>
      <li>Extreme sea levels and mean sea-level rise</li>
      <li>Short- and long-term beach and shoreline dynamics</li>
      <li>Satellite remote sensing: shorelines and bathymetry from Sentinel-2 and Landsat</li>
    </ul>
    <a class="more" href="{{ '/research/' | relative_url }}">Research and publications →</a>
  </div>
  <div class="split-card dark">
    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#9CC4EA" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="5" r="2"/><path d="M12 7v14"/><path d="M5 13H3a9 9 0 0 0 18 0h-2"/><path d="M8 10h8"/></svg>
    <h3>Consulting</h3>
    <ul>
      <li>Maritime climate: extremes and long-term trends</li>
      <li>Harbour agitation, resonance and operability</li>
      <li>Shoreline dynamics and beach nourishment</li>
      <li>Breakwaters, seawalls and nature-based solutions</li>
    </ul>
    <a class="more" href="{{ '/consulting/' | relative_url }}">Services and projects →</a>
  </div>
</section>

<section id="publications" class="band">
  <div class="container pubs">
    <div class="section-head">
      <h2 class="section-title">Recent publications</h2>
      <a href="{{ site.orcid }}">All publications on ORCID →</a>
    </div>
    {%- comment -%} TODO: add journal and DOI to each entry, e.g. "Agulles, M. et al. · Journal name · <a href="https://doi.org/...">doi:...</a>" {%- endcomment -%}
    <article class="pub">
      <span class="pub-year">2026</span>
      <div class="pub-body">
        <h3>A fully coupled 85-year hindcast of waves and storm surges along European coastlines (1940–2024)</h3>
        <p>Agulles, M. et al.</p>
      </div>
    </article>
    <article class="pub">
      <span class="pub-year">2026</span>
      <div class="pub-body">
        <h3>Multi-decadal shoreline variability at a Mediterranean urban beach: disentangling storm impacts and sea-level influence</h3>
        <p>Agulles, M. et al.</p>
      </div>
    </article>
    <article class="pub">
      <span class="pub-year">2024</span>
      <div class="pub-body">
        <h3>Mediterranean seagrasses provide essential coastal protection under climate change</h3>
        <p>Agulles, M. et al.</p>
      </div>
    </article>
  </div>
</section>

<section class="container education">
  <h2 class="section-title">Education</h2>
  <div class="edu-grid">
    <div class="edu-card"><span class="years">2018–2023</span><h3>PhD in Physical Oceanography</h3><span class="inst">University of the Balearic Islands (UIB)</span></div>
    <div class="edu-card"><span class="years">2013–2015</span><h3>MSc in Coastal and Port Engineering</h3><span class="inst">University of Cantabria (UC)</span></div>
    <div class="edu-card"><span class="years">2005–2011</span><h3>Civil Engineering (Public Works)</h3><span class="inst">Polytechnic University of Valencia (UPV)</span></div>
  </div>
</section>
