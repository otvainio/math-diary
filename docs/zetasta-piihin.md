---
icon: lucide/pencil
date: 2026-06-28
---

# Zetasta piihin

*28. kesäkuuta 2026*

Tutkitaan eri Riemannin \(\zeta\) funktion arvoja \(\displaystyle\sum_{n=1}^{\infty} \frac{1}{n^k}\) kun \(k\) on parillinen luku.

Huomaamme hienon kuvion:

$$\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$$

$$\sum_{n=1}^{\infty} \frac{1}{n^4} = \frac{\pi^4}{90}$$

$$\sum_{n=1}^{\infty} \frac{1}{n^6} = \frac{\pi^6}{945}$$

Kaikissa näissä esiintyy \(k\) asteen pii.

On myös mielenkiintoista, miten kaikki nämä kolme käyttäytyvät piin likiarvon etsimisessä.

$$\sum_{n=1}^{5} \frac{1}{n^2} = 1 + \frac{1}{4} + \frac{1}{9} + \frac{1}{16} + \frac{1}{25} = 1{,}46361\ldots$$

$$\sum_{n=1}^{5} \frac{1}{n^4} = 1 + \frac{1}{16} + \frac{1}{81} + \frac{1}{256} + \frac{1}{625} = 1{,}08035\ldots$$

$$\sum_{n=1}^{5} \frac{1}{n^6} = 1 + \frac{1}{64} + \frac{1}{729} + \frac{1}{4096} + \frac{1}{15625} = 1{,}01730\ldots$$

Lasketaan kaikkien pii approksimaatio viidellä termillä johtamalla kaava alkuperäisestä summasta.

---

$$\frac{\pi^2}{6} \approx 1{,}46361\ldots \quad \Big| \cdot 6$$

$$\pi^2 \approx 6 \cdot 1{,}46361\ldots \quad \Big| \sqrt{\phantom{x}} \text{ (ei negatiivisia arvoja)}$$

$$\pi \approx \sqrt{6 \cdot 1{,}46361\ldots} \approx 2{,}96338\ldots$$

---

$$\frac{\pi^4}{90} \approx 1{,}08035\ldots \quad \Big| \cdot 90$$

$$\pi^4 \approx 90 \cdot 1{,}08035\ldots \quad \Big| \sqrt[4]{\phantom{x}} \text{ (ei negatiivisia arvoja)}$$

$$\pi \approx \sqrt[4]{90 \cdot 1{,}08035\ldots} \approx 3{,}14016\ldots$$

---

$$\frac{\pi^6}{945} \approx 1{,}01730\ldots \quad \Big| \cdot 945$$

$$\pi^6 \approx 945 \cdot 1{,}01730\ldots \quad \Big| \sqrt[6]{\phantom{x}} \text{ (ei negatiivisia arvoja)}$$

$$\pi \approx \sqrt[6]{945 \cdot 1{,}01730\ldots} \approx 3{,}14157\ldots$$

---

$$\pi = 3{,}14159\ldots$$

!!! success "Johtopäätös"
    Saimme toisen asteen sarjalla 0 piin yksikköä oikein, mutta kuudennen asteen sarjalla saimme vain viidellä termillä jopa 5 yksikköä oikein. Löysin, että piille saa paremman likiarvon korkeimmilla asteilla. Todistamani menetelmä on siis erittäin kelpo ja tehokas menetelmä piin likiarvon hankkimiseen.
