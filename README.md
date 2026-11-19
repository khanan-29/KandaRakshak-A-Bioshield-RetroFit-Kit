# KandaRakshak: A Bio-Shield Retrofit Kit

A passive, zero-electricity "snap-on" retrofit kit that transforms traditional storage crates into self-ventilating, bio-active onion preservation chambers—slashing post-harvest crop loss from 35–40% to under 10%.

![Event](https://img.shields.io/badge/SIH_2026-University_Internal_Round_2_Qualifier-success) ![Team](https://img.shields.io/badge/Team-HelixSix_-blue) ![Tech](https://img.shields.io/badge/Stack-Python_|_NumPy_|_Trimesh_|_Pygame-orange)

---

## Overview
India loses 35%–40% of its post-harvest onions annually to ethylene-induced sprouting and fungal mold, while conventional electronic IoT cold-storage setups are expensive and corrode rapidly in humid rural conditions. 

**KandaRakshak** solves this using a nature-driven, zero-electricity approach:
* **3-Layer Bio-Active Sorbent Bed:** Combines antifungal VOC pads, an ethylene scrubber, and a natural zeolite moisture buffer.
* **Passive Solar Chimney Ventilation:** Generates continuous natural airflow without external power or electronics.

---

## Repository Structure

| File / Video | Description |
| :--- | :--- |
| `kandarakshak.ipynb` | Core 3D digital twin geometry and bio-shield structural modeling built with **NumPy** & **Trimesh**.|
| `KandaRakshak prototype.mp4` | Live demonstration of the physical hand-assembled hardware prototype. |
| `airflow prototype simulation.ipynb` | Interactive fluid/airflow dynamics simulation built in **Pygame** validating passive solar chimney updrafts. |
| `airflow pygame simulations.mp4` | Video demonstration of the live Pygame airflow simulation. |
| `KandaRakshak with biosensors.mp4` | Live validation video showing biosensor monitoring on the kit.|
| `KandaRakshak with sensors` | Sensor telemetry and calibration script. |
| `Alert` | Threshold monitoring and alert trigger module.|

---

## Code Results & Validation

### 1. Airflow Prototype Simulation (`airflow prototype simulation.ipynb`)
* **Passive Updraft Velocity:** `0.1 – 0.2 m/s` continuous convective flow achieved via solar chimney thermal gradient.
* **Power Consumption:** `0 Watts` (100% passive operation).
* **Result:** Confirmed uniform air circulation across all three sorbent layers without stagnant moisture pockets.

### 2. 3D Digital Twin & Hardware Prototype (`kandarakshak.ipynb`)
* Built parametric 3D mesh models using **Trimesh** and **NumPy** to optimize crate snap-on fit and chimney dimensions prior to hand-assembling the physical hardware prototype.

### 3. Projected Agricultural & Economic Impact
| Metric | Traditional Storage | With KandaRakshak |
| :--- | :---: | :---: |
| **Post-Harvest Crop Loss** | 35% – 40% | **< 10%** |
| **Extra Yield Retained** | Baseline | **+250 to 300 kg / ton** |
| **Electricity Requirement** | High (Cold Storage) | **0 Watts (Zero-Electricity)** |
| **Return on Investment** | Multi-year | **Single 90-day storage cycle** |

---

## Team HelixSix 
* **Background:** 2nd year Biotechnology Students (Minor in Bioinformatics)
* **Ideator, Project Lead & Lead Developer**: **Khanan Khonda**
* **Core Team:** Afiya Ansari, Dhriti Momaya, Riya Joshi, Shazia Laljee, Falak Warsi
* *Developed for Smart India Hackathon (SIH) 2026 — Somaiya School of Basic and Applied Sciences (Internal Rounds).*
