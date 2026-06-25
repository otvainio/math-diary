---
icon: lucide/book-open
---

# Vainio Matematiikka

Tervetuloa matematiikkapäiväkirjaani. Tänne tallennan oivalluksia, ratkaisuja ja kysymyksiä — isoja ja pieniä.

Matematiikka ei ole vain laskemista. Se on tapa nähdä maailma.

---

## Viimeisimmät merkinnät

Sivusto on juuri avattu. Ensimmäiset merkinnät tulevat pian.

---

## Euler'n identiteetti

$$
e^{i\pi} + 1 = 0
$$

Yksi kauneimmista kaavoista matematiikassa — yhdistää viisi perusvakiota yhdeksi lausekkeeksi.

<script id="MathJax-script" src="https://unpkg.com/mathjax@3/es5/tex-mml-chtml.js"></script>
<script>
  window.MathJax = {
    tex: {
      inlineMath: [["\\(", "\\)"]],
      displayMath: [["\\[", "\\]"]],
      processEscapes: true,
      processEnvironments: true
    },
    options: {
      ignoreHtmlClass: ".*|",
      processHtmlClass: "arithmatex"
    }
  };

  document$.subscribe(() => {
    MathJax.startup.output.clearCache()
    MathJax.typesetClear()
    MathJax.texReset()
    MathJax.typesetPromise()
  })
</script>
