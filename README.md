# 26_05_PhageCocktail_NSGAII
Python code for mining phage cocktail combinations using the NSGA-II algorithm
A **multi‑objective genetic algorithm framework** for designing phage cocktails that optimally balance **lysis coverage**, **cocktail size**, and **worst‑host protection**.  
---

## 🧬 Overview

Phage therapy is a powerful weapon against antibiotic‑resistant “superbugs”, yet cocktail design remains largely empirical. This project replaces trial‑and‑error with a **standardized computational pipeline**:

- Convert phage–host interaction matrices into binary decision variables.
- Use **NSGA‑II** (Non‑dominated Sorting Genetic Algorithm II) to evolve a **Pareto front** of optimal phage combinations.
- Visualize convergence, hypervolume, Pareto fronts, and biological patterns (heatmaps, histograms).

The algorithm is validated on **three complementary datasets** that span dense experimental matrices, predicted interactions, and highly sparse cross‑genera collections.

---
