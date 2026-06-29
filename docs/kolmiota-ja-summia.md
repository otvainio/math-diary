---
icon: lucide/pencil
date: 2026-06-30
---

# Kolmiota ja summia

*30. kesäkuuta 2026*

Tasasivuisen kolmion sivun pituus on 1. Sen sisään piirretään toinen tasasivuinen kolmio yhdistämällä alkuperäisen kolmion kolmen sivun keskipisteet. Tätä prosessia toistetaan loputtomiin. Laske kaikkien piirrettyjen kolmioiden pinta-alojen summa.

---

Lasketaan ensiksi tasasivuisen kolmion pinta-ala.

Pythagoraan lauseesta saamme korkeuden:

$$x^2 + \left(\frac{1}{2}\right)^2 = 1^2$$

$$x^2 + \frac{1}{4} = 1$$

$$x^2 = \frac{3}{4} \quad \Big| \sqrt{\phantom{x}}$$

$$x = \sqrt{\frac{3}{4}} = \frac{\sqrt{3}}{2} \quad \text{(ei negatiivisia vastauksia, sillä sivut ovat aina positiivisia)}$$

Koska kolmio jakautuu kahteen yhtä suureen osaan:

$$A = 2 \cdot \frac{pk}{2} = 2 \cdot \frac{\frac{1}{2} \cdot \frac{\sqrt{3}}{2}}{2} = \frac{\sqrt{3}}{4}$$

---

Huomaamme, että uuden kolmion pinta-ala on neljäsosa edellisen kolmion pinta-alasta. Voimme myös todistaa tämän laskemalla:

$$x^2 + \left(\frac{1}{4}\right)^2 = \left(\frac{1}{2}\right)^2$$

$$x^2 + \frac{1}{16} = \frac{1}{4}$$

$$x^2 = \frac{3}{16} \quad \Big| \sqrt{\phantom{x}}$$

$$x = \frac{\sqrt{3}}{4}$$

$$A = 2 \cdot \frac{\frac{1}{4} \cdot \frac{\sqrt{3}}{4}}{2} = \frac{\sqrt{3}}{16}$$

Verrataan alueita:

$$\frac{\sqrt{3}}{16} = x \cdot \frac{\sqrt{3}}{4} \quad \Bigg| : \frac{\sqrt{3}}{4}$$

$$x = \frac{1}{4}$$

Jokainen uusi kolmio on siis neljäsosa edellisestä.

---

Koska prosessia toistetaan loputtomiin, saamme geometrisen sarjan:

$$\sum_{n=1}^{\infty} \frac{\sqrt{3}}{4^n} = \frac{\sqrt{3}}{4} + \frac{\sqrt{3}}{16} + \frac{\sqrt{3}}{64} \cdots$$

$$\sum_{n=1}^{\infty} \frac{\sqrt{3}}{4^n} = \frac{\sqrt{3}}{3}$$

!!! success "Vastaus"
    Alueiden pinta-alojen summa on \(\dfrac{\sqrt{3}}{3}\).
