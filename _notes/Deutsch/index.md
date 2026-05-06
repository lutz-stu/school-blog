---
layout: page
title: Deutsch
permalink: /Deutsch
---

# Deutsch

## Analysieren 🔎
- 📖 [[Einen epischen Text analysieren]] — z.B. Romanauszug, Erzählung, …
- 🪶 [[Einen lyrischen Text analysieren]] — z.B. Gedicht, Lied, …

## Informieren 📰
- ℹ️ [[Einen informierenden Text verfassen]]

---

<strong>Zuletzt aktualisierte Notizen</strong>
<ul>
  {% assign recent_notes = site.notes 
    | where_exp: "note", "note.path contains '/Deutsch/' and note.path != '_notes/Deutsch/index.md'"
    | sort: "last_modified_at_timestamp" 
    | reverse %}
  {% for note in recent_notes %}
    <li>
      {{ note.last_modified_at | date: "%d.%m.%Y" }} — 
      <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>
