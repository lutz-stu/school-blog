---
layout: page
title: Politik
permalink: /Politik
---

# Politik

## Die drei Gewalten des Staats

- 📜 [[Legislative]] – Die gesetzgebende Gewalt  
- 🛡️ [[Exekutive]] – Die ausführende Gewalt  
- ⚖️ [[Judikative]] – Die rechtsprechende Gewalt

<strong>Zuletzt aktualisierte Notizen</strong>
<ul>
  {% assign recent_notes = site.notes 
    | where_exp: "note", "note.path contains '/Politik/'"
    | sort: "last_modified_at_timestamp" 
    | reverse %}
  {% for note in recent_notes %}
    <li>
      {{ note.last_modified_at | date: "%d.%m.%Y" }} — 
      <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>