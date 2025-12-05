# Diagram Index (Auto-Generated Preview Page)

This page provides a thumbnail index of all diagrams in the `/diagrams/` directory.
It is auto-updating whenever new diagrams are added.

---

## 🔍 Thumbnails

{% for file in site.static_files %}
{% if file.path contains 'diagrams' and file.extname == '.png' %}
### {{ file.name }}
<img src="{{ file.path }}" width="300">
---
{% endif %}
{% endfor %}

