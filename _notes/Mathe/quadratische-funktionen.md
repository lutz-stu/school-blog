---
title: Quadratische Funktionen
---

### Normalform

$$ f(x) = ax^2 + bx + c $$

- $a$: Streckungs/Stauchungsfaktor; Spiegelung an der x-Achse, wenn negativ
- $c$: y-Achsenabschnitt

### Scheitelpunktform

$$ f(x) = a(x - d)^2 + e $$

- $a$: Streckungs/Stauchungsfaktor; Spiegelung an der x-Achse, wenn negativ
- $d$: x-Koordinate des Scheitelpunkts (Achtung: Vorzeichen beachten!)
- $e$: y-Koordinate des Scheitelpunkts

### Faktorisierte Form

$$ f(x) = a(x - x_1)(x - x_2) $$

- $a$: Streckungs/Stauchungsfaktor; Spiegelung an der x-Achse, wenn negativ
- $x_1$, $x_2$: Nullstellen der Funktion

## Umformen

### Normalform in Scheitelpunktform umwandeln (Quadratische Ergänzung)

#### Gegeben (Beispiel):

$$ f(x) = 1.5x^2 + 6x + 5 $$

#### 1. $a$ ($1.5$) ausklammern:

$$ f(x) = 1.5 \left( x^2 + 4x \right) + 5 $$

#### 2. Quadratische Ergänzung durchführen:

$$ f(x) = 1.5 \left( x^2 + 4x + \left( \frac{4}{2} \right) ^2 - \left( \frac{4}{2} \right) ^2 \right) + 5 $$

#### 3. Klammern auflösen (binomische Formel):

$$ f(x) = 1.5 \left[ \left( x + 2 \right)^2 - 4 \right] + 5 $$

#### 4. Klammern auflösen:

$$ f(x) = 1.5 \left( x + 2 \right)^2 - 6 + 5 $$

#### 5. Scheitelpunktform aufstellen:

$$ f(x) = 1.5 \left( x + 2 \right)^2 - 1 $$

## Nullstellen berechnen

- $ 0 = ax^2 + bx + c $ lösen
  - durch [Umstellen](/Mathe/quadratische-gleichungen#umstellen){: .internal-link}
  - durch [Ausklammern](/Mathe/quadratische-gleichungen#ausklammern){: .internal-link}
  - mit dem [Satz von Vieta](/Mathe/quadratische-gleichungen#satz-von-vieta){: .internal-link}
  - mit der [pq-Formel](/Mathe/quadratische-gleichungen#pq-formel){: .internal-link}

## Schnittpunkt zweier Funktionen berechnen

1. Funktionen gleichsetzen
2. Beide Terme auf eine Seite bringen, sodass eine Gleichung der Form $$ 0 = ax^2 + bx + c $$ entsteht
3. [[quadratische-gleichungen|Gleichung lösen]] (es können 0/1/2 Lösungen entstehen)
4. $x$-Wert(e) in eine der beiden Funktionen einsetzen, um $y$ zu berechnen
5. Schnittpunkt(e) angeben: $$ S(x, y) $$
