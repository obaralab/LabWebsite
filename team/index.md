---
title: Team
nav:	
  order: 4
  tooltip: About our team
---


{% include section.html %}
# {% include icon.html icon="fa-solid fa-users" %} <u>Team</u>
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}



{% include section.html %}
# {% include icon.html icon="fa-solid fa-paw" %}<u>Support Staff</u>



{% capture content %}

{%
  include card.html
  image="images/Reggie.png"
  link="members/will-kasberg"
  title="Reggie"
  style="big"
  tags="Doggos"
%}


{%
  include card.html
  image="images/millie.jpg"
  link="members/safal-shrestha"
  title="Millie"
  tooltip="Emotional Support Animal for Safal"
  style="big"
  tags="Doggos"
%}



{% endcapture %}

 

{%
  include grid.html
  content=content
  style="regular"
%}

{% include section.html %}
# <u>Lab Pictures</u>

{% capture content %}

{%
  include figure.html
  image="images/LAB/trio.png"
  caption="Lab dinner and beach"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/LAB/lab-6.jpg"
  caption="Pictures on our lab freezer"
  link="team"
  width="100%"
%}


{%
  include figure.html
  image="images/LAB/emma-dad.jpg"
  caption="Quality time with Dr. Farley and her dad"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/LAB/centrifuge.jpg"
  caption="Spin the bottle!"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/LAB/taylor.jpg"
  caption="Showing Dr. Taylor the new incubators"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/LAB/karaoke.jpg"
  caption="Karaoke Night"
  link="team"
  width="100%"
%}


{% endcapture %}
{%
  include grid.html
  content=content
  style="square"
%}
