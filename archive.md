---
layout: home
title: Blog Archive
---

<div style="text-align:center; margin-top:4em; margin-bottom:2em;">
  <h1 style="font-family:Georgia,serif; font-size:2.2em; color:#3a2c1a; margin-bottom:0.2em;">Blog Archive</h1>
</div>

<div class="main-content" style="max-width:650px; margin:0 auto;">
  {% for tag in site.tags %}
    <h3 style="color:#3a2c1a; font-family:Georgia,serif; font-weight:400;">{{ tag[0] }}</h3>
    <ul style="list-style:none; padding:0;">
      {% for post in tag[1] %}
        <li style="margin-bottom:1.2em;">
          <a href="{{ post.url }}" style="color:#7a5c3a; font-family:Georgia,serif; border-bottom:1px dotted #cbbfae;">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
  {% endfor %}
</div>
