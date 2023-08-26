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

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.month }} {{ publi.year }},  {{ publi.journal }}, {{ publi.volume }}, {{ publi.pages }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.url }}"> DOI: {{ publi.doi }}</a>
 
{% endfor %}

