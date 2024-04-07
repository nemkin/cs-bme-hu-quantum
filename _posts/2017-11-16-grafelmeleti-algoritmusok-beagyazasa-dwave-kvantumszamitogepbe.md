---
layout: post
author: nemkin
title: 'Gráfelméleti algoritmusok beágyazása D-Wave kvantumszámítógépbe'
summary: 'Szerző: Szabó Dániel'
date: 2017-11-16 08:00:00 +0100
categories: [TDK]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - tdk-2017
math: false
hidden: true
---

| **Szerző** | Szabó Dániel |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | TDK (II. helyezett) |
| **Dátum** | 2017. november 16. |
| **Nyelv** | magyar |
| **Referencia** | [https://tdk.bme.hu/VIK/Szimu/Grafelmeleti-algoritmusok-beagyazasa-DWave](https://tdk.bme.hu/VIK/Szimu/Grafelmeleti-algoritmusok-beagyazasa-DWave) |

<a
  href="https://quszit.github.io/thesises/daniel-szabo-2017-11-16-tdk-grafelmeleti-algoritmusok-beagyazasa-dwave-kvantumszamitogepbe.pdf"
  style="
    background-color: #7D5BA6;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    outline: none;
    color: white;
    font-size: 16px;
    text-decoration: none;
    cursor: pointer;
    transition: background-color 0.3s ease;"
    onmouseover="this.style.backgroundColor='#6D4A94'"
    onmouseout="this.style.backgroundColor='#7D5BA6'"
    onmousedown="this.style.backgroundColor='#5C3A82'"
    onmouseup="this.style.backgroundColor='#7D5BA6'"
    >Megnyitás</a>

## Absztrakt

Napjainkban egyre gyakrabban hallani híreket a kvantuminformatika világából, például új kvantumszámítógépekről vagy kvantumkommunikációs áttörésekről. Ezekkel összefüggésben egyre fontosabb szerep juthat a közeljövőben a kvantumalgoritmusoknak.

A kvantuminformatika a kvantummechanikából ismert jelenségeken alapul, amely szerint a mikrorészecskék mozgása valószínűségi módon írható le. Ilyen részecskével valósítható meg egy kvantumbit: egyszerre van a két, jól megkülönböztethető klasszikus állapot (0 és 1) szuperpozíciójában, az egyikben p, a másikban 1-p valószínűséggel. Ilyen módon egy n kvantumbites rendszer egyszerre 2^n állapotban van, ennek leírására (azaz az egyes állapotok valószínűségének eltárolására) klasszikus esetben 2^n-nel arányos darabszámú bit kell. Ettől lehet hatékonyabb sok probléma megoldása kvantumszámítógéppel, mint klasszikusan: pl. prímtényezőkre bontás, rendezetlen halmazban keresés [1], [2].

A kanadai D-Wave Systems vállalat volt az első a világon, amely kvantumszámítógépet adott el, a legutóbbi számítógépük 2048 kvantumbites [3]. Bár megoszlanak a vélemények arról, hogy valóban kvantumos elven működő számítógépekről van-e szó, ettől függetlenül érdemes foglalkozni azzal a számítási modellel, amely a gépek mögött van. A modell alapja a Kiméra gráf (Chimera graph), amelybe be kell ágyazni a problémákat [4].

A dolgozat célja, hogy segítségül szolgáljon a modell megértéséhez. Ezen kívül elvégeztem néhány NP-teljes gráfelméleti probléma beágyazását (pl. van-e egy gráfban megadott méretű klikk; van-e olyan részgráfja, ami adott méretű teljes páros gráf). Ehhez már megoldott problémák alapötleteit használtam fel [5], amelyeket szintén ismertetek. Mivel nem kevés hétköznapi probléma megfogalmazható gráfelméleti úton (pl. nagy hálózatokban közösségek keresése), remélhetőleg idővel néhány ilyen feladat hatékony megoldásához vezethetnek a leírtak.

Források:

[1] Mika Hirvensalo. Quantum Computing (2. kiadás, 2004). Springer – Verlag Berlin Heidelberg

[2] Nielsen, M. and Chuang, I. L.. Quantum Computing and Quantum Information (2001). Cambridge University Press, Cambridge.

[3] Wikipédia – D-Wave Systems: [https://en.wikipedia.org/wiki/D-Wave_Systems](https://en.wikipedia.org/wiki/D-Wave_Systems) (2017. 09. 20.)

[4] E. D. Dahl. Programming with D-Wave: Map Coloring Problem (2013): [https://www.dwavesys.com/sites/default/files/Map%20Coloring%20WP2.pdf](https://www.dwavesys.com/sites/default/files/Map%20Coloring%20WP2.pdf)

[5] Eleanor G. Rieffel, Davide Venturelli, Bryan O'Gorman, Minh B. Do, Elicia Prystay, and Vadim N. Smelyanskiy. A case study in programming a quantum annealer for hard operational planning problems (2014). arXiv:1407.2887v1: [https://arxiv.org/pdf/1407.2887.pdf](https://arxiv.org/pdf/1407.2887.pdf)

![Chimera graph](/assets/thesises/daniel-szabo-2017-11-16-tdk-grafelmeleti-algoritmusok-beagyazasa-dwave-kvantumszamitogepbe.png)
