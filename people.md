---
title: People
permalink: /people/
---

Our group is co-located on two sites, in the FEMTO-ST Institute in Besançon and in Paris, in collaboration with GHU/Hopital Sainte-Anne and ICM/Institut du Cerveau. 


<img src="{{site.baseurl}}/images/people/group_2.jpg">
<div class="list-detail" style="text-align: center;" >The Besançon team in May 2023. From left to right: Paul Maublanc, Camille Des Lauriers, Paige Tuttösi, Rudradeep Guha, Coralie Joucla, Jean-Julien Aucouturier, Patrick Nectoux, Aynaz Adl Zarrabi.</div> <br>

{% assign people_sorted = site.people | sort: 'joined' %}
{% assign role_array = "faculty|postdoc|phdstudent|visiting|engineer|masterstudent" | split: "|" %}

{% for role in role_array %}

{% assign people_in_role = people_sorted | where: 'position', role %}

<!-- Skip section if there's nobody -->
{% if people_in_role.size == 0 %}
  {% continue %}
{% endif %}

<div class="pos_header">
 {% if role == 'faculty' %}
<h3>Permanent staff</h3>
{% elsif role == 'postdoc' %}
<h3>Postdoctoral Fellows</h3>
 {% elsif role == 'phdstudent' %}
<h3>PhD Students</h3>
 {% elsif role == 'visiting' %}
<h3>Visiting PhD Students & Scholars</h3>
 {% elsif role == 'engineer' %}
<h3>Developers/Engineers</h3>
 {% elsif role == 'masterstudent' %}
<h3>Master Students</h3>
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
          <a class="name" href="{{ site.baseurl }}{{ profile.url }}"> {{ profile.name }} </a>

          {% capture bool %}{% if profile.location == "paris" %}Yes{% else %}No{% endif %}{% endcapture%}
          {% if profile.location %}
            {% if bool == "Yes" %}
              <div class="list-detail" style="text-align: center;" >Paris team</div>
            {% else %}
              <div class="list-detail" style="text-align: center;">Besançon team</div>
            {% endif %}
          {% endif %}
        </p>
      </div>    
    {% endif %}
  {% endfor %}
</div>
<hr>


{% endif %}
{% endfor %}


<div class="pos_header">
<h3>Alumni</h3>
</div>

<br>

| Who are they | When were they here | Where they went |
| :------------- |:-------------| :-----------|
| Fouad Baamal | Master student (2025) | Continuing M2 studies in SUPMICROTECH, Besançon, FR |
| [Manaoj Aravind](/people/manaoj_aravind/index.html) | Postdoc (2024-2025) | on the job market |
| Maia Lehec | Bachelor student (2025) | Continuing studies in Université de Strasbourg, FR |
| [Aynaz Adl Zarrabi](/people/aynaz_adlzarrabi/index.html) | PhD Student (2022-2025) | on the job market |
| [Anais Llorens](/people/anais_llorens/index.html) | Postdoc (2022-2025) | Researcher, Bioserenity, Paris/Nancy, FR |
| [Paige Tuttosi](/people/paige_tuttosi/index.html) | PhD Student (2022-2025) | Researcher, Enchanted Tools, Paris, FR |
| [Marie Villain](/people/marie_villain/index.html) | Postdoc (2022-2024) | Assistant Professor, Sorbonne Université, Paris, FR | 
| [Sarah Benghanem](/people/sarah_benghanem/index.html) | PhD student (2021-2024) | Postdoc, University of Geneva, CH |
| Juan Diego Díaz | Master student (2024) | Continuing M2 studies in Sorbonne Université, FR | 
| Umut Kurnaz | Master student (2024) | Continuing M2 studies in Université Paris-Saclay, FR |
| [Nadia Guerouaou](/people/nadia_guerouaou/index.html) | PhD student (2020-2024) | Contract lecturer, ESSEC Paris, FR  | 
| [Estelle Pruvost-Robieux](/people/estelle_pruvost/index.html) | PhD student (2020-2024) | Assistant Professor (MCU-PH), Université Paris Cité FR | 
| Saib Hamouza | Master student (2023) | Continuing studies at Supmicrotech ENSMM, Besançon FR |
| [Paul Maublanc](/people/paul_maublanc/index.html) | Research engineer (2022-2023) | PhD student with Boris Kleber, Aarhus University, DK  |
| [Coralie Joucla](/people/coralie_joucla/index.html) | Postdoc, project ANR SEPIA (2022-2023) | Clinical project manager, SOPHYSA, Besançon, FR |
| [Alexander Gontran-Massey](https://www.linkedin.com/in/alexander-gontran-massey/) | Master Student (2022) | Continuing studies at ISIFC, Besançon, FR | 
| [Céline Vanney](https://www.linkedin.com/in/celine-vanney) | Master Student (2022) | Continuing studies at ISIFC, Besançon, FR |
| [Quentin Decultot](https://www.linkedin.com/in/quentin-décultot-b41b62202) | Master Student (2021) | Web developper, SOLUTEC, Lyon, FR |
| [Guillaume Denis](https://www.linkedin.com/in/gudenis/) | Senior web developper, project ERC ACTIVATE (2021) | Freelance Web Application Developer, Marseille, FR |


Alumni members of the CREAM team (2014-2020), and where they went next, can be found on the [CREAM]({{site.baseurl}}/cream) history page .  
