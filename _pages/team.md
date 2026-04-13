---
title: "Team - QSMol"
layout: gridlay
excerpt: "Team - QSMol"
sitemap: false
permalink: /team
---

# Group Members

Jump to [Investigators](#investigators), [Advisory Board](#advisory-board), [Project Partners](#project-partners), [Project Officer](#project-officer), [PDRAs](#pdras), [PhD students](#phd-students).

## Investigators
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% if member.role == "investigator" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  {% if member.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  <h4>{{ member.name }}</h4>
  {% if member.title %}
  <p><strong>{{ member.title | capitalize }}</strong></p>
  {% endif %}
  <p>
    <i>{{ member.institution }}</i>
  </p>
  <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
  <p>{{ member.links }}</p>
  {% if member.notes %}
  <p>{{ member.notes }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Advisory Board
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% if member.role == "advisor" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  {% if member.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  <h4>{{ member.name }}</h4>
  {% if member.title %}
  <p><strong>{{ member.title | capitalize }}</strong></p>
  {% endif %}
  <p>
    <i>{{ member.institution }}</i>
  </p>
  <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
  <p>{{ member.links }}</p>
  {% if member.notes %}
  <p>{{ member.notes }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Project Partners
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% if member.role == "partner" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  {% if member.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  <h4>{{ member.name }}</h4>
  {% if member.title %}
  <p><strong>{{ member.title | capitalize }}</strong></p>
  {% endif %}
  <p>
    <i>{{ member.institution }}</i>
  </p>
  <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
  <p>{{ member.links }}</p>
  {% if member.notes %}
  <p>{{ member.notes }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Project Officer
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% if member.role == "officer" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  {% if member.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% else %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/placeholder.jpg" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  <h4>{{ member.name }}</h4>
  {% if member.title %}
  <p><strong>{{ member.title | capitalize }}</strong></p>
  {% endif %}
  <p>
    <i>{{ member.institution }}</i>
  </p>
  <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
  <p>{{ member.links }}</p>
  {% if member.notes %}
  <p>{{ member.notes }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## PDRAs
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% if member.role == "pdra" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  {% if member.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% else %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/placeholder.jpg" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  <h4>{{ member.name }}</h4>
  {% if member.title %}
  <p><strong>{{ member.title | capitalize }}</strong></p>
  {% endif %}
  <p>
    <i>{{ member.institution }}</i>
  </p>
  <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
  <p>{{ member.links }}</p>
  {% if member.notes %}
  <p>{{ member.notes }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## PhD students
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% if member.role == "phd" %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  {% if member.photo %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  {% else %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/placeholder.jpg" class="img-responsive" width="25%" style="float: left" />
  {% endif %}
  <h4>{{ member.name }}</h4>
  {% if member.title %}
  <p><strong>{{ member.title | capitalize }}</strong></p>
  {% endif %}
  <p>
    <i>{{ member.institution }}</i>
  </p>
  <p><a href="mailto:{{ member.email }}">{{ member.email }}</a></p>
  <p>{{ member.links }}</p>
  {% if member.notes %}
  <p>{{ member.notes }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<!-- 
## Alumni


<div class="row">
<div class="col-sm-6 clearfix">
<h4>PDRAs</h4>
{% assign pdras = site.data.alumni | where:"role", "Postdoctoral research associate" %}
{% for member in pdras %}
<p>{{ member.name }},
{% if member.lab == "rbcs"%}
[RbCs lab]({{ site.url }}{{ site.baseurl }}/rbcs),
{% elsif member.lab == "csyb"%}
[CsYb lab]({{ site.url }}{{ site.baseurl }}/csyb),
{% elsif member.lab == "tweezers"%}
[Tweezers lab]({{ site.url }}{{ site.baseurl }}/tweezers),
{% elsif member.lab == "microscope"%}
[Microscope lab]({{ site.url }}{{ site.baseurl }}/microscope),
{% endif %}
{% if member.years %}{{ member.years }}{% endif %}
{% if member.thesis_link %}
([PhD thesis]({{member.thesis_link}}))
{% endif %}
{{ member.info }}
</p>
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>PhD students</h4>
{% assign phds = site.data.alumni | where:"role", "PhD student" %}
{% for member in phds %}
<p>{{ member.name }},
{% if member.lab == "rbcs"%}
[RbCs lab]({{ site.url }}{{ site.baseurl }}/rbcs),
{% elsif member.lab == "csyb"%}
[CsYb lab]({{ site.url }}{{ site.baseurl }}/csyb),
{% elsif member.lab == "tweezers"%}
[Tweezers lab]({{ site.url }}{{ site.baseurl }}/tweezers),
{% elsif member.lab == "microscope"%}
[Microscope lab]({{ site.url }}{{ site.baseurl }}/microscope),
{% endif %}
{% if member.years %}{{ member.years }}{% endif %}
{% if member.thesis_link %}
([PhD thesis]({{member.thesis_link}}))
{% endif %}
{{ member.info }}
</p>
{% endfor %}
</div>

</div>

<div class="row">
<div class="col-sm-6 clearfix">
<h4>Masters students</h4>
{% for member in site.data.alumni_masters %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>Summer students</h4>
{% for member in site.data.alumni_summer %}
{{ member.name }}
{% endfor %}
</div>

</div> -->
