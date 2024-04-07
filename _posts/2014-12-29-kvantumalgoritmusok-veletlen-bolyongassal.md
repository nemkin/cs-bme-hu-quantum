---
layout: post
author: nemkin
title: 'Kvantumalgoritmusok véletlen bolyongással'
summary: 'Szerző: Kabódi László'
date: 2014-12-29 14:00:00 +0100
categories: [MSc thesis]
keywords: MSc thesis, quantum, quantum algorithms, quantum computing
tags:
 - msc-thesis-2014
math: false
hidden: true
---

| **Szerző** | Kabódi László |
| :- | :- |
| **Konzulens** | Friedl Katalin |
| **Típus** | Diplomaterv |
| **Dátm** | 2014. december 29. |
| **Nyelv** | magyar |
| **Referencia** | [https://diplomaterv.vik.bme.hu/hu/Theses/Kvantumalgoritmusok-veletlen-bolyongassal](https://diplomaterv.vik.bme.hu/hu/Theses/Kvantumalgoritmusok-veletlen-bolyongassal) |

<a
  href="https://quszit.github.io/thesises/laszlo-kabodi-2014-12-29-msc-thesis-kvantumalgoritmusok-veletlen-bolyongassal.pdf"
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

Jól ismert, hogy egyes klasszikus algoritmusok gyorsíthatóak a véletlen felhasználásával. Ennek egyik eltejedt módja a véletlen séta. Mikor a kvantumalgoritmusok kutatása kezdett elterjedni, rögtön adódott, hogy a kvantum világban is megvizsgálják a véletlen séta alkalmazhatóságát. A kutatások eredménye az, hogy lehetséges a kiterjesztés, és a Markov-láncokat felhasználva hatékony keresőalgoritmus készíthető. A klasszikus megközelítéshez képest a kvantum változat négyzetes gyorsulást is hozhat általános esetekre.

A dolgozat a kvantumalgoritmusok alapjainak ismertetésével indul, kiemelve a fontosabb különbségeket a klasszikus és a kvantumos megközelítés között. Továbbá bemutatja a kvantumvilág néhány érdekes tulajdonságát is. Nevezetesen a kvantum teleportálást, amivel kvantumállapotot lehet kvantumcsatorna nélkül közvetíteni, és a nem-klónozhatósági tételt, ami kimondja, hogy kvantumállapotot másolni nem lehet.

A második fejezet a keresést felgyorsító Grover-algoritmust mutatja be. Az eredeti algoritmus ugyan nem használ véletlen bolyongást, de megmutatható, hogy lehet kvantum Markov-lánccal úgy szimulálni, hogy a hatékonysága ne változzon. Azért is érdemes ezzel az algoritmussal foglalkozni, mert bár Grover algoritmusa nem ad exponenciális gyorsulást, mint Shor híres prímtényezőkre bontó eljárása, de a keresést, mint részfeladatot, sok algoritmus használja. Valamint az ebből általánosított amplitúdó amplifikációs eljárás sok későbbi kvantumalgoritmus alapját képzi.

A harmadik fejezet röviden ismerteti a klasszikus véletlen sétát, és ennek kvantum kiterjesztését. Mivel a kvantumalgoritmusok a kvantumvilágban rejlő rejtett párhuzamosságot használják ki, ez a kiterjesztés nem magától adódó. Viszont általános esetben négyzetes gyorsulás érhető el, valamint néhány speciális esetben akár exponenciális is.

A negyedik fejezet a Markov-lánc kvantum kiterjesztését felhasználva Frédéric Magniez, Ashwin Nayak, Jérémie Roland és Miklos Santha által kidolgozott keresőalgoritmust mutat be [1]. Ez az algoritmus egy Markov-láncból készített kvantum séta operátort és egy orákulumot használ. Az iterációk folyamán a megfelelő elemek amplitúdóját növeli, így az algoritmus végén a méréssel nagy valószínűséggel egy keresett elemet kapunk. Bizonyítható, hogy az eljárás ekvivalens a Grover-kereséssel.

Az ötödik fejezet egy, a kvantumáramkörök szimulációjára kitalált adatszerkezetet mutat be [2], amit a QuIDDPro program is felhasznál [3]. Az eredeti cikkben a lépésszám bizonyítása elég elnagyoltan szerepelt, itt egy részletes, általam kidolgozott érvelést ismertetek.

A témában való elmélyedés, és az algoritmus jobb megértése érdekében végigkövettem a korábban ismertetett algoritmus működését egy adott, kis méretű bemenetre. Ezt tartalmazza a hatodik fejezet, amelyben szimuláció futtatásához az előző fejezetben levő QuIDD adatszerkezetet felhasználó QuIDDPro programot használtam. Ehhez nem elegendő a szokásos vázlatos megadása a kvantumalgoritmusban előforduló operátoroknak, ezeket meg kellett alkotnom, pontosan össze kellett állítanom. A 3-SAT problémát választottam szemléltetésre, a feladat ismertetése után az algoritmus lépéseit követem végig egy adott 3-CNF-en.

[1] Magniez, F., Nayak, A., Roland, J., and Santha, M. Search via quantum walk, 2011, arXiv:quant-ph/0608026.

[2] Viamontes, G. F., Markov, I. L., and Hayes, J. P. Improving gate-level simula-tion of quantum circuits, 2003, arXiv:quant-ph/0309060v2.

[3] [http://vlsicad.eecs.umich.edu/Quantum/qp/](http://vlsicad.eecs.umich.edu/Quantum/qp/)
