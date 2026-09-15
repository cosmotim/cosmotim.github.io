---
title: Publications
permalink: /publications/
intro: Six first-author and three co-authored journal articles, plus my doctoral dissertation.
---
<h2>Journal articles</h2>
<div class="publication-list">
{% for paper in site.data.publications %}{% if paper.doi %}{% include publication.html paper=paper full=true %}{% endif %}{% endfor %}
</div>
<h2>Doctoral dissertation</h2>
{% for paper in site.data.publications %}{% unless paper.doi %}{% include publication.html paper=paper full=true %}{% endunless %}{% endfor %}
