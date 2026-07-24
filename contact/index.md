---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="bhjeon@hanyang.ac.kr"
  link="bhjeon@hanyang.ac.kr"
%}
{%
  include button.html
  type="phone"
  text="02-2220-4642"
  link="02-2220-4642"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="[https://www.google.com/maps](https://maps.app.goo.gl/znVJbAncqPXggYB48)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/BHJ.jpg"
  caption="Byong-Hun Jeon"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lab manager  
contact: ossgpfla@hanyang.ac.kr, 010-3750-5039
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
