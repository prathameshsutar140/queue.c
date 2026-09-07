# Linear Queue Implementation in C

This repository contains an array-based implementation of a Linear Queue in C using Turbo C compatible syntax (`conio.h`).

## Features

* **Enqueue:** Adds an integer element to the rear of the queue with overflow checking.
* **Dequeue:** Removes and returns an element from the front of the queue with underflow checking and automatic index resetting.
* **Display:** Traverses and prints all current elements stored in the queue.
* **Menu-Driven Interface:** Interactive loop allowing continuous operations until exit.

## Specifications

* **Storage Type:** Static Array (`MAX = 5`)
* **Pointers Used:** `front` and `rear` track array indices
* **Compiler Requirements:** Turbo C / Borland C / DOSBox C environment (uses `clrscr()` and `conio.h`)

## How to Run

1. Open the `.c` file in Turbo C++ or any DOSBox C environment.
2. Compile and run (`Ctrl + F9`).
3. Select numbers `1` to `4` from the menu to perform queue operations.
