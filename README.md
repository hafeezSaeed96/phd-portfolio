# 📘 PhD Portfolio – Energy Flexibility & Intelligent Control

👋 Hi, I am Hafeez, a PhD researcher at KU Leuven. My work focuses on physics-informed and data-driven reinforcement learning methods for optimizing building and district-level energy systems.

This repository summarizes the core components of my research and technical contributions developed throughout my PhD.

---

## 🔬 Research Areas
- Physics-Informed Neural Networks (PINNs)
- Deep Operator Networks (DeepONets)
- Deep-Q-Networks, Dyna-Q and Model-Based Reinforcement Learning
- Multi-Agent RL for District Energy Flexibility
- Simulation tools: BOPTEST, CityLearn, yards: Yet Another Residential Districts Simulator

---

## 📝 Key Projects

### [Dyna-PINN](papers_and_projects/dyna-pinn.md)
> Physics-informed deep dyna-q reinforcement learning for intelligent control of building heating system in low-diversity training data regimes. Published in *Energy and Buildings* (2024).  
**Keywords:** Model-based reinforcement learningPhysics-informed neural networksBuildings heating systemDeep dyna-q approachDeep q-network
**DOI:** https://doi.org/10.1016/j.enbuild.2024.114879

### [Barriers to Flexibility from Planning to Operation](papers_and_projects/flexibility_barriers.md)
> Interdisciplinary work investigating real-world challenges in flexibility implementation across the World. Published in *Energy and Buildings* (2023).  
**DOI:** https://doi.org/10.1016/j.enbuild.2023.113608

### [Bottom-Up Flexibility Quantification](papers_and_projects/flexibility_quantification.md)
> A foundational IEEE ISGT paper proposing a method to quantify energy flexibility from clusters of heat pump systems using hot water demand data. Published in IEEE PES Innovative Smart Grid Technologies Conference Europe (2022)
**Keywords:** Cluster Control, HP Flexibility, Grid Congestion, Feeder-Level Aggregation
**DOI:** https://doi.org/10.1109/ISGT-Europe54678.2022.9960599

---

## 🛠️ Code Highlights

| Project | Description |
|--------|-------------|
| [PINN-based Temperature Forecasting](code_highlights/pinn_temperature_prediction.md) | Implementation of a physics-informed neural network (PINN) model to predict indoor air and wall temperatures in a two-state RC building model. The network is constrained using thermal balance equations. |
| [Synthetic Data Generator for RC Model](code_highlights/synthetic_data_generator.md) | Script to simulate synthetic temperature trajectories for multiple buildings using a 2-state RC model. Supports control inputs like heat pump operation and outdoor weather conditions. |
| [Flexibility Request CLI Tool](code_highlights/flexibility_requests_cli.md) | A command-line interface (CLI) tool to compute cluster-level flexibility requests based on annual consumption data and dynamic pricing thresholds. Useful for simulating grid-congestion scenarios. |

---

## 📊 Tools & Utilities
- Post-KPI aggregation scripts (cost, emissions, thermal discomfort)
- DAE solver wrappers
- Plotting utilities for multi-building KPIs

---

## 🤝 Acknowledgments

This PhD research is funded by the **Research Foundation – Flanders (FWO)**.

I would also like to acknowledge the support and supervision of **Prof. Geert Deconinck** and **Dr. Hussain Kazmi** at KU Leuven.

---

## 🌐 Contact
- Email: hafeez.saeed96@gmail.com  
- LinkedIn: [Muhammad Hafeez Saeed](https://www.linkedin.com/in/mhafeezsaeed/)

---
> *Note: Some repositories are hosted on institutional GitLab due to project-specific constraints.*
