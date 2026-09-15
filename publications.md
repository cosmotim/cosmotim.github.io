---
title: Publications
permalink: /publications/
intro: Six first-author and three co-authored journal articles, plus my doctoral dissertation.
---
<p>My research explores how atomic motion and material structure govern heat transport in solid electrolytes. The studies below connect crystal growth, thermal measurements, neutron scattering, and modeling to questions in battery thermal management.</p>
<h2>Selected work</h2>
{% for paper in site.data.publications %}{% if paper.selected %}{% include publication-feature.html paper=paper %}{% endif %}{% endfor %}
<h2>Other journal articles</h2>
<div class="publication-list">
{% for paper in site.data.publications %}{% if paper.doi %}{% unless paper.selected %}{% include publication.html paper=paper full=true %}{% endunless %}{% endif %}{% endfor %}
</div>
<h2>Doctoral dissertation</h2>
{% for paper in site.data.publications %}{% unless paper.doi %}{% include publication.html paper=paper full=true %}{% endunless %}{% endfor %}
