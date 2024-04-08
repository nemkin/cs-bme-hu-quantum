---
layout: post
author: nemkin
title: 'Kvantumáramkör-szimulációs rendszer gyorsításának vizsgálata'
summary: 'Szerző: Kabódi László'
date: 2014-11-11 08:00:00 +0100
categories: [TDK]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - tdk-2014
math: false
hidden: true
---

| **Szerző** | Kabódi László |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | TDK (Jutalom) |
| **Dátm** | 2014. november 11. |
| **Nyelv** | magyar |
| **Referencia** | [https://tdk.bme.hu/VIK/Szimulacio/Kvantumaramkorszimulacios-rendszer](https://tdk.bme.hu/VIK/Szimulacio/Kvantumaramkorszimulacios-rendszer) |

<a
  href="https://quszit.github.io/thesises/laszlo-kabodi-2014-11-11-tdk-kvantumaramkor-szimulacios-rendszer-gyorsitasanak-vizsgalata.pdf"
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

Az informatika egyik manapság pezsgő témája a kvantumszámítógépek, és a rajtuk futtatható algoritmusok vizsgálata. Ezekkel az algoritmusokkal olyan problémákon remélhetünk négyzetes, vagy akár exponenciális gyorsulást is, mint például a keresés (Grover-féle keresőalgoritmus) vagy az RSA titkosítás alapját adó faktorizáció problémája (Shor algoritmusa).

Azonban működő kvantumszámítógép még csak néhány laborban létezik, és azok kapacitása is csak néhány qubit. Ezért nagyon fontos, hogy az algoritmusokat lehessen klasszikus számítógépen vizsgálni. Viszont a kvantumjelenségek alapvető természete miatt ez nagyon lassan megy, mivel a probléma méretének növelésével a probléma klasszikus reprezentációja exponenciálisan növekszik.

Egy ilyen szimulációs program a QuIDDPro[1], ami egy újfajta megközelítést használ a kvantumáramkörök reprezentálására. Egy kvantumáramkört az általa végrehajtott transzformációk mátrixával lehet reprezentálni. Ezek a mátrixok gyakran valamilyen struktúrával rendelkeznek, amit kihasználva egy bináris döntési fához hasonló rendszer építhető fel. Ezt felhasználva bizonyos mátrixokra a mátrix-szorzás sebessége jócskán növelhető, és a memóriaigénye is csökkenthető.

A dolgozat egyik célja ennek a rendszernek a bemutatása és elemzése. Felvetek néhány ötletet is, melyek a meglevő struktúra még jobb kihasználását tehetik lehetővé. Megvizsgálom, hogy ily módon sikerül-e a hatékonyságban további javulást elérni.

[1] George F. Viamontes, Igor L. Markov and John P. Hayesl, "Improving Gate-Level Simulation of Quantum Circuits"
