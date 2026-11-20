---
layout: default
title: Meteoport
permalink: /meteoport-project/
description: >-
  Meteoport: high-resolution wave forecasts and maritime climate information
  for ports and marinas. Currently in development.
---

<section class="container page-intro">
  <img class="brand-logo" src="{{ '/assets/img/logo-meteoport.png' | relative_url }}" alt="Meteoport" width="360" height="36">
  <p class="eyebrow">Work in progress</p>
  <h1>Wave forecasts for ports and marinas.</h1>
  <p class="lead">Meteoport is a platform that brings high-resolution wave forecasts and maritime climate information to the scale where port operations happen: the harbour entrance, the basins and the berths.</p>
  <p class="status-pill"><span class="status-dot" aria-hidden="true"></span>Currently in development</p>
</section>

<section class="container services" aria-label="What Meteoport offers">
  <div class="service-grid">
    <div class="service">
      <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#1B5E9E" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2 12c2-2 4-2 6 0s4 2 6 0 4-2 6 0"/><path d="M2 17c2-2 4-2 6 0s4 2 6 0 4-2 6 0"/><path d="M2 7c2-2 4-2 6 0s4 2 6 0 4-2 6 0"/></svg>
      <h3>Wave forecasts inside the port</h3>
      <p>Offshore forecasts are propagated with high-resolution local models to the harbour entrance and inside the basins.</p>
    </div>
    <div class="service">
      <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#1B5E9E" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="12" width="5" height="8" rx="1"/><rect x="9.5" y="9" width="5" height="11" rx="1"/><rect x="16" y="6" width="5" height="14" rx="1"/></svg>
      <h3>Maritime climate</h3>
      <p>Historical wave, wind and sea-level statistics for each port, to put every forecast in context.</p>
    </div>
    <div class="service">
      <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#1B5E9E" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="5" r="2"/><path d="M12 7v14"/><path d="M5 13H3a9 9 0 0 0 18 0h-2"/><path d="M8 10h8"/></svg>
      <h3>Operability</h3>
      <p>Clear information for harbour masters, marinas and users to plan manoeuvres and operations.</p>
    </div>
    <div class="service">
      <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#1B5E9E" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M13 2L4 14h7l-1 8 9-12h-7z"/></svg>
      <h3>Energy analytics</h3>
      <p>Wave and wind resource indicators derived from the same forecasting chain.</p>
    </div>
  </div>
</section>

<section class="band">
  <div class="container studies">
    <div class="study">
      <div>
        <h2 class="section-title" style="margin-bottom:16px">Background</h2>
        <p>Meteoport combines several wave and wind forecast sources and refines them with a high-frequency tide gauge installed in the port, which measures sea level and agitation in real time. By comparing observations and model results continuously, the system corrects its forecasts and keeps improving them over time.</p>
        <p style="margin-top:16px">This makes it possible to issue early warnings up to 72 hours ahead, with thresholds adapted to each area and use of the port, and to build the port’s own long-term record of sea level and storm events: the basis for planning its adaptation to sea-level rise.</p>
        <p style="margin-top:16px">The approach builds on the operational wave forecasting systems I have implemented in harbours in the Balearic Islands, such as Port d’Andratx (Mallorca). Updates will be published here as the project progresses. If you manage a port or marina and are interested in a pilot, <a href="mailto:{{ site.email }}?subject=Meteoport">get in touch</a>.</p>
      </div>
      <figure>
        <img src="{{ '/assets/img/meteoport-tide-gauge.jpg' | relative_url }}" alt="High-frequency tide gauge mounted on a quay" loading="lazy">
        <figcaption>Example of a high-frequency tide gauge installation for real-time measurement of sea level and agitation.</figcaption>
      </figure>
    </div>
    <figure class="wide-figure">
      <img src="{{ '/assets/img/meteoport-forecast.jpg' | relative_url }}" alt="Observed and forecast significant wave height and sea level inside a port, with warning thresholds" loading="lazy">
      <figcaption>Example of the forecasting tool: observed significant wave height and sea level up to the present, and numerical forecast for the next 72 hours with warning thresholds. Illustrative values.</figcaption>
    </figure>
  </div>
</section>
