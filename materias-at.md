---
layout: article
permalink: /materias-at/
title: "Materias de Cs. de la Atmósfera"
---

### Materias Iniciales
<div class="tiles">
{% for item in site.materias-at %}
    {% if item.tipo == "Inicial" %}
    <li><a href="{{ site.url }}{{ item.url }}">{{ item.title }}</a></li>
    {% endif %}
{% endfor %}
</div><!-- /.tiles -->

### Materias Intermedias
<div class="tiles">
{% for item in site.materias-at %}
    {% if item.tipo == "Intermedia" %}
    <li><a href="{{ site.url }}{{ item.url }}">{{ item.title }}</a></li>
    {% endif %}
{% endfor %}
</div><!-- /.tiles -->


### Materias Electivas

<div class="tiles">
{% for item in site.materias-at %}
    {% if item.tipo == "Electiva" %}
    <li><a href="{{ site.url }}{{ item.url }}">{{ item.title }}</a></li>
    {% endif %}
{% endfor %}
</div><!-- /.tiles -->