# Algorithms

An introduction to the concept of algorithms and the three main ways of representing them: **narrative description**, **flowchart**, and **pseudocode (portugol)**.

## Table of Contents

- [What Is an Algorithm?](#what-is-an-algorithm)
- [Examples](#examples)
- [How to Construct an Algorithm](#how-to-construct-an-algorithm)
- [Types of Algorithms](#types-of-algorithms)
  - [1. Narrative Description](#1-narrative-description)
  - [2. Flowchart](#2-flowchart)
  - [3. Pseudocode (Portugol)](#3-pseudocode-portugol)
- [Comparison](#comparison)
- [References](#references)

---

## What Is an Algorithm?

> An algorithm is a sequence of steps aimed at achieving a well-defined objective.
> — FORBELLONE (1999)

> An algorithm is the description of a sequence of steps that must be followed to perform a task.
> — ASCENCIO (1999)

---

## Examples

### Example 1: Add three numbers

```text
Step 1: Receive three numbers
Step 2: Add the three numbers received
Step 3: Display the result of the addition
```

### Example 2: Change a light bulb

```text
Step 1:  Get a new light bulb
Step 2:  Get a ladder
Step 3:  Position the ladder under the burnt-out light bulb
Step 4:  Climb the ladder with the new light bulb in hand
Step 5:  Remove the burnt-out light bulb
Step 6:  Install the new light bulb
Step 7:  Climb down from the ladder
Step 8:  Test the light switch
Step 9:  Put away the ladder
Step 10: Properly dispose of the old light bulb
```

---

## How to Construct an Algorithm

To construct any type of algorithm, follow these steps:

1. **Read** the problem statement carefully, highlighting the most important points.
2. **Define the input data**: which data are provided.
3. **Define the processing**: which calculations will be performed and which constraints apply to them. The processing transforms the input data into output data.
4. **Define the output data**: which data will be generated after the processing.
5. **Construct the algorithm** using one of the types described below.
6. **Test the algorithm** by running simulations.

---

## Types of Algorithms

The three main types of algorithms are:

| Type | Representation |
|------|----------------|
| Narrative description | Natural language |
| Flowchart | Graphical symbols |
| Pseudocode (portugol) | Structured, rule-based text |

All of the examples below solve the same problem:

> **Problem:** Create an algorithm to display the result of multiplying two numbers.

### 1. Narrative Description

A narrative description analyzes the problem statement and writes out the steps to be followed to solve it, using natural language (for example, Portuguese or English).

| | |
|---|---|
| **Advantage** | No new concepts need to be learned. |
| **Disadvantage** | Natural language allows multiple interpretations, which can make it difficult to transcribe the algorithm into a program. |

**Example**

```text
Step 1: Receive two numbers to be multiplied
Step 2: Multiply the numbers
Step 3: Display the result obtained from the multiplication
```

### 2. Flowchart

A flowchart analyzes the problem statement and outlines the steps to solve it using predefined graphical symbols.

| | |
|---|---|
| **Advantage** | Graphical elements are easier to understand than text. |
| **Disadvantage** | The flowchart symbology must be learned, and the resulting algorithm lacks detail, making it harder to translate into a computer program. |

**Flowchart symbols**

| Symbol | Meaning |
|:------:|---------|
| ![Start/End symbol](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/beginEnd.png) | **Start / End**: indicates the beginning and the end of the algorithm. |
| ![Flow arrow symbol](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/arrow.png) | **Flow direction**: indicates the direction of the data flow. |
| ![Process symbol](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/calculus.png) | **Process**: indicates calculations and the assignment of values. |
| ![Input symbol](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/input.png) | **Input**: represents data input. |
| ![Output symbol](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/Output.png) | **Output**: represents data output. |
| ![Decision symbol](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/decision.png) | **Decision**: indicates decision-making, showing the possibility of branching paths. |

**Example**

![Flowchart: multiplication of two numbers](FUNDAMENTALSOFPROGRAMMING/Algorithms/images/FlowChart.png)

### 3. Pseudocode (Portugol)

Pseudocode, also known as *portugol*, analyzes the problem statement and, following predefined rules, writes out the steps required to solve it.

| | |
|---|---|
| **Advantage** | Translating the algorithm into any programming language is nearly immediate; you only need to know the reserved words of the target language. |
| **Disadvantage** | The rules of the pseudocode must be learned. |

**Example**

```text
ALGORITHM "MULTIPLICATION"

VAR
    N1, N2, M: NUMERIC

BEGIN
    WRITE("Enter two numbers: ")
    READ(N1, N2)
    M ← N1 × N2
    WRITE(M)
END_ALGORITHM
```

---

## Comparison

| Criterion | Narrative Description | Flowchart | Pseudocode |
|-----------|:---------------------:|:---------:|:----------:|
| Easy to learn | ✅ | ⚠️ Requires learning symbols | ⚠️ Requires learning rules |
| Free of ambiguity | ❌ | ✅ | ✅ |
| Level of detail | Medium | Low | High |
| Ease of translation to code | Low | Low | High |

---

## References

- ASCENCIO, A. F. G. (1999).
- FORBELLONE, A. L. V. (1999).
- Lecture slides by Prof. Kamila Gomes (Fundamentals of Programming)