---
title: People
permalink: /people/
---

{% assign people_sorted = site.people | sort: 'joined' %}
{% assign role_array = "faculty|postdoc|phdstudent|visiting|others|alumni" | split: "|" %}

{% for role in role_array %}

{% assign people_in_role = people_sorted | where: 'position', role %}

<!-- Skip section if there's nobody -->
{% if people_in_role.size == 0 %}
  {% continue %}
{% endif %}

<div class="pos_header">
{% if role == 'postdoc' %}
<h3>Postdoctoral Fellows</h3>
 {% elsif role == 'faculty' %}
<h3>Permanent staff</h3>
 {% elsif role == 'phdstudent' %}
<h3>PhD Students</h3>
 {% elsif role == 'visiting' %}
<h3>Visiting Scholars</h3>
 {% elsif role == 'alumni' %} 
<h3>Alumni</h3>
{% endif %}
</div>

{% if role != 'alumni' %}
<div class="content list people">
  {% for profile in people_sorted %}
    {% if profile.position contains role %}
      <div class="list-item-people">
        <p class="list-post-title">
          {% if profile.avatar %}
            <a href="{{ site.baseurl }}{{ profile.url }}"><img class="profile-thumbnail" src="{{site.baseurl}}/images/people/{{profile.avatar}}"></a>
          {% else %}
            <a href="{{ site.baseurl }}{{ profile.url }}"><img class="profile-thumbnail" src="http://evansheline.com/wp-content/uploads/2011/02/facebook-Storm-Trooper.jpg"></a>
          {% endif %}
          <a class="name" href="{{ site.baseurl }}{{ profile.url }}">{{ profile.name }}</a>
        </p>
      </div>    
    {% endif %}
  {% endfor %}
</div>
<hr>

{% else %}

<br>

| Who are they | When were they here | Where they went |
| :------------- |:-------------| :-----------|
| [Quentin Decultot](https://www.linkedin.com/in/quentin-décultot-b41b62202) | NEURO team: Master Student (2021) | Continuing studies at ENSMM, Besançon, FR |
| [Pablo Arias](https://www.ircam.fr/person/pablo-arias-sarah/) | CREAM team: PhD Student (2014 - 2018) | Postdoc (2019 - 2021) in Petter Johansson's lab @ Lund University, SE |
| [Laura Rachman](https://www.rug.nl/staff/l.rachman/?lang=en) | CREAM team: PhD Student (2014 - 2018) | Postdoc (2019 - 2021) in Deniz Başkent's lab @ University of Groningen, NL |
| [Louise Goupil](https://www.louisegoupil.co.uk/) | CREAM team: Postdoc (2016 - 2020) | CNRS Researcher (chargé de recherche, 2022~) in LPNC (Université Grenoble Alpes/Université Savoie Mont-Blanc), Grenoble, FR |
| [Emmanuel Ponsot](https://scholar.google.fr/citations?user=oCd7k9IAAAAJ&hl=fr) | CREAM team: Postdoc (2016 - 2018) | CNRS Researcher (chargé de recherche, 2022~) in STMS Lab (IRCAM/CNRS/Sorbonne Université), Paris, FR
{% endif %}
{% endfor %}
