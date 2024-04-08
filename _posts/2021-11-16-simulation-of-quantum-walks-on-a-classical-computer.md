---
layout: post
author: nemkin
title: 'Simulation of quantum walks on a classical computer'
summary: 'Author: Viktória Nemkin'
date: 2021-11-16 08:00:00 +0100
categories: [TDK]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - tdk-2021
math: false
hidden: true
---

| **Author** | Viktória Nemkin |
| :- | :- |
| **Consultant** | Katalin Friedl |
| **Type** | TDK (2nd prize) |
| **Date** | 2021. November 16. |
| **Language** | English |
| **Reference** | [https://tdk.bme.hu/VIK/modell1/Kvantumsetak-szimulacioja-klasszikus](https://tdk.bme.hu/VIK/modell1/Kvantumsetak-szimulacioja-klasszikus) |

<a
  href="https://quszit.github.io/thesises/viktoria-nemkin-2021-11-16-tdk-simulation-of-quantum-walks-on-a-classical-computer.pdf"
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

In recent years, there has been an increasing focus on quantum informatics. Influential global companies such as IBM, Google, Microsoft, and Amazon have invested significant amounts into studying and developing hardware and software for this sector, while the European Union and Hungary have launched several programs to accelerate quantum research.

Current technology is yet to produce a significant number of qubits (quantum bits) in a quantum processor, but many believe the amount will increase over the years. The first practical quantum algorithms to be run on these processors are likely to be the ones that use qubits sparingly. Quantum walking, the generalized version of classical random walking, is exactly this kind of algorithm. The number of qubits required to run a quantum walk on a graph is logarithmic in the number of vertices, making it a promising technique for the near future. Furthermore, Grover's search algorithm (a basis for many quantum algorithms) can be viewed as a special case of quantum walks, which illustrates the potential power of this method.

In my dissertation, I present the mathematical framework for quantum walks, detailing the points critical for implementation, which are given less emphasis in the literature. I describe the architecture and capabilities of the simulator program I have written and the conclusions of the simulations I have run.

I developed the software using Python 3, based on the Strategy design pattern. It supports graphs commonly found in the literature while also providing a method for combining them, facilitating experimentation on several kinds of regular graphs. This composition is also the foundation of the quantum walk. It can simulate classical and quantum walks on the same graphs and produce a report file detailing the results. In the quantum case, the characteristics of the walk are also dependent on the type of coin used to generate the probabilities, which can be defined in several ways. The program includes the Hadamard, Grover, and Fourier coins and can easily be extended with others.

Running several simulations, I compared the behavior of classical and quantum walks and demonstrated the quantum characteristics expected from the theoretical literature, the ballistic nature of the Hadamard walk, and the cyclic property of quantum walks.
