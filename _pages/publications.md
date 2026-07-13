---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The full list my publications is available [here](){:target="_blank"}.

## Selected Publications
---

{% for publi in site.data.publications %}

# Peer-reviewed
Behera, S.S.<sup>&midast;</sup>, Tiwari, S.<sup>&midast;</sup>, Pandey, A.<sup>&midast;</sup>, <b>Agarwal A.</b>, Ojha, A.K. (2024). <i>The probable direction of impact at Dhala impact structure, India deciphered from microfracture intensity and X-ray diffractometry: a new potential impact direction indicator.</i> <b>Earth, Planets and Space.</b> 76. Doi: <a href="https://doi.org/10.1186/s40623-024-02028-1" target="_blank" style="color:#00876c">10.1186/s40623-024-02028-1.</a>

<span style="color:grey"> <em>{{2024}},  {{Earth, Planets and Space.}}, {{ publi.volume }}, {{ publi.pages }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.url }}"> DOI: {{ publi.doi }}</a>

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.month }} {{ publi.year }},  {{ publi.journal }}, {{ publi.volume }}, {{ publi.pages }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.url }}"> DOI: {{ publi.doi }}</a>
 
{% endfor %}

