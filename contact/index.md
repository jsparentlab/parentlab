---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located at the Central Experimental Farm in Ottawa, part of Agriculture and Agri-Food Canada's [Ottawa Research and Development Centre](https://agriculture.canada.ca/en/science/agriculture-and-agri-food-research-centres/ottawa-research-and-development-centre). 
Jean-Sébastien is also affiliated with Carleton University's [Department of Biology](https://carleton.ca/biology/people/jean-sebastien-parent/).

{%
  include button.html
  type="email"
  text="jean-sebastien.parent@agr.gc.ca"
  link="jean-sebastien.parent@agr.gc.ca"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/G8D3mkkHnywzvCA67"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/kwneatby.png"
  caption="The KW Neatby building at the Central Experimental Farm"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
