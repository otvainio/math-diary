---
icon: lucide/pencil
date: 2026-07-03
---

# Vanhoja derivaattoja

*3. heinäkuuta 2026*

Kokoelma vanhoja derivointiharjoituksia, joissa toistuvat tulon, osamäärän ja ketjun säännöt.

---

## 1. Tulon ja ketjun sääntö

$$f(x) = (x^2+1)^4 \cdot \sin^3 x$$

Derivoidaan tekijät erikseen:

$$w = (x^2+1)^4 \quad\Rightarrow\quad w' = 4(x^2+1)^3 \cdot 2x = 8x(x^2+1)^3$$

$$o = \sin^3 x \quad\Rightarrow\quad o' = 3\sin^2 x \cdot \cos x$$

Tulon säännöllä:

$$f'(x) = (x^2+1)^4 \cdot 3\sin^2 x \cos x + 8x(x^2+1)^3 \cdot \sin^3 x$$

---

## 2. Tangentti

$$f(x) = \tan x = \frac{\sin x}{\cos x}$$

Osamäärän säännöllä:

$$f'(x) = \frac{\cos x \cdot \cos x - \sin x \cdot (-\sin x)}{\cos^2 x}$$

$$f'(x) = \frac{\cos^2 x + \sin^2 x}{\cos^2 x} = \frac{1}{\cos^2 x} = \sec^2 x$$

---

## 3. Logaritmi jaettuna sinin neliöllä

$$f(x) = \frac{\ln x}{\sin^2 x}$$

Osittaisderivaatat:

$$u = \ln x \quad\Rightarrow\quad u' = \frac{1}{x}$$

$$k = \sin^2 x \quad\Rightarrow\quad k' = 2\sin x \cos x$$

Huom: $\sin^2 x = (\sin x)^2$, joten ketjun säännöllä derivaatta on $2(\sin x)^1 \cdot \cos x = 2\sin x \cos x$ — potenssi alenee, sisäfunktio säilyy.

Osamäärän säännöllä:

$$f'(x) = \frac{\frac{1}{x}\sin^2 x - \ln x \cdot 2\sin x \cos x}{(\sin^2 x)^2}$$

Supistetaan $\sin x$ osoittajasta ja nimittäjästä:

$$f'(x) = \frac{\frac{\sin x}{x} - 2\ln x \cos x}{\sin^3 x}$$

---

## 4. Neliöjuuri kertaa eksponenttifunktio

$$f(x) = \sqrt{x} \cdot e^{3x}$$

Osittaisderivaatat:

$$w = \sqrt{x} = x^{1/2} \quad\Rightarrow\quad w' = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}$$

$$p = e^{3x} \quad\Rightarrow\quad p' = 3e^{3x}$$

Tulon säännöllä:

$$f'(x) = \sqrt{x} \cdot 3e^{3x} + \frac{1}{2\sqrt{x}} \cdot e^{3x}$$

Otetaan $e^{3x}$ yhteiseksi tekijäksi:

$$f'(x) = e^{3x}\left(3\sqrt{x} + \frac{1}{2\sqrt{x}}\right)$$

---

## 5. Trigonometrinen sievennys ennen derivointia

$$f(x) = \frac{\sin x \cos x}{\cos 2x}$$

Käytetään kaksinkertaisen kulman kaavaa $\sin x \cos x = \tfrac{1}{2}\sin 2x$:

$$f(x) = \frac{\frac{1}{2}\sin 2x}{\cos 2x} = \frac{1}{2} \cdot \frac{\sin 2x}{\cos 2x} = \frac{1}{2}\tan 2x$$

Nyt derivointi on helppoa. Ketjun säännöllä $\tan 2x$:n derivaatta on $\sec^2(2x) \cdot 2$:

$$f'(x) = \frac{1}{2} \cdot \sec^2(2x) \cdot 2 = \sec^2(2x)$$

---

## 6. Neljä sisäkkäistä funktiota

$$f(x) = \sqrt{\sin\left(e^{x^2+1}\right)}$$

Puretaan ketju kerroksittain ulkoa sisälle:

$$r = \sqrt{t} \quad\Rightarrow\quad r' = \frac{1}{2\sqrt{t}} = \frac{1}{2\sqrt{\sin\left(e^{x^2+1}\right)}}$$

$$t = \sin u \quad\Rightarrow\quad t' = \cos u = \cos\left(e^{x^2+1}\right)$$

$$u = e^v \quad\Rightarrow\quad u' = e^v = e^{x^2+1}$$

$$v = x^2+1 \quad\Rightarrow\quad v' = 2x$$

Ketjun säännöllä kerrotaan kaikki yhteen:

$$f'(x) = \frac{1}{2\sqrt{\sin\left(e^{x^2+1}\right)}} \cdot \cos\left(e^{x^2+1}\right) \cdot e^{x^2+1} \cdot 2x$$

Kakkoset kumoavat toisensa:

$$f'(x) = \frac{x \cdot e^{x^2+1} \cdot \cos\left(e^{x^2+1}\right)}{\sqrt{\sin\left(e^{x^2+1}\right)}}$$
