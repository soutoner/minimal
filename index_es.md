---
layout: default
lang: es
permalink: es
---

{% capture about_me %}{% include about_me.md %}{% endcapture %}
{% capture experience %}{% include experience.md %}{% endcapture %}
{% capture education %}{% include education.md %}{% endcapture %}
{% capture projects %}{% include projects.md %}{% endcapture %}
{% capture languages %}{% include languages.md %}{% endcapture %}
{% capture additional_references %}{% include additional_references.md %}{% endcapture %}

{{ about_me | markdownify }}
{{ experience | markdownify }}
{{ projects | markdownify }}
{{ education | markdownify }}
{{ languages | markdownify }}
{{ additional_references | markdownify }}