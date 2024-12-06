---
---
<!---
# Welcome to SecLab at Auburn!
-->
<!---
An engaging 1-3 sentence description of your lab.
-->

<span class="title">{{ description }}

{{ description }}

{ description }

{% include section.html %}

## Highlights

{% capture text %}
<!---
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
-->
{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.jpg"
  link="research"
  title="Our Research"
  text=text
%}


<!---
{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}
-->


{% capture text %}
<!---
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
-->
{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}

<div id="iptracker" style="float: right; visibility: hidden; display: none;">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=oxkl7Keoq53_tjpwqB_b_22kwAXf2iZSu_Zilg3DXIg&cl=ffffff&w=a"></script>
</div>
