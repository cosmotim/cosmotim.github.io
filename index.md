---
title: Thermal transport & lattice dynamics
home: true
---
<section class="hero">
  <div>
    <p class="eyebrow">Postdoctoral Fellow · UT Austin</p>
    <h1>Understanding heat.<br><span>Advancing energy materials.</span></h1>
    <p class="lede">I’m Yitian Wang. I study thermal transport and lattice dynamics in functional oxides and solid-state ionic conductors, connecting crystal growth, neutron scattering, and modeling.</p>
    <div class="button-row"><a class="button button-primary" href="{{ '/research/' | relative_url }}">Explore my research <span aria-hidden="true">→</span></a><a class="text-link" href="{{ '/contact/' | relative_url }}">Get in touch <span aria-hidden="true">↗</span></a></div>
  </div>
  <aside class="impact" aria-label="Research at a glance">
    <div><strong class="metric">6</strong><span>First-author journal papers</span></div>
    <div><strong>Neutron-scattering leadership</strong><span>Two successful beam time proposals; experiments at ORNL’s HFIR and SNS.</span></div>
    <div><strong>~7 research groups</strong><span>Collaboration across universities and national laboratories.</span></div>
  </aside>
</section>
<section class="home-section" aria-labelledby="research-heading">
  <div class="section-heading"><div><p class="eyebrow">Research highlights</p><h2 id="research-heading">From atomic motion to heat flow</h2></div><a class="text-link" href="{{ '/research/' | relative_url }}">Research details →</a></div>
  <div class="research-grid">
    <article class="research-card"><span class="card-number">01 / Transport</span><h3>Heat in solid electrolytes</h3><p>Investigating how phonons and diffusons carry heat in lithium- and sodium-ion conductors.</p></article>
    <article class="research-card"><span class="card-number">02 / Crystal growth</span><h3>Crystals that enable discovery</h3><p>Built a floating-zone growth workflow for centimeter-scale LLZTO single crystals.</p></article>
    <article class="research-card"><span class="card-number">03 / Neutron scattering</span><h3>Resolving lattice dynamics</h3><p>Led experiments at Oak Ridge to map phonon dispersion in a garnet solid electrolyte.</p></article>
    <article class="research-card"><span class="card-number">04 / Modeling</span><h3>Explaining unusual heat flow</h3><p>Developed a phonon–diffuson model to explain thermal conductivity beyond the traditional Debye model.</p></article>
  </div>
</section>
<section class="home-section" aria-labelledby="publications-heading">
  <div class="section-heading"><div><p class="eyebrow">Selected publications</p><h2 id="publications-heading">Recent work & key findings</h2></div><a class="text-link" href="{{ '/publications/' | relative_url }}">All publications →</a></div>
  {% for paper in site.data.publications %}{% if paper.selected %}{% include publication.html paper=paper %}{% endif %}{% endfor %}
</section>
<section class="home-section" aria-labelledby="media-heading">
  <div class="section-heading"><div><p class="eyebrow">Media & recognition</p><h2 id="media-heading">Research in the news</h2></div></div>
  {% include media.html %}
</section>
<section class="home-section documents-strip" aria-labelledby="documents-heading"><p class="eyebrow">Documents</p><h2 id="documents-heading">Background, in brief or in full</h2>{% include documents.html %}</section>
<section class="contact-panel" aria-labelledby="contact-heading"><div><p class="eyebrow">Contact</p><h2 id="contact-heading">Let’s connect.</h2><p>Interested in thermal transport, solid electrolytes, or a research collaboration?</p></div><a class="button button-primary" href="mailto:ywang00149@gmail.com">Email Yitian <span aria-hidden="true">↗</span></a></section>
