---
layout: default
title: Beyond the Latent Space
---

<div class="sticky-nav">
    <div class="nav-name">Akshaj // Latent Space</div>
    <div class="nav-links">
        <a href="{{ '/' | relative_url }}">← Return to Portfolio</a>
    </div>
</div>

<div style="margin-top: 40px; margin-bottom: 40px;">
    <p style="font-style: italic; color: #57606a;">
        Welcome to the off-duty logs. A hidden digital garden for thoughts on life, engineering quirks, and everything outside the academic stack.
    </p>
</div>

---

## Log Entries

<ul style="list-style-type: none; padding-left: 0; line-height: 1.8;">
  {% for post in site.categories.blog %}
    <li style="margin-bottom: 20px;">
      <span style="color: #57606a; font-family: monospace; margin-right: 15px;">{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url | relative_url }}" style="font-weight: 600; color: #0366d6; text-decoration: none;">{{ post.title }}</a>
      <p style="margin: 4px 0 0 0; font-size: 0.92em; color: #24292f;">{{ post.description }}</p>
    </li>
  {% else %}
    <li style="color: #57606a; font-style: italic;">The ink is still drying. First transmission coming soon.</li>
  {% endfor %}
</ul>