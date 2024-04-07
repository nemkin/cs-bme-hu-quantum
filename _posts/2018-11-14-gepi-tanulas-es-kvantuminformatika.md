---
layout: post
author: nemkin
title: 'Gépi tanulás és kvantuminformatika'
summary: 'Szerző: Szabó Dániel'
date: 2018-11-14 08:00:00 +0100
categories: [TDK]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - tdk-2018
math: false
hidden: true
---

| **Szerző** | Szabó Dániel |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | TDK (III. helyezett) |
| **Dátum** | 2018. november 14. |
| **Nyelv** | magyar |
| **Referencia** | [https://tdk.bme.hu/VIK/Szimu1/Gepi-tanulas-es-kvantuminformatika](https://tdk.bme.hu/VIK/Szimu1/Gepi-tanulas-es-kvantuminformatika) |

<a
  href="https://quszit.github.io/thesises/daniel-szabo-2018-11-14-tdk-gepi-tanulas-es-kvantuminformatika.pdf"
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

Napjainkban egyre gyakrabban hallani híreket a kvantuminformatika világából, például új kvantumszámítógépekről vagy kvantumkommunikációs áttörésekről. Ezekkel összefüggésben egyre fontosabb szerep juthat a közeljövőben a kvantumalgoritmusoknak. Szintén nagyon népszerű terület a gépi tanulás, amit rengeteg különböző célra használnak a sakkozógéptől az önvezető autóig.

A kvantuminformatika a kvantummechanikából ismert jelenségeken alapul, amely szerint a mikrorészecskék mozgása valószínűségi módon írható le. Ilyen részecskével valósítható meg egy kvantumbit: egyszerre van a két, jól megkülönböztethető klasszikus állapot (0 és 1) szuperpozíciójában, az egyikben p, a másikban 1-p valószínűséggel. Ilyen módon egy n kvantumbites rendszer egyszerre 2^n állapotban van, ennek leírására (azaz az egyes állapotok valószínűségének eltárolására) klasszikus esetben 2^n-nel arányos darabszámú bit kell. Ettől lehet hatékonyabb bizonyos problémák megoldása kvantumszámítógéppel, mint klasszikusan, pl. prímtényezőkre bontás, rendezetlen halmazban keresés [1], [2].

Gépi tanulást (és általában heurisztikus megoldásokat) akkor érdemes használni, ha nem ismert olyan egzakt algoritmus, ami hatékonyan megold egy problémát. Lényege, hogy a gép, ami megoldja a feladatot, „tanul” a korábban már látott esetekből. Ezt ellenőrzött tanulás esetén úgy érjük el, hogy ismert eredménnyel rendelkező tanító bemeneteket adunk bemenetként, amelyekből a gép egy modellt tud előállítani. Így ha olyan új bemeneteket kap, amelyeknek már nem ismert az eredménye, akkor erre a modell alapján becslést tud mondani. Elterjedt gépi tanulási módszerek például a neurális hálózatok és a döntési fák. Tipikusan gépi tanulással megoldott feladatok például a képfelismerés és a kéretlen levelek kiszűrése [3].

A dolgozat fő célja bizonyos gépi tanulási módszerek (döntési fák, ensemble módszerek / boosting) kvantum változatának bemutatása. Ez azért fontos, mert a széles körben használt gépi tanuló algoritmusok sok adattal dolgozhatnak, és a kvantuminformatikában rejlő párhuzamosítási képesség nagyban gyorsíthatja ezek futását egy jövőbeli kvantumszámítógépen. Ezenkívül az ismertetett megoldásokból kiindulva egy új bináris osztályozó algoritmus is született, amely megalkotásánál szempont volt a kvantumos megvalósíthatóság is. Ez az algoritmus is bemutatásra kerül a dolgozatban.

Források:

[1] Mika Hirvensalo. Quantum Computing (2. kiadás, 2004). Springer – Verlag Berlin Heidelberg

[2] Nielsen, M. and Chuang, I. L.. Quantum Computing and Quantum Information (2001). Cambridge University Press, Cambridge.

[3] Wikipedia – Machine learning: [https://en.wikipedia.org/wiki/Machine_learning](https://en.wikipedia.org/wiki/Machine_learning) (2018. 09. 28.)
