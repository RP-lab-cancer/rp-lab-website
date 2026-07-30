---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# Contact

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
  link="+1-464-220-9453"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  text="Address: Bldg 112, Rm 303"
  link="https://www.google.com/maps/place/2160+S+1st+Ave,+Maywood,+IL+60153/data=!4m2!3m1!1s0x880e35788abe158b:0x692f31330a04c8b2?sa=X&ved=1t:242&ictx=111"
%}

{% include section.html %}
<div style="text-align: center;">
For more information about our research, data resources, or potential collaborations, please feel free to reach out by email.
<br><br>
Prospective <strong>students</strong> and <strong>postdoctoral fellows</strong> should send their CV and a summary of research interests.
  <br><br>
<strong>Collaborators</strong> should include relevant background or project ideas. We are interested in collaborations related to:<br></div>

{% capture col1 %}
Breast cancer
  - patient-centered research
  - susceptibility
  - initiation
  - progression
  - therapy resistance
{% endcapture %}

{% capture col2 %}
RNA biology
  - long non-coding RNAs
  - microRNAs
  - structure-function studies
  - tissue-specificity
  - role in normal development and in cancer
{% endcapture %}

{% capture col3 %}
And more:
- patient-derived organoids
- translational research
- computational approaches
- genetic perturbations

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html dark=true %}

{% capture col1 %}
<div style="text-align: left;">
<strong>Scientific inquiries:</strong><br>
rprzanowska@luc.edu<br><br>

<strong>Breast Cancer Initiation:</strong><br>
pprzanowski@luc.edu<br>
</div>
{% endcapture %}

{% capture col2 %}
**[Department of Cancer Biology](https://www.luc.edu/stritch/cancerbiology/)**  
Loyola University Chicago  
Stritch School of Medicine  
Cardinal Bernardin Cancer Center  
2160 S. First Ave., Bldg 112, Rm 303  
Maywood, IL 60153  
{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/stritch-exterior.jpg"
  caption="Stritch School of Medicine"
  link="https://www.luc.edu/stritch/"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/cardinal-bernardin-cancer-center.jpg"
  caption="Cardinal Bernardin Cancer Center"
  link="https://www.loyolamedicine.org/location/cardinal-bernardin-cancer-center"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html background="images/main/background.jpg" dark=true %}
<div style="text-align: center;">
"The map is not the territory, the word is not the thing it describes."
<br><br>
— <em>Alfred Korzybski</em>
</div>
