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
  caption="S9 Wet Science Building"
%}

{% endcapture %}

{% capture col2 %}

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.7978734415537!2d103.78020803488968!3d1.2958822242022032!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da1bc911595d3d%3A0xd684eb7b6242d35c!2sNUS%20S9%20Wet%20Science%20Building!5e0!3m2!1sen!2ssg!4v1760685171475!5m2!1sen!2ssg" width="480" height="270" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
We are part of the 
[Department of Biochemistry](https://medicine.nus.edu.sg/bch/faculty/li-ronghui/), 
Yong Loo Lin School of Medicine, 
National University of Singapore.
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
