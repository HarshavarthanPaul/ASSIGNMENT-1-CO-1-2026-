# Grama Jyothi Rural Electricity Co-operative: C Programming Assignment 1

This repository contains the complete source code, implementation analysis, and documentation for **Assignment 1** of the C Programming course. The assignment addresses a real-world billing scenario for the **Grama Jyothi Rural Electricity Co-operative**, scaling from a single village (4,000 households) up to district level (800,000 households)[cite: 1].

---

## Assignment Overview

* **Assignment Title:** Design, Implement and Validate a Reliable Billing Program for a Rural Electricity Co-operative[cite: 1]
* **Total Marks:** 50[cite: 1]
* **Submission Date:** 26/10/2026[cite: 1]
* **Assessment Levels:** K3 - Apply, K4 - Analyse, K5 - Evaluate[cite: 1]

---

## Repository Structure & Task Breakdown

| Task | Title | Bloom's Level | Source / Code File |
| :--- | :--- | :--- | :--- |
| **Task 1** | Understand the Problem and Identify the Data | K4 - Analyse | `task1_analysis.md`, `task1_data_model.c`[cite: 1, 2] |
| **Task 2** | Choose the Data Types | K4 - Analyse | `task2_datatypes.c`[cite: 2] |
| **Task 3** | Define the Constants | K3 - Apply | `task3_constants.c`[cite: 3, 4] |
| **Task 4** | Use Macros Safely | K4 - Analyse | `task4_macros.c`[cite: 5] |
| **Task 5** | Organise with Header Files & Conditional Compilation | K3 - Apply | `billing.h`, `task5_main.c`[cite: 5, 6] |
| **Task 6** | Read and Print Data Correctly | K3 - Apply | `task6_io.c`[cite: 6] |
| **Task 7** | Control Type Conversion and Precision | K4 - Analyse | `task7_conversion.c`[cite: 6, 7] |
| **Task 8** | Trace the Compilation Process | K3 - Apply | `task8_compilation.c`[cite: 7] |
| **Task 9** | Implement and Test the Billing Program | K3 - Apply | `task9_billing.c`[cite: 8] |
| **Task 10** | Compare Expectations with Execution | K4 - Analyse | `task10_comparison.c`[cite: 8, 9] |
| **Task 11** | Recommend and Defend the Final Design | K5 - Evaluate | `task11_recommendation.c`[cite: 9] |
| **Task 12** | Day-4 Design Challenge: Re-evaluate and Adapt | K5 - Evaluate | `task12_smart_meter.c`[cite: 9, 10] |

---

## Compilation and Execution Instructions

To compile and run any of the task source files, use the GNU C Compiler (`gcc`) with warning flags enabled (`-Wall -Wextra`)[cite: 7]:

```bash
# Example compilation for Task 9
gcc -Wall -Wextra task9_billing.c -o task9_billing
./task9_billing

# Example compilation with DEBUG mode enabled for Task 5
gcc -Wall -Wextra -DDEBUG task5_main.c -o task5_debug
./task5_debug
