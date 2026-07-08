---
icon: lucide/pencil
date: 2026-07-08
---

# √2 + √3 + √5 on irrationaalinen

*8. heinäkuuta 2026*

Oletetaan, että luku $\sqrt2 + \sqrt3 + \sqrt5$ on rationaalinen:

$$\sqrt2 + \sqrt3 + \sqrt5 = \frac{o}{t} \quad \text{syt}(o,t) = 1$$

$$\sqrt2 + \sqrt3 = \frac{o}{t} - \sqrt5 \quad \Big|\, ()^2 \text{ molemmat puolet positiivisia}$$

$$\left(\sqrt2 + \sqrt3\right)^2 = \left(\frac{o}{t} - \sqrt5\right)^2$$

$$2 + 2\sqrt6 + 3 = \frac{o^2}{t^2} - 2\sqrt5\,\frac{o}{t} + 5$$

$$2\sqrt6 + 2\sqrt5\,\frac{o}{t} = \frac{o^2}{t^2} \quad \Big|\, ()^2 \text{ molemmat puolet positiivisia}$$

$$\left(2\sqrt6 + 2\sqrt5\,\frac{o}{t}\right)^2 = \frac{o^4}{t^4}$$

$$24 + 8\sqrt{30}\,\frac{o}{t} + 20\,\frac{o^2}{t^2} = \frac{o^4}{t^4}$$

$$8\sqrt{30}\,\frac{o}{t} = \frac{o^4}{t^4} - 20\,\frac{o^2}{t^2} - 24$$

Koska oikea puoli koostuu vain rationaaliluvuista ja vasen puoli rationaaliluvuista paitsi $\sqrt{30}$, täytyy $\sqrt{30}$:n olla myös rationaalinen.

---

$$\sqrt{30} = \frac{r}{s} \quad \text{syt}(r,s) = 1$$

$$\sqrt{30} = \frac{r}{s} \quad \Big|\, ()^2 \text{ molemmat puolet positiivisia}$$

$$30 = \frac{r^2}{s^2} \quad \Big|\, \cdot s^2$$

$$30s^2 = r^2$$

$$2(15s^2) = r^2$$

Koska $r^2$ voidaan kirjoittaa muodossa $2k$, se on parillinen.

$$30s^2 = (2k)^2$$

$$30s^2 = 4k^2 \quad \Big|\, : 2$$

$$15s^2 = 2k^2$$

Koska $2k^2$ on parillinen, täytyy myös luvun $15s^2$ olla parillinen. Koska kerroin 15 ei ole parillinen, luvun $s$ täytyy siis olla parillinen, jotta yhtäsuuruus toteutuu.

Todistuksessa syntyi looginen ristiriita, joten alkuperäisen väittämän täytyy olla väärä.

!!! success "Vastaus"
    Luku $\sqrt2 + \sqrt3 + \sqrt5$ on irrationaalinen.
