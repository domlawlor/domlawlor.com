---
title:
layout: default
permalink: /
published: true
---


<div class="ProjectContainer">

	<div class="gallery">


  {% for project in site.projects %}

  {% if project.redirect %}
  <div class="projectTile">
          <a href="{{ project.redirect }}" target="_blank">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% else %}

  <div class="projectTile">
          <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% endif %}

  {% endfor %}

	</div>

</div>

---

## Released Titles

List of the games I've been part of the development team:    Call of Duty: Vanguard | Call of Duty: Modern Warfare 2 | Tennis World Tour 2 | AO Tennis 2 | Cricket 19 | Big Bash Boom

![COD:MW2](/assets/images/cv/mw2.jpg)
![COD:Vanguard](/assets/images/cv/vanguard.jpg)
![TennisWorldTour2](/assets/images/cv/twt2.jpg)
![AO2Tennis](/assets/images/cv/ao2.jpg)
![Cricket19](/assets/images/cv/c19.jpg)
![BigBashBoom](/assets/images/cv/bigbashboom.jpg)