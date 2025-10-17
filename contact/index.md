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
  text="email"
  link="ronghui.li@nus.edu.sg"
%}
{%
  include button.html
  type="phone"
  text="phone"
  link="+65 6516 2846"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/QnYWaUy9QdrF8Ubv6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/1920_wsb1-1267351765.jpg"
  caption="We are part of the Department of Biochemistry and Synthetic Biology for Clinical and Technological Innovation at National University of Singapore. The lab is located on the Kent Ridge campus on the 10th floor of the S9 Wet Science building. 

Address: 4 Science Drive 2, S(117544) [map](https://maps.app.goo.gl/QnYWaUy9QdrF8Ubv6)"
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
