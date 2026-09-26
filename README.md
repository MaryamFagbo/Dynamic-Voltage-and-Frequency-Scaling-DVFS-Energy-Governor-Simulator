# DVFS Energy Governor Simulator

A lightweight Python simulation modeling a Linux-style Dynamic Voltage and Frequency Scaling (DVFS) power governor for resource-constrained edge computing architectures.

## Overview

In low-power systems and embedded hardware, balancing computational performance with energy efficiency is vital. This project implements:
1. **Synthetic Workload Generation** simulating fluctuating task demands over time.
2. **A Threshold-Based Governor Policy** that dynamically scales CPU frequency and operating voltage profiles.
3. **Dynamic Power Calculation** utilizing fundamental hardware power metrics ($P \propto V^2 \cdot f$).
4. **Performance Visualization** plotting workload adjustments against real-time frequency transitions.

## Code Architecture

* **Dependencies:** `numpy`, `matplotlib`
* **Core Logic:** Threshold-driven hardware power state controller.
* **Environment:** Developed and executed via Google Colab.

## How to Run

View and execute this notebook directly in Google Colab:


https://colab.research.google.com/drive/1uTreZcFGaaU6k7AdRVCy2lH0Y0kw4ze6?usp=sharing

MARYAM FAGBO
