---
icon: lucide/pencil
date: 2026-07-08
---

# Fysiikka 1

*8. heinäkuuta 2026*

Kappaleen nopeus on $v(t) = 3t^2 - 2t$ (m/s).

Laske:

a) kiihtyvyys hetkellä $t = 2$ s

b) paikan muutos välillä $0 \ldots 3$ s

---

## a)

Tarvitsemme käyrän tangentin kulmakertoimen kiihtyvyyden määrittämiseksi tietyllä hetkellä.

Määritetään $v'(t)$:

$$v(t) = 3t^2 - 2t$$

Eksponenttisäännöstä:

$$v'(t) = 6t - 2$$

Tangentin kulmakertoimen arvo kohdassa $t = 2$ s:

$$v'(2) = 6 \cdot 2 - 2$$

$$v'(2) = 10$$

Tangentin kulmakertoimen yksikkö on m/s², joten kiihtyvyys hetkellä $2$ s on $10$ m/s².

---

## b)

Integroimalla funktio $v(t)$ $t$:n suhteen välillä $0 \ldots 3$ saamme määritettyä paikan muutoksen.

Lasketaan määrätty integraali:

$$\int_0^3 3t^2 - 2t \, dt$$

Käänteisellä eksponenttisäännöllä:

$$\int_0^3 3t^2 - 2t \, dt = t^3 - t^2$$

Sijoitetaan rajat:

$$3^3 - 3^2 - (0^3 - 0^2) = 18$$

Paikan muutos aikavälillä $0 \ldots 3$ s on siis $18$ m.
