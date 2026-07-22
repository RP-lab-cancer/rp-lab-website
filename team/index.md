---
title: People
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'research-assistant-professor'" %} 
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %} 
{% include list.html data="members" component="portrait" filter="role == 'phd'" %} 
{% include list.html data="members" component="portrait" filter="role == 'master'" %} 
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html background="images/main/background.jpg" dark=true %}

"You cannot hope to build a better world without improving the individuals. To that end, each of us must work for his own improvement, and at the same time share a general responsibility for all humanity, our particular duty being to aid those to whom we think we can be most useful." 

— _Maria Skłodowska-Curie_

{% include section.html %}

{% capture content %}

{% include figure.html image="images/people/Sectioning.png" %}
{% include figure.html image="images/people/Organoid_NucView.jpg" %}
{% include figure.html image="images/people/ice_bucket.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
