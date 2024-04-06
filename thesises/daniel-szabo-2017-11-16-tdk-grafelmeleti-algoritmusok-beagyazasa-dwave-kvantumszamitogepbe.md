---
layout: page
title: Gráfelméleti algoritmusok beágyazása D-Wave kvantumszámítógépbe
---

| **Author** | Dániel Szabó |
| :- | :- |
| **Consultant** | Katalin Friedl |
| **Type** | TDK (2nd prize) |
| **Date** | 2017. November 16. |
| **Language** | Hungarian |

[https://tdk.bme.hu/VIK/Szimu/Grafelmeleti-algoritmusok-beagyazasa-DWave](https://tdk.bme.hu/VIK/Szimu/Grafelmeleti-algoritmusok-beagyazasa-DWave)

<a
  href="https://quszit.github.io/thesises/daniel-szabo-2017-11-16-tdk-grafelmeleti-algoritmusok-beagyazasa-dwave-kvantumszamitogepbe.pdf"
  download
  style="
    padding: 10px 20px;
    background-color: #7D5BA6;
    border: none;
    outline: none;
    border-radius: 5px;
    color: white;
    font-size: 16px;
    cursor: pointer;
    text-decoration: none;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: background-color 0.3s ease;"
    onmouseover="this.style.backgroundColor='#6D4A94'"
    onmouseout="this.style.backgroundColor='#7D5BA6'"
    onfocus="this.style.boxShadow='0 0 0 2px #5C3A82'"
    onblur="this.style.boxShadow='0 4px 8px rgba(0, 0, 0, 0.2)'"
    onmousedown="this.style.backgroundColor='#5C3A82'"
    onmouseup="this.style.backgroundColor='#7D5BA6'"
    >Download</a>

## Abstract

Nowadays quantum computing is getting more and more publicity. For example, we can hear news about new quantum computers or breakthroughs in quantum communication. These may cause quantum algorithms to become more and more important in the not too distant future.

Quantum computing is based on quantum mechanical effects which describes the movement of microparticles probabilistically. A quantum bit can be realized with a microparticle which can be in a superposition of 0and 1 at a time with probability p and 1-p respectively. So, an n-quantum bit system encodes 2^n states at a time, and in a classical computer the number of bits used to store the probabilities for each state is proportional to them. That is why several problems can be solved more efficiently on a quantum computer than on a classical one. E.g. factorization, searching in unordered sets [1] [2].

The Canadian D-Wave Systems was the first company in the world to sell quantum computers. Their latest model is a 2048-quantum bit system [3]. Although, it is controversial that these computers really work by quantum principles, the computational model that they provide is worth to investigate. This model is based on the Chimera graph, in which we should embed our problems [4].

One goal of the work is to help to understand the model. I embedded some NP-complete graph theory problems (e.g. find the maximum clique size in a graph, determine the maximum size of a complete bipartite subgraph). These use some ideas from earlier results [5] that I also present. Plenty of everyday problems can be translated to graph theory problems (e.g. community search in large networks), so there is hope that in time this method will lead to efficient solutions of such problems.

References:

[1] Mika Hirvensalo. Quantum Computing (2nd edition, 2004). Springer – Verlag Berlin Heidelberg

[2] Nielsen, M. and Chuang, I. L.. Quantum Computing and Quantum Information (2001). Cambridge University Press, Cambridge.

[3] Wikipedia – D-Wave Systems: [https://en.wikipedia.org/wiki/D-Wave_Systems](https://en.wikipedia.org/wiki/D-Wave_Systems) (2017. 09. 20.)

[4] E. D. Dahl. Programming with D-Wave: Map Coloring Problem (2013): [](https://www.dwavesys.com/sites/default/files/Map%20Coloring%20WP2.pdf)

[5] Eleanor G. Rieffel, Davide Venturelli, Bryan O'Gorman, Minh B. Do, Elicia Prystay, and Vadim N. Smelyanskiy. A case study in programming a quantum annealer for hard operational planning problems (2014). arXiv:1407.2887v1: [https://arxiv.org/pdf/1407.2887.pdf](https://arxiv.org/pdf/1407.2887.pdf)

![Chimera graph](/assets/thesises/daniel-szabo-2017-11-16-tdk-grafelmeleti-algoritmusok-beagyazasa-dwave-kvantumszamitogepbe.png)
