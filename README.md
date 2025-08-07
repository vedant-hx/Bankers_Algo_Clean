# Banker's Algorithm Simulator 💻

This project implements the **Banker's Algorithm**, a classic deadlock avoidance algorithm used in operating systems.

## 📚 Overview

The Banker's Algorithm is used to allocate resources to multiple processes in a system without causing a deadlock. It checks for a **safe sequence** before allocating resources.

This project simulates the algorithm using static inputs or user-provided data.

## 🔧 Features

- Accepts number of processes and resources.
- Takes input for Allocation, Maximum Need, and Available matrices.
- Determines if the system is in a **safe state**.
- Prints the **safe sequence** if one exists.

## 📂 File Structure

- `bankers.c` — Main source code implementing the algorithm

## ⚙️ Compilation & Running

To compile:

```bash
gcc bankers.c -o bankers

./bankers


Enter number of processes: 5
Enter number of resources: 3

Enter Allocation matrix:
...

Enter Max matrix:
...

Enter Available resources:
...


Safe sequence is: P1 -> P3 -> P4 -> P0 -> P2
System is in a safe state.



Thank You

