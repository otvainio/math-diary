---
icon: lucide/pencil
date: 2026-08-04
---

# Ympyrä ja juuri

*4. elokuuta 2026*

Tutkitaan polynomia:

$$x^n = 1 \quad \Big| \, n \in \mathbb{Z}^+$$

Asetetaan polynomi $x^n$ napamuotoon:

$$x^n = \left(re^{i\theta}\right)^n$$

$$x^n = r^n e^{i\theta n}$$

Kirjoitetaan $1$ napakoordinaatistossa:

$$1 = 1 \cdot e^{i2\pi k}$$

Voimme nyt verrata kompleksilukuja ja saada:

$$r^n e^{i\theta n} = 1 \cdot e^{i2\pi k}$$

$$r^n = 1$$

Koska $r \in \mathbb{R}$ ja $r > 0$:

$$r > 1 \rightarrow r^n > 1$$

$$r < 1 \rightarrow r^n < 1$$

$$r^n = 1 \rightarrow r = 1$$

$$\theta n = 2\pi k$$

$$\theta = \frac{2\pi k}{n}$$

Otetaan kompleksiluvun $x$ napamuoto:

$$x = re^{i\theta}$$

Sijoitetaan $\theta = \dfrac{2\pi k}{n}$ ja $r = 1$:

$$x = e^{i\frac{2\pi k}{n}}$$

Eulerin kaavaa käyttämällä:

$$x = \cos\left(\frac{2\pi k}{n}\right) + i\sin\left(\frac{2\pi k}{n}\right)$$

Kaava toimii kaikille polynomeille muotoa $x^n = 1$.

---

## Osat selitettynä

$$x = \text{polynomin juuri}$$

$$i \ (\text{imaginääriyksikkö}) = \sqrt{-1}$$

$$2\pi \ (\text{yksi rotaatio})$$

$$k \ (\text{kuinka mones juuri lasketaan})$$

$$n \ (\text{polynomin aste})$$

Uniikit arvot kaavalla saadaan arvoilla $k = 0, 1, 2, 3 \ldots n-1$.

---

## Kokeillaan kaavaa polynomiin $x^4 = 1$

$$x = \cos\left(\frac{2\pi k}{n}\right) + i\sin\left(\frac{2\pi k}{n}\right)$$

Kaikissa tapauksissa $n = 4$.

**$k = 0$**

$$x = \cos(0) + i\sin(0)$$

$$x = 1$$

**$k = 1$**

$$x = \cos\left(\frac{2\pi}{4}\right) + i\sin\left(\frac{2\pi}{4}\right)$$

$$x = i$$

**$k = 2$**

$$x = \cos\left(\frac{4\pi}{4}\right) + i\sin\left(\frac{4\pi}{4}\right)$$

$$x = -1$$

**$k = 3$**

$$x = \cos\left(\frac{6\pi}{4}\right) + i\sin\left(\frac{6\pi}{4}\right)$$

$$x = -i$$

**$k = 4$**

$$x = \cos\left(\frac{8\pi}{4}\right) + i\sin\left(\frac{8\pi}{4}\right)$$

$$x = 1$$

Huomaamme miten juuret toistuvat kun $k$ kasvaa.

---

Voimme todistaa kaavan toimivuuden myös jakamalla $x^4 = 1$ tekijöihin perinteisesti:

$$x^4 = 1$$

$$x^4 - 1 = 0$$

Kahden neliön erotus -identiteetillä:

$$\left(x^2-1\right)\left(x^2+1\right) = 0$$

Tulon nollasäännöllä:

$$x^2 - 1 = 0$$

$$x^2 = 1$$

$$x = \pm 1$$

$$x^2 + 1 = 0$$

$$x^2 = -1$$

$$x = \pm\sqrt{-1}$$

$$x = \pm i$$

$$x = 1, \ -1, \ i, \ -i$$

Saimme samat juuret tekijöillä kuin kaavalla.

---

## Kokeillaan kaavaa hankalempaan polynomiin $x^5 = 1$

$$x^5 = 1$$

$$x = \cos\left(\frac{2\pi k}{n}\right) + i\sin\left(\frac{2\pi k}{n}\right)$$

Kaikissa tapauksissa $n = 5$.

**$k = 0$**

$$x = \cos(0) + i\sin(0)$$

$$x = 1$$

**$k = 1$**

$$x = \cos\left(\frac{2\pi}{5}\right) + i\sin\left(\frac{2\pi}{5}\right)$$

$$x = \frac{-1+\sqrt{5}}{4} + \sqrt{\frac{5+\sqrt{5}}{8}}\,i$$

**$k = 2$**

$$x = \cos\left(\frac{4\pi}{5}\right) + i\sin\left(\frac{4\pi}{5}\right)$$

$$x = -\frac{1+\sqrt{5}}{4} + \sqrt{\frac{5-\sqrt{5}}{8}}\,i$$

**$k = 3$**

$$x = \cos\left(\frac{6\pi}{5}\right) + i\sin\left(\frac{6\pi}{5}\right)$$

$$x = -\frac{1+\sqrt{5}}{4} - \sqrt{\frac{5-\sqrt{5}}{8}}\,i$$

**$k = 4$**

$$x = \cos\left(\frac{8\pi}{5}\right) + i\sin\left(\frac{8\pi}{5}\right)$$

$$x = \frac{-1+\sqrt{5}}{4} - \sqrt{\frac{5+\sqrt{5}}{8}}\,i$$

Kaikki viisi juurta:

$$x = 1$$

$$x = \frac{-1+\sqrt{5}}{4} + \sqrt{\frac{5+\sqrt{5}}{8}}\,i$$

$$x = -\frac{1+\sqrt{5}}{4} + \sqrt{\frac{5-\sqrt{5}}{8}}\,i$$

$$x = -\frac{1+\sqrt{5}}{4} - \sqrt{\frac{5-\sqrt{5}}{8}}\,i$$

$$x = \frac{-1+\sqrt{5}}{4} - \sqrt{\frac{5+\sqrt{5}}{8}}\,i$$

!!! success "Lopputulos"
    Johtamani kaava

    $$x = \cos\left(\frac{2\pi k}{n}\right) + i\sin\left(\frac{2\pi k}{n}\right)$$

    on varma tapa löytää kaikkien polynomien muotoa $x^n = 1$ kompleksijuuret. Työ paljastaa myös sen, miten kaikki juuret löytyvät yksikköympyrältä.
