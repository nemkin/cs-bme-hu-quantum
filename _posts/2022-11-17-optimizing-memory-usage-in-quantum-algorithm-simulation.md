---
layout: post
author: nemkin
title: 'Optimizing memory usage in quantum algorithm simulation'
summary: 'Author: Viktória Nemkin'
date: 2022-11-17 08:00:00 +0100
categories: [TDK]
keywords: tdk, quantum, quantum algorithms, quantum computing
tags:
 - tdk-2022
math: false
hidden: true
---

| **Author** | Viktória Nemkin |
| :- | :- |
| **Consultant** | Katalin Friedl |
| **Type** | TDK (1st place) |
| **Date** | 2022. November 17. |
| **Language** | English |
| **Reference** | [https://tdk.bme.hu/VIK/sw9/Memoriafelhasznalas-optimalizalasa](https://tdk.bme.hu/VIK/sw9/Memoriafelhasznalas-optimalizalasa) |

<a
  href="https://quszit.github.io/thesises/viktoria-nemkin-2022-11-17-tdk-optimizing-memory-usage-in-quantum-algorithm-simulation.pdf"
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

The quantum algorithm execution frameworks currently available on the market (IBM Qiskit, Google Cirq) implement their computations using unitary matrices of exponential size in the number of qubits. Consequently, they require large amounts of memory, even for small inputs. Although existing frameworks use some optimization methods, these often cannot provide improvements of an order of magnitude (e.g. sparse matrix storage mode) or are only applicable in special cases (Clifford gates). In practice, in contrast to a large company, the average user cannot experiment within reasonable limits, for many algorithms, even with relatively small inputs, as this would incur outstanding hardware costs.

Algorithms that save memory in exchange for increased runtime can reduce these hardware expenses. For example, any submatrix of the unitary matrix can be computed on-the-fly during runtime, or the equivalent conventional algorithm can replace the unitary matrix operation. Although the currently available frameworks are open-source, they store the unitary matrices in memory as an integral part of their architecture, making it impossible to incorporate these memory optimization techniques.

In my paper, I focus on developing these memory optimization methodologies and implementing them in a general-purpose quantum algorithm simulation framework. I present the classical algorithm and architecture design steps that form the basis of the system and demonstrate how this system can be used in quantum algorithm research. The framework is primarily intended to be used in a resource-constrained environment to enable running tests on a larger number of qubits, thus facilitating theoretical research. Accordingly, I will make the system and its documentation available to everyone in an open-source licensed form.