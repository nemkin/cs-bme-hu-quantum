---
layout: post
author: nemkin
title: 'Függvény- és gráftulajdonságok lokális tesztelése'
summary: 'Szerző: Szabó Dániel'
date: 2021-05-21 15:37:00 +0100
categories: [MSc thesis]
keywords: MSc thesis, quantum, quantum algorithms, quantum computing
tags:
 - msc-thesis-2021
math: false
hidden: true
---

| **Szerző** | Szabó Dániel |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | Diplomaterv |
| **Dátum** | 2021. május 21. |
| **Nyelv** | magyar |
| **Referencia** | [https://diplomaterv.vik.bme.hu/hu/Theses/Fuggveny-es-graftulajdonsagok-lokalis](https://diplomaterv.vik.bme.hu/hu/Theses/Fuggveny-es-graftulajdonsagok-lokalis) |

<a
  href="https://quszit.github.io/thesises/daniel-szabo-2021-05-21-msc-thesis-fuggveny-es-graftulajdonsagok-lokalis-tesztelese.pdf"
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

A PCP-elmélet (Probabilistically Checkable Proofs) alapkérdése, hogy ha adott egy állítás és egy bizonyíték, ami elvileg tanúsítja az állítás igazságát, akkor a bizonyíték végigolvasása nélkül, csak néhány helyen beletekintve, nagy valószínűséggel meg tudunk-e győződni arról, hogy valóban az állítást igazolja.

Ennek fontos része a lokális tesztelés, avagy tulajdonságtesztelés. Ez alatt azt érjük, hogy egy objektum egy tulajdonságát vizsgálva nem végzünk kimerítő ellenőrzést, hanem megelégszünk azzal, hogy az objektumnak csak egy kis részét figyelve nagy valószínűséggel helyes eredményt kapunk, jóval hatékonyabban.

Függvények vizsgálatakor például nagyon hasznos tud lenni, ha tudjuk a függvényről, hogy rendelkezik egy tulajdonsággal, például lineáris. Hasonló a helyzet gráfoknál is. Manapság rengeteg nagy hálózat vesz körül bennünket, és ezek elemzésekor fontos megtudnunk, hogy a gráf rendelkezik-e valamely tulajdonsággal. A hálózatok kiterjedt mérete miatt a kimerítő ellenőrzés sokszor nem járható út, ezért érdemes lokális tesztelést végezni.

A dolgozatban több ilyen függvény-, illetve gráftulajdonsággal kapcsolatos korábbi elméleti eredményt is bemutatunk. A függvények linearitásának tesztelését és annak elemzését részletesen ismertetjük, ezenkívül az alacsonyfokúság, valamint az ún. diktatúra és junta tulajdonságok ellenőrzésére is mutatunk algoritmust. Gráfok esetén a párosságot és azt a tulajdonságot vizsgáljuk részletesen, hogy a gráf nem tartalmaz feszített részgráfként négy hosszú kört. Ez utóbbi esetben a bizonyítás gondos végigkövetésével és pontosabb becslésekkel sikerült az eredmény konstansaiban némi javítást elérni.

A kvantuminformatika napjainkban tapasztalható jelentős fejlődése, valamint elméleti érdekessége miatt a dolgozatban a vizsgált terület néhány kvantuminformatikai vonatkozását is bemutatjuk. Konkrétan a junták tesztelésének elemzését ismertetjük, valamint a PCP-elméletnél is felmerülő interaktív bizonyító rendszerekhez kapcsolódó CHSH-játékot.

Fontos kérdés továbbá, hogy az elméleti korlátokhoz hogyan viszonyulnak a gyakorlatban tapasztalt eredmények. Ezért a függvények linearitásának és a gráfok párosságának teszteléséhez kapcsolódó algoritmusok implementálása és futtatása során kapott tapasztalati eredményeket bemutatjuk, és összevetjük az elméleti korlátokkal.
