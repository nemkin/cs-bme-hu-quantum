---
layout: post
author: nemkin
title: 'Application of Quantum Computing in Bioinformatics'
summary: 'Author: Viktória Nemkin'
date: 2022-12-18 21:47:00 +0100
categories: [MSc thesis]
keywords: MSc thesis, quantum, quantum algorithms, quantum computing
tags:
 - msc-thesis-2022
math: false
hidden: true
---

| **Author** | Viktória Nemkin |
| :- | :- |
| **Consultant** | Katalin Friedl |
| **Type** | MSc thesis |
| **Date** | 2021. November 17. |
| **Language** | English |
| **Reference** | [https://diplomaterv.vik.bme.hu/en/Theses/Kvantumalgoritmusok-bioinformatikai-alkalmazasa](https://diplomaterv.vik.bme.hu/en/Theses/Kvantumalgoritmusok-bioinformatikai-alkalmazasa) |

<a
  href="https://quszit.github.io/thesises/viktoria-nemkin-2022-12-18-msc-thesis-application-of-quantum-computing-in-bioinformatics.pdf"
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
    >Open</a>

## Abstract

Bioinformatics is an interdisciplinary field between computer science and biology. Its main goal is to answer biological questions by transforming them into computational problems and providing efficient algorithmic solutions. Researching bioinformatics significantly impacts our everyday lives, as discoveries in this field could help us solve many of today's major global problems. Utilizing them, we could create novel medical treatments, advance our understanding of genetic diseases, develop resistant crops to tackle a global food crisis or invent new technologies to decrease environmental pollution.

Unfortunately, many practical problems in bioinformatics turn out to be computationally hard ones on classical hardware. Despite tremendous research effort to date, no sufficiently fast, deterministic solutions have been found to these problems.

Quantum informatics is a compelling field for algorithmic research since quantum computers work fundamentally differently from classical ones, which means that the already established classical problem complexities are different in the quantum world. One of the most famous examples is Shor's prime factorization algorithm, which could break modern-day encryption quickly on a large-scale quantum computer.

Due to this, governmental entities and global corporations are paying increased attention to quantum computing, and they are investing in quantum hardware and software development. For example, the European Commission started Quantum Flagship in 2018, a large-scale 10-year initiative with €1 billion in funding for quantum research, currently running under the Horizon Europe initiative.

While quantum computing is still in its early stages and the limits of quantum hardware are yet unknown, the availability of a different computational model has already made new theoretical discoveries possible in both the classical and the quantum worlds.

In my dissertation, I present a general overview of some computational problems in bioinformatics, particularly protein folding, and explain its connection to Grover's search algorithm and quantum walks. Then, I introduce the toolkit of quantum computation, specifically quantum walks and Grover's search algorithm. I present the mathematical framework for quantum walks, formulated in a way which is less common in literature, from which implementation follows naturally, and demonstrate their characteristics using the visualization software I have written. I describe the current practical problems with experimenting on quantum algorithms, specifically quantum protein folding, then design and implement a framework which can reduce some of these issues.
