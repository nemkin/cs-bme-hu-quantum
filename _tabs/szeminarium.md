---
# the default layout is 'page'
title: Szeminárium
permalink: szeminarium/
icon: fa-solid fa-chalkboard-user
order: 1
---

## Elhangzott előadások

### 2023\. ősz

### 2023\. tavasz

- 2023-05-26: [Kvantumalgoritmusok az izogénia-alapú kriptográfiában]({{ site.baseurl }}/posts/2023-05-23-kvantumalgoritmusok-az-izogenia-alapu-kriptografiaban)
- 2023-05-19: [Kvantumos bonyolultsági osztályok]({{ site.baseurl }}/posts/2023-05-15-kvantumos-bonyolultsagi-osztalyok)
- 2023-05-12: [Quantum Thermal State Preparation]({{ site.baseurl }}/posts/2023-05-09-quantum-thermal-state-preparation)
- 2023-04-28: [Összefonódás és ami mögötte van]({{ site.baseurl }}/posts/2023-04-24-osszefonodas-es-ami-mogotte-van)
- 2023-04-21: [Kvantumos jelfeldolgozás és szingulárisérték transzformáció]({{ site.baseurl }}/posts/2023-04-16-kvantumos-jelfeldolgozas-es-szingularisertek-transzformacio)
- 2023-04-14: [A kvantumos algoritmusok egyesített elmélete: kvantumos szingulárisérték-transzformáció]({{ site.baseurl }}/posts/2023-04-11-kvantumos-szingularisertek-transzformacio)
- 2023-03-31: [Mintavételezés kvantumos bolyongásokkal]({{ site.baseurl }}/posts/2023-03-28-mintavetelezes-kvantumos-bolyongasokkal)
- 2023-03-17: [Bevezetés a Szegedy-féle kvantumbolyongásokba]({{ site.baseurl }}/posts/2023-03-13-bevezetes-a-szegedy-fele-kvantumbolyongasokba)



### 2023\. május 12\.

Ezen a héten pénteken a tanszéken nem tartunk szemináriumot, helyette ugyanebben az időpontban a BME TTK Elméleti Fizika Tanszéken lehet meghallgatni Gilyén András előadását (angol nyelven):

