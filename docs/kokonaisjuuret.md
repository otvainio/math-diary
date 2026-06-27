---
icon: lucide/pencil
date: 2026-06-27
---

# Kokonaisjuuret

Tutkitaan polynomia \((x^2 - n)\)

Kysymys kuuluu: Millä luvun \(n\) arvoilla polynomia voidaan jakaa tekijöiksi, joiden juuret ovat kokonaislukuja.

Kun käytämme neliön erotuksen kaavaa huomaamme, että

$$(x^2 - n) = (x + \sqrt{n})(x - \sqrt{n})$$

Koska kaavan mukaan polynomi jakautuu luvun \(n\) neliöjuuriksi, jotta saamme kokonaisluku vastauksen tarvitsemme luvuksi \(n\) täydellisen neliön.

Jos taas pelkkä rationaaliluku riittää, voi luku \(n\) myös olla kahden täydellisen neliön osamäärä.

Luku \(n\) ei voi myös olla negatiivinen, sillä:

$$n = -k \quad (k \geq 0)$$

$$(x^2 - n) = (x + \sqrt{n})(x - \sqrt{n})$$

$$\left(x + \sqrt{-k}\right)\left(x - \sqrt{-k}\right)$$

Tällöin päädymme imaginäärijuureen.

---

Tämä sääntö voidaan myös yleistää korkeampien asteiden polynomeihin.

$$(x^k - n)$$

$$x^k = n \quad \Big| \, \sqrt[k]{\phantom{x}}$$

$$x = \sqrt[k]{n} \qquad \left(\pm\sqrt[k]{n} \text{ jos } k \equiv 0 \pmod{2}\right)$$

Jotta saamme kokonaisluku ratkaisun, tarvitsemme luvun \(n\) olla täydellinen \(k\) asteen luku. Jos meille riittää rationaaliluku, voi luku olla myös kahden täydellisen \(k\) asteen luvun välinen rationaaliluku.
