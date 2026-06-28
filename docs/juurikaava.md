---
icon: lucide/pencil
date: 2026-06-27
---

# Juurikaava

Voimme laskea yleisen kaavan äärettömiin neliöjuuriin, joissa on toistuva jäsen.

$$O = \sqrt{n + \sqrt{n + \sqrt{n + \sqrt{n+\ldots}}}} \quad n \in \mathbb{R}_{\geq 0}$$

$$O = \sqrt{n + O} \quad \Big| \, ()^2 \text{ neliön korotusehot}: n + O \geq 0$$

$$O^2 = n + O$$

$$O^2 - O - n = 0$$

$$O = \frac{-(-1) \pm \sqrt{(-1)^2 - 4 \cdot 1 \cdot (-n)}}{2 \cdot 1}$$

$$O = \frac{1 \pm \sqrt{1 + 4n}}{2}$$

Emme voi käyttää negatiivista arvoa sillä:

$$\frac{1 - \sqrt{1+4n}}{2} \leq 0 \text{ jos } n \geq 0$$

Koska alkuperäinen lauseke on aritmeettinen neliöjuuri, meidän on hylättävä negatiiviset vastaukset.

!!! success "Lopullinen kaava"
    $$O = \frac{1 + \sqrt{1+4n}}{2} \quad \text{(jossa } n \text{ on toistuva jäsen)}$$
