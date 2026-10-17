# 🎮 Game-Theoretic Multiphase Flow in Pore Networks

[![Published in TiPM (Paper 1)](https://shields.io)](https://springer.com)
[![Published in TiPM (Paper 2)](https://shields.io)](https://springer.com)
[![Open In Colab](https://google.com)](https://google.com)

An ultra-fast, physics-aware simulation framework for quasi-static multiphase displacement in porous media. By replacing traditional, empirical snap-off and contact angle rules with **Topological Barriers** and **Nash Equilibrium formulations on graphs**, this framework natively predicts capillary pressure hysteresis and residual trapping with remarkable computational efficiency.

---

## ⚡ Key Framework Features

* **Physics-Driven Game Theory:** Eliminates arbitrary empirical tuning factors. Multiphase competition naturally emerges as a dynamic graphical game.
* **Ultra-Fast Performance:** Simulates full primary drainage and imbibition cycles on real-world rock geometries (e.g., **Berea Sandstone**) in just **10 to 20 seconds** inside a standard Google Colab environment.
* **Benchmark Validation:** Native support for standard micro-CT pore network datasets extracted from institutional digital rock libraries, including the **Imperial College London** open repository.

---

## 📄 Core Research & Notebooks

### 1. Static Equilibrium (Potential-Game Formulation)
* **Title:** *A Potential-Game Formulation for Thermodynamic Equilibrium of Two-Phase Systems in Pore Networks*
* **Journal:** *Transport in Porous Media* (Published: June 4, 2026) 
* **Citation:** Transp Porous Med 153, 70 (2026)
* **DOI:** [10.1007/s11242-026-02326-0](https://springer.com)
* **Notebook:** Run the static formulation directly: [![Open In Colab](https://google.com)](https://google.com)

### 2. Hysteresis Dynamics (Dynamic Graphical Game)
* **Title:** *Decomposing Capillary Hysteresis: A Topology-Aware Dynamic Graphical Game for Multiphase Displacement in Pore Networks*
* **Journal:** *Transport in Porous Media* (Published: 2026)
* **Citation:** Transp Porous Med 153, 105 (2026)
* **DOI:** [10.1007/s11242-026-02362-w](https://springer.com)
* **Notebook:** Run the dynamic displacement simulation: [![Open In Colab](https://google.com)](https://google.com)

---

## 📦 Dataset Pipeline & Reproducibility

The dynamic graphical game notebook evaluates the framework across **6 benchmark digital rock networks** (including Berea Sandstone). 

> 💡 **Data Availability Note:** To guarantee instant execution without local setup, the Google Colab notebooks are pre-configured to automatically fetch these 6 network geometries directly from our cloud storage pipeline. You do not need to download or upload external files manually to reproduce the paper's exact figures.

---

## 🗺️ Project Roadmap
- [x] Potential-game static equilibrium framework
- [x] Dynamic graphical game & capillary hysteresis formulation
- [ ] **Interactive GUI Application (Coming Soon):** A web-based dashboard allowing users to upload a micro-CT network file, adjust contact angles, and view hysteresis curves interactively in real time.

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
  number    = {1},
  pages     = {70},
  doi       = {10.1007/s11242-026-02326-0},
  url       = {https://springer.com}
}

@article{mojoodi_dynamic_game_2026,
  author    = {Mojoodi, A.},
  title     = {Decomposing Capillary Hysteresis: A Topology-Aware Dynamic Graphical Game for Multiphase Displacement in Pore Networks},
  journal   = {Transport in Porous Media},
  year      = {2026},
  volume    = {153},
  number    = {1},
  pages     = {105},
  doi       = {10.1007/s11242-026-02362-w},
  url       = {https://springer.com}
}
```

---
*For technical inquiries, scaling collaboration, or mapping new network data, please open an issue or contact the author.*
