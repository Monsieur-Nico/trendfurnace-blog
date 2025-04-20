---
layout: default
title: TrendFurnace Blog
---

# 🔥 TrendFurnace Blog

Welcome to **TrendFurnace** — your daily source of AI-powered, fact-checked breakdowns of what's trending across the web.

Every post is:

- 🧠 Written using intelligent summarization
- ✅ Verified to ensure factual accuracy
- 🚀 Published within hours of the trend emerging

---

## 📌 Latest Trends

<div class="post-list">
  {% for post in site.posts %}
  <div class="post-card">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
    <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    <p><a href="{{ post.url | relative_url }}">Read more →</a></p>
  </div>
  {% endfor %}
</div>

---

Stay tuned — new posts drop every day. This project is built entirely on automation + integrity.

Want to suggest a topic or collaborate? Reach out anytime!
