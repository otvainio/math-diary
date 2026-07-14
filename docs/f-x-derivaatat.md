---
icon: lucide/pencil
date: 2026-07-14
---

# f(x), f'(x), f''(x), f'''(x)…

*14. heinäkuuta 2026*

Haluan löytää neliöjuurien sisäiset rakenteet.

Määritetään ensiksi funktion $\sqrt x$ derivaattafunktio:

$$f(x) = \sqrt x$$

Kirjoitetaan uudelleen:

$$f(x) = x^{\frac{1}{2}}$$

Eksponenttisäännöllä:

$$f'(x) = \frac{1}{2} \cdot x^{-\frac{1}{2}}$$

$$f'(x) = \frac{1}{2\sqrt x}$$

Määritetään kolmanteen derivaataan saakka:

$$f'(x) = \frac{1}{2\sqrt x}$$

Osamääräsäännöllä:

$$f''(x) = \frac{2\sqrt x \cdot 0 - 1 \cdot \frac{1}{\sqrt x}}{(2\sqrt x)^2}$$

$$f''(x) = \frac{-\frac{1}{\sqrt x}}{4x}$$

$$f''(x) = -\frac{1}{4x\sqrt x}$$

Osamääräsäännöllä:

$$f'''(x) = \frac{4x \cdot \dfrac{\sqrt x \cdot 0 - (-1) \cdot \frac{1}{2\sqrt x}}{(\sqrt x)^2} - 4 \cdot \left(-\frac{1}{\sqrt x}\right)}{(4x)^2}$$

$$f'''(x) = \frac{\frac{2}{\sqrt x} + \frac{4}{\sqrt x}}{16x^2}$$

$$f'''(x) = \frac{\frac{6}{\sqrt x}}{16x^2}$$

$$f'''(x) = \frac{3}{8x^2\sqrt x}$$

---

Määritetään funktion $\sqrt x$ Taylorin sarja kohdassa 1 derivaattafunktioiden kanssa:

$$f(x) = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \frac{f'''(a)}{3!}(x-a)^3 + \ldots$$

$$f(x) = \sqrt1 + \frac{1}{2\sqrt1}(x-1) + \frac{-\frac{1}{4 \cdot 1 \cdot \sqrt1}}{2}(x-1)^2 + \frac{\frac{3}{8 \cdot 1^2 \sqrt1}}{6}(x-1)^3 + \ldots$$

$$f(x) = 1 + \frac{x-1}{2} - \frac{x^2-2x+1}{8} + \frac{x^3-3x^2+3x-1}{16} + \ldots$$

Voimme laittaa lausekkeen muotoon:

$$\sqrt x = 1 + \frac{x-1}{2} - \frac{x^2-2x+1}{8} + \frac{x^3-3x^2+3x-1}{16} + \ldots$$

kun $x = 2$:

$$\sqrt2 = 1 + \frac{2-1}{2} - \frac{4-4+1}{8} + \frac{8-12+6-1}{16} + \ldots$$

$$\sqrt2 = 1 + \frac{1}{2} - \frac{1}{8} + \frac{1}{16} + \ldots$$

Saimme aikaan vuorottelevan merkkisarjan, joka lähestyy arvoa $\sqrt2$.

---

Työ paljastaa, että monimutkaiset funktiot ovat vain perimmiltään polynomeja. Koko universumi rakentuu polynomeista. Toiset ovat vain suurempia.
