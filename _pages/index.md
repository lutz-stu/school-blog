---
layout: page
title: Startseite
id: home
permalink: /
---

# Hallo! 🌱

<!--
<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p>
-->

<strong>Alle Notizen nach Ordnern</strong>

{% assign notes_by_folder = site.notes | group_by_exp: "note", "note.path | split: '/' | slice: 1, 1" %}
<ul>
  {% for folder in notes_by_folder %}
    <li>
      <strong>{{ folder.name | default: "Root" }}</strong>
      <ul>
        {% for note in folder.items %}
          <li>
            <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
          </li>
        {% endfor %}
      </ul>
    </li>
  {% endfor %}
</ul>


<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
