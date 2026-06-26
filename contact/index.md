---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located in the Cardinal Bernardin Cancer Center at Loyola University Chicago.


{%
  include button.html
  type="email"
  text="rprzanowska at luc dot edu"
  link="rprzanowska@luc.edu"
%}
{%
  include button.html
  type="phone"
  text="RP lab phone"
  link="+1-434-260-1835"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/2160+S+1st+Ave,+Maywood,+IL+60153/data=!4m2!3m1!1s0x880e35788abe158b:0x692f31330a04c8b2?sa=X&ved=1t:242&ictx=111"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/stritch-exterior.jpg"
  caption="Stritch School of Medicine"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/cardinal-bernardin-cancer-center.jpg"
  caption="Cardinal Bernardin Cancer Center"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Department of Cancer Biology
Loyola University Chicago
Stritch School of Medicine Health Sciences Division
Cardinal Bernardin Cancer Center
2160 S. First Ave., Bldg 112, Rm 303
Maywood, IL 60153
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
