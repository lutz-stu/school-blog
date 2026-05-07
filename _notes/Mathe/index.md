---
layout: page
title: Mathe
permalink: /Mathe
---

# Mathe

## Algebra 🔢
- 💯 [[Prozente]]
- 🌱 [[Wurzeln]] – Wurzelgesetze, Wurzelgleichungen, etc.
- 💶 [[Zinsen]]
- 🧮 [[Potenzen]] – Potenzgesetze, Potenzgleichungen, etc.
- 🧩 [[Binomische Formeln]]
- ✏️ [[Lineare Gleichungen und Gleichungssysteme]] – Gleichungen lösen, Variablen bestimmen, Gleichungssysteme mit zwei Unbekannten
- 🟦 [[Quadratische Gleichungen]] – Mitternachtsformel, pq-Formel, Nullstellen und Parabeln

## Geometrie 📏
- 📐 [[Größeneneinheiten]] – Längen, Flächen, Volumen, Masse
- ⬛ [[Flächeninhalt und Umfang von Vielecken]] – Kreis, Dreieck, Quadrat, Rechteck, Trapez, Parallelogramm
- 📦 [[Flächeninhalt und Volumen von Körpern]] – Würfel, Quader, Prisma, Pyramide, Kegel, Zylinder, Kugel
- 📏 [[Zentrische Steckung und Ähnlichkeit]] – Streckfaktor, Strahlensatz, Ähnlichkeit
- 🔺 [[Geometrie und Trigonometrie im Dreieck]] – Rechtwinklige Dreiecke, Satz d. Pythagoras, Kosinussatz, An-/Gegenkathete + Hypotenuse

## Funktionen 📈
- ➖ [[Lineare Funktionen]] – $ f(x) = mx + b $
- ⬜ [[Quadratische Funktionen]] – $ f(x) = a(x - d)^2 + e $ / $ f(x) = ax^2 + bx + c $
- 📈 [[Exponentialfunktionen]] – $ f(x) = \pm c \cdot a^x+b + d $
- 🌊 [[Sinus- & Kosinusfunktion]] – $ f(x) = a \cdot \sin(b \cdot x) + d $ / $ f(x) = a \cdot \cos(b \cdot x) + d $

## Stochastik 🎲
- 🎲 [[Zufallsexperimente]] – mit/ohne Zurücklegen, Laplace-Experiment, etc.
- 🌳 [[Baumdiagramme]] – Pfadregeln, etc.
- 🎯 [[Bedingte Wahrscheinlichkeit]] – Stochastische Unabhängigkeit, Vierfeldertafel, umgekehrtes Bamdiagramm

<!--
<strong>Zuletzt aktualisierte Notizen</strong>
<ul>
  {% assign recent_notes = site.notes 
    | where_exp: "note", "note.path contains '/Mathe/'"
    | sort: "last_modified_at_timestamp" 
    | reverse %}
  {% for note in recent_notes %}
    <li>
      {{ note.last_modified_at | date: "%d.%m.%Y" }} — 
      <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>
-->