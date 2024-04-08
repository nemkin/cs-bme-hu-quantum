---
layout: post
author: nemkin
title: 'Módszerek közel optimális vágások keresésére'
summary: 'Szerző: Zalavári Márton'
date: 2021-12-18 19:00:00 +0100
categories: [MSc thesis]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - msc-thesis-2021
math: false
hidden: true
---

| **Szerző** | Zalavári Márton |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | Diplomaterv |
| **Dátum** | 2021. december 18. |
| **Nyelv** | magyar |
| **Referencia** | [https://diplomaterv.vik.bme.hu/hu/Theses/Modszerek-kozel-optimalis-vagasok-keresesere](https://diplomaterv.vik.bme.hu/hu/Theses/Modszerek-kozel-optimalis-vagasok-keresesere) |

<a
  href="https://quszit.github.io/thesises/marton-zalavari-2021-12-18-msc-thesis-modszerek-kozel-optimalis-vagasok-keresesere.pdf"
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

A kvadratikus programozás a lineáris programozásnál egy általánosabb technika, hiszen megengedi négyzetes tagok jelenlétét a célfüggvényben. Ezzel az alkalmazások körét jóval kibővíti, ugyanakkor az általános feladat megoldása sokkal nehezebbé válik.

Ez a fajta optimalizációs technika többek között azért is érdekes és hasznos, mert ha a változók binárisak és nincsenek további korlátjaink, akkor a probléma megoldásához felhasználható egy kvantumállapotokat használó számítógép, ezzel remélhetőleg jelentősen csökkentve az optimalizáláshoz szükséges időt. A szakirodalom egyszerűen csak QUBO (Quadratic Unconstrained Binary Optimization) néven hivatkozik erre a fajta felírásra.

Gráfokon vágások keresése a (számítógép)hálózatok megjelenése óta egy sokat kutatott tématerület. Maximális vágást találni közismerten NP-nehéz probléma, ugyanakkor gyakorlati szempontból fontos, hiszen például a tipikus klaszterezési problémák megfogalmazhatók így, ha az adatot gráfként tudjuk reprezentálni.

A minimális és maximális vágással kapcsolatos problémákra a lineáris programozás mellett többféle QUBO felírást is adok, melyeket elméleti és gyakorlati szempontból is összehasonlítok. Az elkészített formulákat több szempontból elemzem, például a legegyszerűbb ilyen összehasonlítási metrika a felhasznált változók száma.

A maximális K-vágás egyik QUBO megfogalmazása kapcsán logikai függvények kvadratikus optimalizálását is megmutatom, melyek egyszerűbb esetben bár ismertek, nincs részletes vagy egységes dokumentációjuk, illetve összetettebb esetben egyáltalán nem találtam korábbi szakirodalmat. Ilyen összetett logikai kifejezésekre, különös tekintettel a kizáró vagy (XOR) műveletére saját bizonyításokat is közlök.

A QUBO-k optimalizálásához a D-Wave Ocean nevű programcsomagját használtam fel, mely több lehetőséget kínál a formulák megoldására. A klasszikus megoldók mellett lehetőség van például valódi, a D-Wave Systems által forgalmazott kvantumszámítógépeket is használni, vagy a klasszikus és kvantum eljárásokat hibrid módon ötvözni.

Összehasonlítom a különböző lehetőségekből adódó módszereket azok eredményessége és hatékonysága alapján.

A kapott eredményeket összevetem más, klasszikus heurisztikus megoldók használatával, és minimális vágás esetében a polinom idejű folyamalgoritmussal is.

A munka jelentős részét tette ki, hogy tapasztalatot gyűjtsek a D-Wave-es programcsomaggal kapcsolatban, hiszen a terület újdonságából kifolyólag az elérhető dokumentációk meglehetősen limitáltnak bizonyultak.
