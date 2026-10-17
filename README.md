# Article Codes – Multiphase Flow in Pore Networks

This repository contains the simulation codes accompanying our research on multiphase displacement in porous media. By replacing traditional empirical snap-off and contact angle rules with **Topological Barriers** and **Nash Equilibrium formulations on graphs**, this framework natively predicts capillary pressure hysteresis and residual trapping with high computational efficiency.

## ⚡ Key Framework Features
* **Physics-Driven Game Theory:** Eliminates arbitrary empirical tuning factors. Multiphase competition naturally emerges as a dynamic graphical game.
* **Ultra-Fast Performance:** Simulates full primary drainage and imbibition cycles on real-world rock geometries (e.g., **Berea Sandstone** micro-CT networks from the **Imperial College London** open library) in just **10 to 20 seconds** inside Google Colab.

---

## 📄 Published Papers (Code Available)

### Paper 1: Potential-Game Formulation

**Title:**  
*A Potential-Game Formulation for Thermodynamic Equilibrium of Two-Phase Systems in Pore Networks*

**Journal:** Transport in Porous Media (Transp Porous Med 153, 70 (2026))  
**DOI / Link:** [https://link.springer.com/article/10.1007/s11242-026-02326-0](https://link.springer.com/article/10.1007/s11242-026-02326-0)

Click the badge below to open and run the corresponding notebook (`PotentialGame.ipynb`) directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ML-OilGas/Article_Codes/blob/main/PotentialGame.ipynb)

---

### Paper 2: Decomposing Capillary Hysteresis

**Title:**  
*Decomposing Capillary Hysteresis: A Topology-Aware Dynamic Graphical Game for Multiphase Displacement in Pore Networks*

**Journal:** Transport in Porous Media (Transp Porous Med 153, 105 (2026))  
**DOI / Link:** [https://link.springer.com/article/10.1007/s11242-026-02362-w](https://link.springer.com/article/10.1007/s11242-026-02362-w)

Click the badge below to open and run the corresponding notebook (`DynamicGraphicalGame.ipynb`) directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ML-OilGas/Article_Codes/blob/main/DynamicGraphicalGame.ipynb)

---

## 📦 Dataset Pipeline & Reproducibility
To guarantee instant execution without local setup, the Google Colab notebooks are pre-configured to automatically fetch the 6 benchmark digital rock networks (including Berea Sandstone) directly from our cloud storage pipeline. You do not need to download or upload external files manually to reproduce the paper's exact figures.

---

## ✒️ Citation

If you use this framework, the game-theoretic formulations, or the accompanying simulation codes in your research, please cite the following papers:

```bibtex
@article{mojoodi_potential_game_2026,
  author    = {Mojoodi, A.},
  title     = {A Potential-Game Formulation for Thermodynamic Equilibrium of Two-Phase Systems in Pore Networks},
  journal   = {Transport in Porous Media},
  year      = {2026},
  volume    = {153},
  pages     = {70},
  doi       = {10.1007/s11242-026-02326-0},
  url       = {https://link.springer.com/article/10.1007/s11242-026-02326-0}
}

@article{mojoodi_dynamic_game_2026,
  author    = {Mojoodi, A.},
  title     = {Decomposing Capillary Hysteresis: A Topology-Aware Dynamic Graphical Game for Multiphase Displacement in Pore Networks},
  journal   = {Transport in Porous Media},
  year      = {2026},
  volume    = {153},
  pages     = {105},
  doi       = {10.1007/s11242-026-02362-w},
  url       = {https://link.springer.com/article/10.1007/s11242-026-02362-w}
}
```

---

*For any questions, feel free to open an issue or contact the corresponding author.*
