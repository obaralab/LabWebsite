---
name: Lilly Castorena
image: images/Lilly.jpg
role: undergrad
group: active
---

Lilly's Story



{% capture content %}
{%
  include figure.html
  image="images/Lilly-Team/Lilly-1.jpeg"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/Lilly-Team/Lilly-2.jpeg"
  link="team"
  width="100%"
%}

{% endcapture %}
{%
  include grid.html
  content=content
  
 %}

