---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<img src="/images/RadEye_teaser.png" align="left" style="vertical-align: middle; width: 233px; height: 130px;  margin-right: 15px;">

<b>RadEye: Tracking Eye Motion Using FMCW Radar</b> <I>[[PDF]](/files/Shichen25_CHI_Radeye.pdf)</i><br>
<b>Shichen Zhang</b>, Qijun Wang, Kunzhe Song, Qiben Yan and Huacheng Zeng<br>
<I><b>CHI 2025 <span style="color: red;">[Honorable Mention recognition (top 5%)]</span></b> 

<br clear="left">

<img src="/images/Radsee_teaser.png" align="left" style="vertical-align: middle; width: 233px; height: 130px;  margin-right: 15px;">

<b>RadSee: See Your Handwriting Through Walls Using 6GHz FMCW Radar</b> <I>[[PDF]](/files/Shichen25_NDSS_Radsee.pdf)</i><br>
<b>Shichen Zhang</b>, Qijun Wang, Maolin Gan, Zhichao Cao and Huacheng Zeng<br>
<I><b>NDSS Symposium 2025</b> \[Acceptance rate: 19.8%\]</i> <br>

<br clear="left">
