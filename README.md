# 🇬🇭 GIPHEP Dashboard
### **Ghana Integrated Public Health Emergency Platform**
> **National Outbreak Intelligence & Emergency Coordination Platform for the Ghana Health Service (GHS)**

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_svg.svg)](https://npheoc-m2dvbtnvbqbg4uvzzysbr3.streamlit.app/)
[![GitHub Core Repo](https://img.shields.io/badge/GitHub-Repository-100000?style=flat&logo=github&logoColor=white)](https://github.com/npheoc-glitch)
[![LinkedIn Developer](https://img.shields.io/badge/LinkedIn-Contact_Developer-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ebenezer-kwaw/)

---

## 📌 Executive Overview

Public health surveillance across Ghana’s 16 regions and 261 districts historically relied on fragmented data pipelines, slowing situational updates to the Public Health Emergency Operations Centre (PHEOC). 

**GIPHEP** bridges this operational gap. It serves as a rapid-ingestion, production-grade intelligence layer designed to bypass heavy, multi-tier database syncing infrastructures. By integrating directly with field export mechanisms (such as **KoboCollect** data metrics and standardized Excel/CSV Situation Reports), GIPHEP maps transmission vectors, monitors Case Fatality Rates (CFR), and tracks epidemiological trajectories in real time using official national colors and high-fidelity Emergency Operations Command graphics.

---

## ⚡ Core Platform Capabilities

* **Zero-Database Local Processing:** Executes memory-efficient `pandas` vector transformations locally. Ensures emergency response teams can deploy instantly in low-connectivity areas using static workbook dumps.
* **Dynamic Spatial Radar:** Interactive GIS geographical modules highlighting outbreak coordinates and regional risk matrices via `Folium`.
* **Advanced Epicurve Reconstruction:** Advanced temporal modeling including automated 7-Day Moving Averages, case-doubling rates ($R_t$), and transmission event markers.
* **Automated Insights Engine:** Replaces manual situational logging with rule-based epidemiological alerts to eliminate human reporting delay.
* **High-Res Command UI:** Designed around a dark, institutional dashboard matrix that adapts perfectly to large EOC video walls.

---

## 🛠️ System Workflow & Data Pipeline
