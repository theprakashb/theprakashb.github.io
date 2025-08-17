---
layout: home
title: One Photon
description: ..and infinite darkness.
---
<div style="text-align:center; margin-top:4em; margin-bottom:3em; line-height:1.4;">
  <h1 style="font-family:Georgia,serif; font-size:2.5em; color:#3a2c1a; margin:0;">One Photon</h1>
  <div style="font-size:1.2em; color:#a89c8a; font-style:italic; margin:0.3em 0;">..and infinite darkness.</div>
  <p style="font-size:1.15em; color:#5a4a36; margin:2em 0 0 0;">
    I write to redeem myself.<br>
    <span style="display:block; margin-top:1em; font-size:1em; color:#a89c8a;">by <span style="font-style:italic; color:#7a5c3a;">prakash</span></span>
  </p>
</div>


<div class="main-content" style="max-width:650px; margin:0 auto;">
  <h2 style="text-align:center; color:#3a2c1a; font-family:Georgia,serif; font-weight:400;">Posts</h2>
  <ul style="list-style:none; padding:0;">
    {% for post in site.posts %}
      <li style="margin-bottom:2.2em;">
        <a href="{{ post.url | relative_url }}" style="font-size:1.3em; color:#7a5c3a; font-family:Georgia,serif; border-bottom:1px dotted #cbbfae;">{{ post.title }}</a>
        <div style="color:#a89c8a; font-size:0.95em; margin-top:0.2em;">{{ post.date | date: "%b %d, %Y" }}</div>
      </li>
    {% endfor %}
  </ul>
</div>


