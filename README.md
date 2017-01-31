# prova-fusion
Prova fusion to merge Jekyll

{{site.posts|inspect}}

{% for p in site.posts %}

{{ p.title }} {% endfor %}
