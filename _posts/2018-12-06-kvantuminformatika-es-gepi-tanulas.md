---
layout: post
author: nemkin
title: 'Kvantuminformatika és gépi tanulás'
summary: 'Szerző: Szabó Dániel'
date: 2018-12-06 17:49:00 +0100
categories: [BSc thesis]
keywords: BSc thesis, quantum, quantum algorithms, quantum computing
tags:
 - bsc-thesis-2018
math: true
hidden: true
---

| **Szerző** | Szabó Dániel |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | Szakdolgozat |
| **Dátum** | 2018. december 06. |
| **Nyelv** | magyar |
| **Referencia** | [https://diplomaterv.vik.bme.hu/hu/Theses/Kvantuminformatika-es-gepi-tanulas](https://diplomaterv.vik.bme.hu/hu/Theses/Kvantuminformatika-es-gepi-tanulas) |

<a
  href="https://quszit.github.io/thesises/daniel-szabo-2018-12-06-bsc-thesis-kvantuminformatika-es-gepi-tanulas.pdf"
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

Napjainkban egyre gyakrabban hallani híreket a kvantuminformatika világából, például új kvantumszámítógépekről vagy kvantumkommunikációs áttörésekről. Ezekkel összefüggésben egyre fontosabb szerep juthat a közeljövőben a kvantumalgoritmusoknak. Szintén nagyon népszerű terület a gépi tanulás, amit rengeteg különböző célra használnak a sakkozógéptől az önvezető autóig. A két terület ötvözése rendkívül ígéretesnek tűnik.

A kvantuminformatika a kvantummechanikából ismert jelenségeken alapul, amely szerint a mikrorészecskék mozgása valószínűségi módon írható le. Ilyen részecskével valósítható meg egy kvantumbit: egyszerre van a két, jól megkülönböztethető klasszikus állapot (0 és 1) szuperpozíciójában, az egyikben $p$, a másikban $1-p$ valószínűséggel. Ilyen módon egy $n$ kvantumbites rendszer egyszerre $2^n$ állapotban van, ennek leírására (azaz az egyes állapotok valószínűségének eltárolására) klasszikus esetben $2^n$-nel arányos darabszámú bit szükséges. Ettől lehet hatékonyabb bizonyos problémák megoldása kvantumszámítógéppel, mint klasszikusan, pl. prímtényezőkre bontás, rendezetlen halmazban keresés stb.

A kanadai D-Wave Systems vállalat volt az első a világon, amely kvantumszámítógépet adott el, a legutóbbi számítógépük 2048 kvantumbites. Bár megoszlanak a vélemények arról, hogy valóban kvantumos elven működő számítógépekről van-e szó, ettől függetlenül érdemes foglalkozni azzal a számítási modellel, amely a gépek mögött van. A modell alapja a Kiméra gráf (Chimera graph), ebbe kell beágyazni a problémákat.

Gépi tanulást (és általában heurisztikus megoldásokat) akkor érdemes használni, ha nem ismert olyan egzakt algoritmus, ami hatékonyan megold egy problémát. Lényege, hogy a gép, ami megoldja a feladatot, "tanul" a korábban már látott esetekből. Ezt ellenőrzött tanulás esetén úgy érjük el, hogy ismert eredménnyel rendelkező tanító adatokat adunk bemenetként, amelyekből a gép egy modellt tud előállítani. Így ha olyan új bemeneteket kap, amelyeknek már nem ismert az eredménye, akkor erre a modell alapján becslést tud mondani.

A dolgozat fő célja egyrészt a különböző kvantuminformatikai számítási modellek ismertetése és néhány NP-teljes gráfelméleti probléma D-Wave kvantumszámítógépen történő megoldásának bemutatása. Másrészt felvázoljuk bizonyos gépi tanulási módszerek kvantum változatát, és egy új bináris osztályozó algoritmust is terveztünk, amely megalkotásánál szempont volt a kvantumos megvalósíthatóság is. A téma jelentősége abban áll, hogy a bemutatott problémák hatékonyabb megoldása válhat lehetővé egy jövőbeli kvantumszámítógépen.
