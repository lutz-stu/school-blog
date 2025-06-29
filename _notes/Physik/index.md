---
layout: page
title: Physik
permalink: /Physik
---

# Physik

<strong>Zuletzt aktualisierte Notizen</strong>
<ul>
  {% assign recent_notes = site.notes 
    | where_exp: "note", "note.path contains '/Physik/'"
    | sort: "last_modified_at_timestamp" 
    | reverse %}
  {% for note in recent_notes %}
    <li>
      {{ note.last_modified_at | date: "%d.%m.%Y" }} — 
      <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>