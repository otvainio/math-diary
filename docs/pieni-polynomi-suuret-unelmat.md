---
icon: lucide/pencil
date: 2026-07-03
---

# Pieni polynomi, suuret unelmat

*3. heinäkuuta 2026*

Tarkastellaan funktiota $f(x) = e^x$.

Määritetään sen Maclaurinin sarja (Taylorin sarja kohdassa 0):

$$f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \ldots$$

---

Määritetään funktion $e^x$ derivaattafunktio:

$$f(x) = e^x$$

$$f'(x) = e^x$$

Koska $e^x$:n derivaatta on funktio itse:

$$f''(x) = e^x$$

$$f'''(x) = e^x$$

Lasketaan funktion ja derivaattafunktioiden $y$-akselin leikkauspisteet:

$$f(0) = e^0 = 1$$

$$f'(0) = e^0 = 1$$

Koska $f(x) = f'(x)$, en laske loppuja tässä.

---

Sijoitetaan termit sarjaan:

$$f(x) = 1 + 1x + \frac{1}{2!}x^2 + \frac{1}{3!}x^3 + \ldots$$

$$f(x) = 1 + \frac{1x}{1!} + \frac{1x^2}{2!} + \frac{1x^3}{3!} + \ldots$$

---

Verrataan alkuperäistä funktiota ja sarjakehitelmää neljällä termillä.

**Kohdassa $x = 0$:**

$$f(0) = e^0 = 1$$

$$f(0) = 1 + \frac{1 \cdot 0}{1!} + \frac{1 \cdot 0^2}{2!} + \frac{1 \cdot 0^3}{3!} = 1$$

Molemmat saavat saman arvon kohdassa $x = 0$.

**Kohdassa $x = 1$:**

$$f(1) = e^1 = e = 2{,}71828\ldots$$

$$f(1) = 1 + \frac{1 \cdot 1}{1!} + \frac{1 \cdot 1^2}{2!} + \frac{1 \cdot 1^3}{3!}$$

$$f(1) = 1 + 1 + \frac{1}{2} + \frac{1}{6} = \frac{16}{6} = \frac{8}{3} = 2{,}\overline{6}$$

Funktioiden arvoissa näkee jo selvää eroa.

**Kohdassa $x = 2$:**

$$f(2) = e^2 = 7{,}38905\ldots$$

$$f(2) = 1 + \frac{1 \cdot 2}{1!} + \frac{1 \cdot 2^2}{2!} + \frac{1 \cdot 2^3}{3!}$$

$$f(2) = 1 + 2 + 2 + \frac{8}{6} = \frac{38}{6} = \frac{19}{3} = 6{,}33333\ldots$$

Ero on kasvanut jo yli yksikön.

**Kohdassa $x = 10$:**

Jos taas funktiota kokeillaan jo huomattavasti suuremmalla arvolla kuten $x = 10$:

$$f(10) = e^{10} = 22026{,}46579\ldots$$

$$f(10) = 1 + \frac{1 \cdot 10}{1!} + \frac{1 \cdot 10^2}{2!} + \frac{1 \cdot 10^3}{3!}$$

$$f(10) = 1 + 10 + 50 + \frac{1000}{6} = \frac{1366}{6} = 227{,}66666\ldots$$

Approksimaatiofunktio antaa suurella $x$:n arvolla jo todella huonon approksimaation (noin sadasosan alkuperäisestä).

Suuremmalla termimäärällä saisimme aina vain entistä paremman approksimaatiofunktion.

!!! note "Lopputulos"
    Maclaurinin sarja on erittäin hyvä jäljittelemään oikeita monimutkaisia funktioita varsinkin matalilla $x$:n arvoilla. Korkeammilla $x$:n arvoilla saman tarkkuuden saavuttaminen vaatii kuitenkin erittäin korkean asteen polynomeja.
