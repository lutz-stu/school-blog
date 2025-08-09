---
layout: page
title: Startseite
id: home
permalink: /
---

# Hallo! 🌱

<style>
.subject-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2em;
  row-gap: 2em; /* Gleicher Abstand zwischen Zeilen wie Spalten */
  justify-content: flex-start;
  margin-bottom: 2em;
  margin-top: 2em; /* Standard margin unter h1 */
}
.subject-card {
  background: #f5f7ff;
  border-radius: 24px;
  box-shadow: 0 4px 24px #0001;
  width: 160px;
  height: 180px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-bottom: 0; /* Kein zusätzlicher Abstand, gap übernimmt das */
  transition: transform 0.15s;
  text-align: center;
  text-decoration: none;
  color: inherit;
}
.subject-card:hover {
  transform: translateY(-4px) scale(1.04);
  box-shadow: 0 8px 32px #0002;
}
.subject-card img {
  width: 56px;
  height: 56px;
  margin-bottom: 1em;
}
.subject-title {
  font-weight: bold;
  font-size: 1.1em;
  margin-bottom: 0.3em;
}
</style>

<p style="padding: 3em 1em; background: #f7ece8ff; border-radius: 4px;">
    <b>Diese Webseite ist noch in der Entwicklungsphase und wird nur privat verwendet.</b>
</p>

<div class="subject-grid">
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Latein">
    <img src="https://cdn-icons-png.flaticon.com/512/9085/9085836.png" alt="Latein Icon"/>
    <div class="subject-title">Latein</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Deutsch">
    <img src="https://cdn-icons-png.flaticon.com/512/8276/8276821.png" alt="Deutsch Icon"/>
    <div class="subject-title">Deutsch</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Mathe">
    <img src="https://cdn-icons-png.flaticon.com/512/2084/2084541.png" alt="Mathe Icon"/>
    <div class="subject-title">Mathe</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Englisch">
    <img src="https://cdn-icons-png.flaticon.com/512/330/330425.png" alt="Englisch Icon"/>
    <div class="subject-title">Englisch</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Informatik">
    <img src="https://cdn-icons-png.flaticon.com/512/8824/8824175.png" alt="Informatik Icon"/>
    <div class="subject-title">Informatik</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Politik">
    <img src="https://cdn-icons-png.flaticon.com/512/1651/1651652.png" alt="Politik Icon"/>
    <div class="subject-title">Politik</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Physik">
    <img src="https://cdn-icons-png.flaticon.com/512/887/887862.png" alt="Physik Icon"/>
    <div class="subject-title">Physik</div>
  </a>
  <a class="subject-card internal-link" href="{{ site.baseurl }}/Geschichte">
    <img src="https://cdn-icons-png.flaticon.com/512/124/124784.png" alt="Geschichte Icon"/>
    <div class="subject-title">Geschichte</div>
  </a>
</div>


<!-- <strong>Alle Notizen nach Ordnern</strong> 
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
</ul> -->


## Zuletzt aktualisierte Notizen

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes %}
    <li>
      {{ note.last_modified_at | date: "%d.%m.%Y" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
