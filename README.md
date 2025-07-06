# Advances in Supercritical Carbon Dioxide Technologies

## Project Overview

This project investigates the use of **Supercritical Carbon Dioxide (SC-CO<sub>2</sub>)** as a green, efficient, and selective solvent for separating bioactive compounds, particularly focusing on applications like **caffeine removal from coffee beans**.

We implemented simulations and sensitivity analyses in **Python (Google Colab)**, visualized the process flow, and explored mass transfer principles, tray efficiency, and optimization of operational parameters.


## Final Learnings & Key Takeaways

* **Pressure** is the most influential factor affecting solubility, phase stability, and overall extraction efficiency.
* **Stripping Factor (A)** and **Tray Efficiency (E)** significantly reduce the number of required stages.
* **Temperature** has a secondary impact within typical operating ranges but is important in fine-tuning.
* **SC-CO<sub>2</sub> extraction is highly selective and eco-friendly**, making it an excellent alternative to traditional solvent methods.
* **Interactive simulations and visualizations** helped us deeply understand multistage extraction systems and design optimizations.
* Gained hands-on experience with **Python modeling**, **Kremser equation**, **sensitivity analysis (SALib)**, and **column simulation** techniques.


## Project Objectives

* Simulate a **liquid-liquid extraction** system using SC-CO<sub>2</sub> as the solvent.
* Use the **Kremser Equation** to calculate theoretical and actual stage requirements.
* Analyze the impact of various parameters on **separation efficiency**.
* Visualize extraction kinetics, McCabe-Thiele diagram, and tray-wise column design.
* Conduct **Sobol-based sensitivity analysis** to identify dominant factors.


## Technical Summary

* **Equations Used**:

  * Peng–Robinson EOS
  * Chrastil's Solubility Correlation
  * Fick’s Law of Diffusion
  * Reynolds and Sherwood Number

* **Simulations**:

  * Mass transfer modeling
  * Tray calculation via Kremser Equation
  * Interactive tray efficiency plot
  * McCabe-Thiele diagram generation

* **Sensitivity Analysis**:

  * Using SALib and Sobol indices
  * Analyzed effects of `Temperature`, `Pressure`, `K_La`


## Links
- [Presentation on Canva](https://www.canva.com/design/DAGkQ-KX8OY/0wmB-_Bi4zN626xrg-K1Og/edit)
- [Colab Notebook – Supercritical CO<sub>2</sub> Simulation](https://colab.research.google.com/drive/1r805AgEYWniCC0-YwHYxZvWp3wQetl6m?usp=sharing)

## Team Members

* Vedika Butle (230008012)
* Mannan Mahajan (230008020)
* Mohak Dadhich (230008023)

<!-- ## Refrences

- SALib: Sensitivity Analysis Library in Python - [GitHub Repo](https://github.com/SALib/SALib) -->