---
icon: lucide/pencil
date: 2026-06-27
---

# Phi

Kultaisen leikkauksen voi laskea usealla tavalla sillä se esiintyy useasse eri matematiikan alalla.

Voimme laskea tarkon arvon kultaiselle leikkaukselle sisäkkäisen juuren avulla:

$$\phi = \sqrt{1 + \sqrt{1 + \sqrt{1 + \sqrt{1+\ldots}}}}$$

$$\phi = \sqrt{1 + \phi} \quad \Big| \, ()^2 \text{ molemmat puolet positiivisia}$$

$$\phi^2 = 1 + \phi$$

$$\phi^2 - \phi - 1 = 0$$

$$\phi = \frac{-(-1) \pm \sqrt{(-1)^2 - 4 \cdot 1 \cdot (-1)}}{2 \cdot 1}$$

$$\phi = \frac{1 \pm \sqrt{5}}{2}$$

$$\phi = \frac{1 + \sqrt{5}}{2}$$

---

Voimme myös käyttää Fibonaccin sarjaa kultaisen leikkauksen likiarvon hankkimiseen, sillä Fibonaccin sarjan kahden vierekkäisen luvun suhde lähestyy kultaista leikkausta.

$$\sum_{n=0}^{\infty} F_n = F_0 + F_1 + F_2 + F_3 + \ldots$$

$$\sum_{n=0}^{\infty} F_n = 0 + 1 + 1 + 2 + \ldots$$

$$\phi = \lim_{n \to \infty} \frac{F_n}{F_{n-1}}$$

$$\phi \approx \frac{F_{20}}{F_{19}} = \frac{6765}{4181} \approx 1{,}61803396\ldots$$

$$\phi = 1{,}61803398\ldots$$
