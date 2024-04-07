---
layout: post
author: nemkin
title: 'Kvadratikus optimalizálás kvantum alapú számítógéppel'
summary: 'Szerző: Zalavári Márton'
date: 2021-11-16 08:00:00 +0100
categories: [TDK]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - tdk-2021
math: false
hidden: true
---

| **Szerző** | Zalavári Márton |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | TDK (II. helyezett) |
| **Dátum** | 2021. november 16. |
| **Nyelv** | magyar |
| **Referencia** | [https://tdk.bme.hu/VIK/modell1/Kvadratikus-optimalizalas-kvantum-alapu](https://tdk.bme.hu/VIK/modell1/Kvadratikus-optimalizalas-kvantum-alapu) |

<a
  href="https://quszit.github.io/thesises/marton-zalavari-2021-11-16-tdk-kvadratikus-optimalizalas-kvantum-alapu-szamitogeppel.pdf"
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

A kvadratikus programozás a lineáris programozásnál egy általánosabb technika, hiszen megengedi négyzetes tagok jelenlétét a célfüggvényben és a korlátokban is. Ezzel az alkalmazások körét jóval kibővíti, ugyanakkor az általános feladat megoldása sokkal nehezebbé válik.

Ez a fajta optimalizációs technika többek között azért is érdekes és hasznos, mert ha a változók binárisak és nincsenek további korlátjaink, akkor a probléma megoldásához felhasználható egy kvantumállapotokat használó számítógép, ezzel remélhetőleg jelentősen csökkentve az optimalizáláshoz szükséges időt. A szakirodalom egyszerűen csak QUBO (Quadratic Unconstrained Binary Optimization) néven hivatkozik erre a fajta felírásra.

Gráfban maximális vágást találni közismerten NP-nehéz probléma, ugyanakkor gyakorlati szempontból fontos, hiszen például a tipikus klaszterezési problémák megfogalmazhatók így, ha az adatot gráfként tudjuk reprezentálni.

A maximális vágással kapcsolatos problémákra többféle QUBO felírást is adok, melyeket elméleti és gyakorlati szempontból is összehasonlítóan elemzek. Az elkészített formulákat több szempontból elemzem, például a legegyszerűbb ilyen összehasonlítási metrika a felhasznált változók száma.

A QUBO-k optimalizálásához a D-Wave Ocean nevű programcsomagját használtam fel, mely több lehetőséget kínál a formulák megoldására. A klasszikus megoldók mellett lehetőség van például valódi, a D-Wave Systems által forgalmazott kvantumszámítógépeket is használni, vagy a klasszikus és kvantum eljárásokat hibrid módon ötvözni.

Összehasonlítom a különböző lehetőségekből adódó módszereket azok eredményessége és hatékonysága alapján. Természetesen a kapott eredményeket összevetem más, klasszikus heurisztikus megoldók használatával is.

A munka jelentős részét tette ki számos tapasztalat gyűjtése a D-Wave-es programcsomaggal kapcsolatban, hiszen a terület újdonságából kifolyólag az elérhető dokumentációk meglehetősen limitáltnak bizonyultak.
