---
icon: lucide/pencil
date: 2026-07-03
---

# √2 + √3 on irrationaalinen

*3. heinäkuuta 2026*

Oletetaan, että $\sqrt{2} + \sqrt{3}$ voidaan kirjoittaa rationaalilukuna $\dfrac{o}{v}$:

$$\sqrt{2} + \sqrt{3} = \frac{o}{v} \quad \text{syt}(o,v) = 1$$

Korotetaan molemmat puolet toiseen potenssiin (molemmat puolet positiivisia):

$$\left(\sqrt{2} + \sqrt{3}\right)^2 = \left(\frac{o}{v}\right)^2$$

$$2 + 2\cdot\sqrt{2}\cdot\sqrt{3} + 3 = \frac{o^2}{v^2}$$

$$2 + \sqrt{24} + 3 = \frac{o^2}{v^2}$$

$$\sqrt{24} = \frac{o^2}{v^2} - 5 = \frac{o^2 - 5v^2}{v^2}$$

$$2\sqrt{6} = \frac{o^2 - 5v^2}{v^2}$$

$\sqrt{6}$:n pitää siis olla kahden kokonaisluvun suhde, jotta alkuperäinen oletuksemme pitäisi paikkaansa. Kokeillaan onko $\sqrt{6}$ irrationaalinen.

---

Oletetaan, että $\sqrt{6} = \dfrac{t}{s}$, missä $\text{syt}(t,s) = 1$:

$$6 = \frac{t^2}{s^2} \quad \Big|\, \cdot s^2$$

$$6s^2 = t^2$$

$$2(3s^2) = t^2$$

Luvun $t$ täytyy siis olla parillinen, koska $t^2$ on jaollinen kahdella. Kirjoitetaan $t = 2k$:

$$6s^2 = (2k)^2 = 4k^2 \quad \Big|\, :2$$

$$3s^2 = 2k^2$$

Koska $2k^2$ on parillinen, myös $3s^2$ täytyy olla parillinen, sillä ne ovat yhtäsuuria. Koska 3 on pariton, $s^2$:n täytyy olla parillinen, joten myös $s$ on parillinen.

Koska kummatkin luvut $t$ ja $s$ ovat parillisia, päädyimme ristiriitaan oletuksen $\text{syt}(t,s)=1$ kanssa.

Täten $\sqrt{6}$ on irrationaalinen — ja siis myös $2\sqrt{6}$ on irrationaalinen. Mutta oletimme sen olevan rationaalinen. Ristiriita.

!!! success "Vastaus"
    Luku $\sqrt{2} + \sqrt{3}$ on irrationaalinen.
