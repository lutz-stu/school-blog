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

#### Gegeben:

$$ f(x) = ax^2 + bx + c $$

#### 1. $a$ ausklammern:

$$ f(x) = a \left( x^2 + \frac{b}{a} \cdot x \right) + c $$

#### 2. Quadratische Ergänzung durchführen:

$$ f(x) = a \left( x^2 + \frac{b}{a} \cdot x + \left( 0,5 \cdot \frac{b}{a} \right)^2 - \left( 0,5 \cdot \frac{b}{a} \right)^2 \right) + c $$

#### 3. Klammern auflösen (binomische Formel):

$$ f(x) = a \left[ \left( x + 0,5 \cdot \frac{b}{a} \right)^2 - a \cdot \left( 0,5 \cdot \frac{b}{a} \right)^2 \right] + c $$

#### 4. Klammern auflösen:

$$ f(x) = a \cdot \left( x + 0,5 \cdot \frac{b}{a} \right)^2 - a \cdot \left( 0,5 \cdot \frac{b}{a} \right)^2 + c $$

#### 5. Scheitelpunktform aufstellen:

$$ f(x) = a \cdot \left( x + 0,5 \cdot \frac{b}{a} \right)^2 + \left( c - a \cdot \left( 0,5 \cdot \frac{b}{a} \right)^2 \right) $$

## Nullstellen berechnen

- $ 0 = ax^2 + bx + c $ lösen
  - durch [Umstellen](/Mathe/quadratische-gleichungen#umstellen){: .internal-link}
  - durch [Ausklammern](/Mathe/quadratische-gleichungen#ausklammern){: .internal-link}
  - mit dem [Satz von Vieta](/Mathe/quadratische-gleichungen#satz-von-vieta){: .internal-link}
  - mit der [pq-Formel](/Mathe/quadratische-gleichungen#pq-formel){: .internal-link}