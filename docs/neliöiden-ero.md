---
icon: lucide/pencil
date: 2026-06-25
---

# Neliöiden ero

| \(n\) | \(n^2\) |
|------:|--------:|
| 1 | 1 |
| 2 | 4 |
| 3 | 9 |
| 4 | 16 |

Kun tutkimme näitä lukuja, huomaamme, että peräkkäisten neliöiden ero kasvaa aina kahdella.

---

*Voimme todistaa tämän:*

$$
(n+1)^2 = n^2 + 2n + 1
$$

Vähennetään alkuperäinen \(n^2\), jotta tiedemmä kuinka paljon luku kasvoi:

$$
n^2 + 2n + 1 - n^2 = 2n + 1
$$

*Muodostetaan lauseke seuraavalle erolle:*

$$
(n+2)^2 - (n+1)^2 = n^2 + 4n + 4 - (n^2 + 2n + 1) = 2n + 3
$$

*Verrataan näitä kahta eroa:*

$$
(2n + 3) - (2n + 1) = 2
$$

!!! success "Johtopäätös"
    Ero kahden peräkkäisen täydellisen neliön välillä kasvaa aina luvulla **2**.
