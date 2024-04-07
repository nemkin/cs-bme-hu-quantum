---
layout: post
author: nemkin
title: 'Kvantumbitek gazdag dinamikája'
summary: 'Előadó: Kiss Tamás'
date: 2023-09-25 12:15:00 +0200
categories: [Seminar]
keywords: seminar, quantum, quantum algorithms, quantum computing
tags:
 - seminar-2023-fall
math: false
---

2023\. őszén folytatódik a **Kvantumalgoritmusok** szeminárium, melyen a kvantuminformatika különböző területeivel kapcsolatos előadásokat hallgathattok meglévő eredményekről és folyamatban lévő kutatásokról diákok és kutatók előadásában.

Az aktuális alkalmakról a [weboldalunkon]({{ site.baseurl }}/seminar) és a [levelezőlistánkon]({{ site.baseurl }}/mailing-list) értesülhettek. Az alkalmak nem feltétlenül épülnek majd egymásra, tehát annak is érdemes lehet feliratkozni, aki csak 1-2 előadásra tudna benézni.

Az első alkalom témája:

## Téma

- **Cím**: Kvantumbitek gazdag dinamikája
- **Előadó**: [Kiss Tamás](http://bird.szfki.kfki.hu/~tkiss/index_hu.html)
- **Diasor**: [Link](https://quszit.github.io/seminar/tamas-kiss-2023-09-18-seminar-rich-dynamics-of-qubits.pdf)

## Koordináták

- **Időpont**: 2023. szeptember 25., hétfő 12:15 - 13:15
- **Helyszín**: IB134-es terem (BME I épület, 1. emelet, SZIT tanszéken belül)

## Absztrakt

Egy kétállapotú, nemrelativisztikus kvantumrendszer (vagyis egy
kvantumbit) az egyik legegyszerűbb nemtriviális fizikai objektum.
Időfejlődését zárt rendszer esetén unitér operátor, nyílt
kvantumcsatornákban pedig egy CPTP (teljesen pozitív, nyomőrző)
leképezés írja le. Ezek a leképezések lineárisak a rendszer állapotára
nézve. Ilyen esetben a kezdő kvantumállapotot kissé megváltoztatva a
végállapot sem változik nagyon. A kvantuminformatikai protokollok
között azonban ennél általánosabb viselkedés is megjelenhet. Tekintsük
azonosan preparált rendszerek sokaságát, amely sokaságot egy
kvantumállapottal írhatunk le. Ekkor megtehetjük azt, hogy páronként
vesszük a rendszereket, végzünk rajtuk valamilyen műveletet, majd a
pár egyik tagját megmérjük. Végül a mérés eredményétől függően
megtartjuk vagy eldobjuk a pár másik részét (posztszelekció). Ez a
gondolat húzódik a kvantummechanikai összefonódás (entanglement)
növelését célzó eljárás, a kvantumállapot-disztilláció mögött is,
ilyenkor a sokaságot két- vagy többrészű rendszerek alkotják.

A fenti eljárás iterációja már a legegyszerűbb esetben is nemlineáris,
determinisztikus kvantumdinamikához vezethet. A kialakuló komplex
káosz eltér mind a klasszikus mechanikában ismert kaotikus
dinamikától, mind a szokásos kvantumkáosztól, ahol általában unitér
időfejlődést tételeznek fel. A kialakuló dinamika ideális esetben
(ahol nincs hiba vagy zaj sem a preparált kezdőállapotokban sem az
eljárás többi lépésében) egy n-edfokú komplex racionális törtfüggvény
iterációjával írható le. Ezeket a dinamikai rendszereket mintegy 100
éve tanulmányozzák matematikusok, sok eredmény ezek közül jól
használható az említett fizikai rendszerek viselkedésének megértésére.
Például megvalósítható az ún. Lattès map vagy kirajzolódhat egy szép,
fraktáldimenziós Julia-halmaz (vagy akár egy Mandelbrot halmaz is) a
kvantumbitet reprezentáló Bloch-gömb felszínén.

A fizikai megvalósítás során nem tekinthetünk el a zajtól, hibáktól. A
legegyszerűbben figyelembe vehető zaj az, ami a kezdőállapotban van
jelen. Ekkor szemléletesen a Bloch-gömb belseje reprezentálja a kevert
állapotokat, a gömb középpontja felé haladva nő a zaj. Bemutatok egy
konkrét esetet, ahol elsősorban numerikus vizsgálatokon alapuló
eredményeink azt mutatják, hogy a felszíni fraktál nem tűnik el a zaj
hatására. A felszínhez közeli gömbhéjakon a fraktál numerikusan
becsült dimenziója állandó marad, majd egy jól meghatározható pont
után (ami a gömb belsejében lévő fixpont) hirtelen eltűnik. Hasonló
folyamat játszódik le ha ezt a folyamatot n-ed rendűre általánosítjuk.
Más zajtípusokról is említést teszek majd. Nyitott kérdés, hogy mi az
a mélyebb matematikai struktúra ami összeköti a gömb felszínén és a
gömb belsejében lejátszódó folyamatot? Egy másik érdekes
általánosítás, ha kvantumbitek helyett magasabb dimenziós rendszereket
veszünk, ezek lehetnek qubit-párok, qubit n-esek, vagy más rendszerek
is, ahol persze szintén megjelenhet a zaj.
