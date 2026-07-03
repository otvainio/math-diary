---
icon: lucide/pencil
date: 2026-07-03
---

# Matematiikan hienoin kaava

*3. heinäkuuta 2026*

Otetaan ensiksi ääretön sarja funktiolle $e^x$:

$$e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}$$

$$\sum_{n=0}^{\infty} \frac{x^n}{n!} = 1 + \frac{x}{1!} + \frac{x^2}{2!} + \frac{x^3}{3!} + \frac{x^4}{4!} + \frac{x^5}{5!} + \ldots$$

---

Annetaan $x$:n olla $i\theta$:

$$e^{i\theta} = 1 + \frac{i\theta}{1!} + \frac{(i\theta)^2}{2!} + \frac{(i\theta)^3}{3!} + \frac{(i\theta)^4}{4!} + \frac{(i\theta)^5}{5!} + \ldots$$

$$e^{i\theta} = 1 + \frac{i\theta}{1!} + \frac{-1\theta^2}{2!} + \frac{-i\theta^3}{3!} + \frac{1\theta^4}{4!} + \frac{i\theta^5}{5!} + \ldots$$

---

Ryhmitellään sarjat:

$$e^{i\theta} = 1 + \frac{-1\theta^2}{2!} + \frac{\theta^4}{4!} + \ldots + i\left(\frac{\theta}{1!} + \frac{-\theta^3}{3!} + \frac{\theta^5}{5!} + \ldots\right)$$

---

Verrataan näitä $\cos(\theta)$:n ja $\sin(\theta)$:n äärettömiin sarjoihin:

$$\cos\theta = 1 - \frac{\theta^2}{2!} + \frac{\theta^4}{4!} - \frac{\theta^6}{6!} + \ldots$$

$$\sin\theta = \theta - \frac{\theta^3}{3!} + \frac{\theta^5}{5!} - \frac{\theta^7}{7!} + \ldots$$

Sijoitetaan nämä alkuperäiseen sarjaan $e^{i\theta}$:

$$e^{i\theta} = \cos(\theta) + i\sin(\theta)$$

Johdin juuri matematiikan hienoimman kaavan.

---

Voin näyttää myös jotain hienompaa. Sijoitetaan $\theta = \pi$:

$$e^{i\pi} = \cos(\pi) + i\sin(\pi)$$

$$e^{i\pi} = -1 + i \cdot 0$$

$$e^{i\pi} = -1$$

$$e^{i\pi} + 1 = 0$$

!!! success "Eulerin identiteetti"
    $$e^{i\pi} + 1 = 0$$

    Viisi matematiikan tärkeintä vakiota — $e$, $i$, $\pi$, $1$ ja $0$ — syntyi muutamalla pienellä kikalla samaan yhtälöön.
