---
layout: archive
permalink: /
title: ""
---

I am a Ph.D. Candidate in Government at Harvard University and a *James M. and Cathleen D. Stone Ph.D. Scholar in Inequality and Wealth Concentration* at the Harvard Kennedy School. My core research agenda highlights the central role of violence and coercion--both directly and indirectly--in shaping the politics of race, class, and gender. What role, if any, does mass warfare have in catalyzing social change? Why do groups engage in violence against each other? How do violent and coercive institutions rise and decline in democracies? I use a combination of historical, administrative data and quasi-experimental techniques to help answer questions like these primarily within the context of the United States. By putting American politics in historical perspective, I seek to understand how the American experience may not be so different from that of other nations.

My work is published or forthcoming in the *American Journal of Political Science*, the *Journal of Peace Research*, and the *Review of International Organizations*. You can find my [C.V. here.]({{site.url}}/files/Mazumder_Academic_CV.pdf)

My research benefits from generous support from the following organizations:

* [Harvard Kennedy School Malcolm Weiner Center for Social Policy](https://inequality.hks.harvard.edu/)
* [The Russell Sage Foundation](https://www.russellsage.org/)

See below for a list of projects that I am currently working on.

<div class="tiles">
{% for post in site.posts %}
	{% if post.category == 'research'%}
	{% include post-grid.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->


