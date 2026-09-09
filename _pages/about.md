---
permalink: /
title: ""
excerpt: "Machine learning researcher in NLP, information extraction and knowledge graphs."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======
I build machine learning systems that turn text into structured knowledge —
information extraction, entity linking and knowledge graphs, across general and
biomedical domains. My work has produced open datasets and benchmarks that other
groups build on, including [DWIE](https://github.com/klimzaporojets/dwie),
[TempEL](https://github.com/klimzaporojets/TempEL) and
[BioDEX](https://github.com/KarelDO/BioDEX), alongside 24 peer-reviewed
publications at ACL, NeurIPS, VLDB and CIKM.

Before returning to research I spent seven years building software in industry,
including production machine learning for fraud prevention at
[MercadoLibre](https://www.mercadolibre.com). Most recently I held a Marie
Skłodowska-Curie Postdoctoral Fellowship at [Aarhus
University](https://cs.au.dk/), in the [Algorithms, Data and Artificial
Intelligence](https://cs.au.dk/research/algorithms-data-and-artificial-intelligence)
group, working alongside the [INDE Lab](https://indelab.org/) at the University
of Amsterdam.

**I am open to research and applied-ML roles in industry and academia.**

Selected work
======
{% include selected-work.html %}

[Full publication list →](/research/){: .btn} &nbsp;
[CV and résumé →](/cv/){: .btn}

Technical skills
======
**Programming** — Python (10+ yrs), Java (7+ yrs), SQL, Scala, Groovy, JavaScript<br>
**Machine learning** — PyTorch, Pandas, scikit-learn, NLTK, spaCy, PyTorch Geometric, NetworkX, TensorFlow<br>
**Data and retrieval** — Spark, Lucene, UIMA, Tableau, R<br>
**Databases** — Oracle, MySQL, Neo4j<br>
**Infrastructure** — Linux, Git, Jenkins, Docker, Nginx, Flask

Contact
======

<!-- The address is base64-encoded so no form of it appears in the page source
     for spam harvesters to scrape. JS rebuilds it as a normal clickable mailto
     link for human visitors. The <noscript> fallback points at LinkedIn rather
     than spelling the address out, so the source stays completely clean. -->
<div id="contact-email"><noscript>Reach me via <a href="https://www.linkedin.com/in/klim-zaporojets-9102b0a">LinkedIn</a>.</noscript></div>
<script>
  (function () {
    var addr = atob('a2xpbXphcG9yb2pldHNAZ21haWwuY29t');
    var link = document.createElement('a');
    link.href = 'mailto:' + addr;
    link.textContent = addr;
    document.getElementById('contact-email').appendChild(link);
  })();
</script>
