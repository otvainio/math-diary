---
icon: lucide/pencil
date: 2026-07-08
---

# Leibnizin ja Newtonin tavoin

*8. heinäkuuta 2026*

## 1

Kappaleen paikka on $x(t) = 2t^3 - 5t^2 + 3t$ (m).

Määritä:

a) nopeus ja kiihtyvyys hetkellä $t = 2$ s

b) hetket, jolloin kappale on hetkellisesti levossa

---

**a)** Funktion $x(t)$ ensimmäisestä ja toisesta derivaatasta voimme tietää kappaleen nopeuden ja kiihtyvyyden.

Lasketaan ensin nopeus ensimmäisestä derivaatasta kun $t = 2$ s

$$x(t) = 2t^3 - 5t^2 + 3t$$

eksponenttisäännöstä:

$$x'(2) = 6 \cdot 2^2 - 10 \cdot 2 + 3$$

$$x'(2) = 7$$

Lasketaan nyt kiihtyvyys kohdassa $t = 2$ s funktion toisesta derivaatasta:

$$x(t) = 2t^3 - 5t^2 + 3t$$

eksponenttisäännöstä:

$$x''(2) = 12 \cdot 2 - 10$$

$$x''(2) = 14$$

**V:** Kappaleen nopeus on kohdassa $t = 2$ s $7$ m/s ja kiihtyvyys $14$ m/s²

**b)** Kappale on levossa, kun nopeus on nolla. Saamme määritettyä nämä kohdat alkuperäisen funktion ensimmäisen derivaatan nollakohdista.

$$x(t) = 2t^3 - 5t^2 + 3t$$

eksponenttisäännöstä:

$$x'(t) = 6t^2 - 10t + 3$$

Lasketaan nollakohdat:

$$0 = 6t^2 - 10t + 3$$

$$t = \frac{-(-10) \pm \sqrt{(-10)^2 - 4 \cdot 6 \cdot 3}}{2 \cdot 6}$$

$$t = \frac{10 \pm \sqrt{28}}{12}$$

$$t = \frac{10 \pm 2\sqrt7}{12}$$

$$t = \frac{5 \pm \sqrt7}{6}$$

**V:** Kappale on hetkellisesti kohdissa $t = \dfrac{5 \pm \sqrt7}{6}$

## 2

Kappaleen kiihtyvyys on $a(t) = 6t - 4$ (m/s²).

Alkunopeus $v(0) = 2$ m/s ja alkupaikka $x(0) = 0$.

Määritä nopeus- ja paikkafunktio.

---

Määritetään ensiksi nopeusfunktio integroimalla epämäärällinen integraali:

$$a(t) = 6t - 4$$

$$\int 6t - 4 \, dt$$

käänteisellä eksponenttisäännöllä:

$$\int 6t - 4 \, dt = 3t^2 - 4t + C$$

Määritetään vakio $C$ tiedolla "Alkunopeus $v(0) = 2$ m/s":

$$3 \cdot 0^2 - 4 \cdot 0 + C = 2$$

$$C = 2$$

Lopullinen nopeusfunktio: $3t^2 - 4t + 2$

Määritetään paikkafunktio integroimalla nopeusfunktio:

$$\int 3t^2 - 4t + 2 \, dt$$

käänteisellä eksponenttisäännöllä:

$$\int 3t^2 - 4t + 2 \, dt = t^3 - 2t^2 + 2t + C$$

Määritetään vakio $C$ tiedolla "alkupaikka $x(0) = 0$."

$$0 = 0^3 - 2 \cdot 0^2 + 2 \cdot 0 + C$$

$$C = 0$$

Lopullinen paikkafunktio: $t^3 - 2t^2 + 2t$

**V:** Nopeusfunktio: $3t^2 - 4t + 2$ ja paikkafunktio: $t^3 - 2t^2 + 2t$
