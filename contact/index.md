---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The von Mentzer-Group is based in the Department of Microbiology and immunology at Sahlgrenska Academy, Institute of Biomedicine, University of Gothenburg. We are located on the 5th floor.

{%
  include button.html
  type="email"
  text="astrid.von.mentzer@gu.se"
  link="astrid.von.mentzer@gu.se"
%}
{%
  include button.html
  type="phone"
  text="+46 (0)769-410890"
  link="+46 (0)769-410890"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/FP46gpt98ZtfuYxN9"
%}

Mailing adress
Astrid von Mentzer
Department of Microbiology and Immunology
Institute of Biomedicine
Medicinaregatan 1G
413 90 Gothenburg

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/1200px-Sahlgrenska_Academy.jpeg"
  caption="Sahlgrenska Academy"
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