**Cím**: Quantum Thermal State Preparation  
**Előadó**: [Gilyén András](http://gilyen.hu/)

**Koordináták**:

- **Időpont**: 2023. május 12. péntek, 10:15 - 11:00 + kérdések  
- **Helyszín**: 1111 Budapest, Budafoki út 8., F III épület, magasföldszint 1.

**Absztrakt**: Preparing ground states and thermal states is of key importance to simulating quantum systems on a quantum computer. Despite the hope for practical quantum advantage in quantum simulation, popular approaches like variational circuits or adiabatic algorithms appear to face serious difficulties. Monte-Carlo style quantum Gibbs samplers have emerged as an alternative, but prior proposals have been unsatisfactory due to technical obstacles related to energy-time uncertainty. We introduce simple continuous-time quantum Gibbs samplers that overcome these obstacles by efficiently simulating Nature-inspired quantum Master Equations (Liouvillians) utilizing the operator Fourier transform. In addition, we construct the first provably accurate and efficient algorithm for preparing certain purified Gibbs states (called thermal field double states in high-energy physics) of rapidly thermalizing systems; this algorithm also benefits from a Szegedy-type quadratic improvement with respect to the mixing time. Our algorithms' cost has a favorable dependence on temperature, accuracy, and the mixing time (or spectral gap) of the relevant Liouvillians. We contribute to the theory of thermalization by developing a general analytic framework that handles energy uncertainty through non-asymptotic secular approximation and approximate detailed balance, establishing our approximation guarantees and, as a byproduct yielding the first rigorous proof of finite-time thermalization for physically derived Liouvillians. Given the success of the classical Metropolis algorithm and the ubiquity of thermodynamics, we anticipate that quantum Gibbs sampling will become an indispensable tool in quantum computing.

Joint work with Chi-Fang (Anthony) Chen, Michael J. Kastoryano, Fernando G.S.L. Brandão: [https://arxiv.org/abs/2303.18224](https://arxiv.org/abs/2303.18224)

**Szemináriumsorozat linkje**: [https://dtp.physics.bme.hu/szeminarium](https://dtp.physics.bme.hu/szeminarium)

-----

### 2023\. április 28\.

**Cím**: Összefonódás és ami mögötte van  
**Előadó**: Galambos Máté

**Absztrakt**: (Előzetes terv, még változhat!)

- Bell-teszt
  - CHSH egyenlőtlenség maximuma klasszikus esetben
  - CHSH maximum kvantumos esetben, Tsirelson korlát
  - Elméleti CHSH maximum, szuprakvantum fizika
- Ekert protokoll
  - E91 protokoll, mint a Bell teszt alkalmazása
  - Kulcsszétosztás
- Pauli teleportáció
  - Pauli teleportáció posztszelekcióval
  - Algoritmikus következmények, Pauli teleportáció, mint kezdetleges előszámítás
- A teleportáció új fajtája, a kapu-alapú teleportáció
  - A kapu-alapú teleportáció, mint kvantumos előszámítás
  - Korlátok, fidelitás, aszimptotikus természet
  - Instant kvantumszámítás
- Kvantumkriptográfia a kulcsszétosztáson túl\*
  - Helyhitelesítés (távoli kommunikációs partner helyének tesztelése)
  - Teleportációs támadás a helyhitelesítés ellen
- Szuprakvantum fizika és következményei\*\*
  - Popescu-Rohrlich dobozok (PR box)
  - Véletlen hozzáférésű kódolás (RAC box)
  - Kommunikációs komplexitás összeomlása klasszikusan és kvantumosan
  - Lehetséges ellenérvek

\*Ha marad még rá idő.  
\*\*Érdekes lenne beszélni róla, de még nekem is jobban utána kellene néznem. Esetleg említés szintjén beleférhet.

-----

### 2023\. április 21\.

**Cím**: Kvantumos jelfeldolgozás és szingulárisérték transzformáció  
**Előadó**: [Gilyén András](http://gilyen.hu/)

**Absztrakt**: A múlt héten tárgyalt lineáris algebrai algoritmusos keretrendszer
fő állításainak egy egyszerű elemi bizonyítását fogom elmondani.

-----

### 2023\. április 14\.

**Cím**: A kvantumos algoritmusok egyesített elmélete: kvantumos szingulárisérték-transzformáció  
**Előadó**: [Gilyén András](http://gilyen.hu/)

**Absztrakt**: A kvantumos algoritmusok lineáris algebrai megközelítése az elmúlt
években elvezetett egy egységes algoritmikus keretrendszer kifejlesztéséhez. A
kvantumos szingulárisérték-transzformáció a kvantumos algoritmusok egy olyan
absztrakciója ami egyben közös általánosítása a Grover keresésnek, az amplitúdó
amplifikációnak, a Szegedy-féle kvantumos bolyongásoknak, a Hamilton-szimulációnak
és a kvantumos lineáris egyenlet megoldó (HHL) algoritmusoknak.

**Diasor**: [Link](https://github.com/quszit/szeminarium/raw/main/2023_04_14_kvantumos_szingularisertek_transzformacio/andras_gilyen_-_quantum_singular_value_transformation.pdf)

-----

### 2023\. március 31\.

**Cím**: Mintavételezés kvantumos bolyongásokkal  
**Előadó**: Pituk Sára

**Absztrakt**: A kvantumos bolyongások a klasszikus véletlen bolyongások kvantumos
megfelelői. Többek között a mintavételezésben is használnak véletlen bolyongáson
alapuló algoritmusokat. Az előadásban bemutatok egy eredményt, ami szerint kvantumos
bolyongással kvadratikusan gyorsabban lehetséges a mintavételezés egy Markov-lánc
állapotai közül tetszőleges céleloszlás esetén, mint klasszikus véletlen bolyongást
használva, feltéve, hogy a kezdeti eloszlás a stacionárius eloszlás.

**Kapcsolódó irodalom**: Dante Bencivenga: Sampling Using Controlled Quantum Walks ([Link](https://prism.ucalgary.ca/server/api/core/bitstreams/6c838e8f-958e-474c-9160-cda2d73c1623/content))

-----

