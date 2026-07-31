---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

These are the members of the lab.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'technician'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'technician'" %}

{% include section.html dark=true %}

Come join our lab! We are always looking for motivated students for both undergraduate and graduate positions. 

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="contact"
  style="button"
%}

{% include section.html %}

## Lab Alumni

Haley Turcotte

Nilofar Pattang

Alice Van Wyk

Michelle Deng

Allie Melin

