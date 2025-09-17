# 🚀 Drone-Assisted Communication System Simulation  

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)  
![Simulation](https://img.shields.io/badge/Simulation-Queuing%20Theory-orange)  
![Telecom](https://img.shields.io/badge/Domain-Telecom%20Networks-green)  
![License](https://img.shields.io/badge/License-Academic-lightgrey)  

---

## 📍 Overview  
This project was developed for the **Management and Content Delivery for Smart Networks (MCDSN)** course at **Politecnico di Torino**.  

It focuses on simulating **drone-assisted communication systems**, where **solar-powered UAVs** act as aerial base stations to offload traffic from terrestrial networks during peak demand.  

The network is modeled as a **queuing system (M/M/1, M/M/2, M/G/1, etc.)**, extended to include **energy constraints, finite/infinite buffers, and scheduling strategies**.  

---

## 📸 System Scenario  

The figure below shows the **simulation scenario** with **solar-powered UAVs** assisting **on-ground base stations** during peak traffic.  

<img src="image scenario.png" alt="System Scenario" width="600"/>



---

## ✨ Features  
✅ Simulation of **UAV-assisted Base Stations (BSs)** with queuing theory  
✅ Performance metrics: throughput, delays, buffer occupancy, loss probability  
✅ Analysis of **finite vs infinite buffers** and **multi-server setups**  
✅ Scheduling strategies under **battery & PV panel constraints** ☀️🔋  
✅ Comparison of drone configurations for **QoS optimization**  
✅ Complete **lab reports** with results, graphs, and insights  

---

## 📂 Repository Structure  

```
.
├─ LAB1_Group3.ipynb        # Lab 1 notebook: Queuing models & buffer analysis  
├─ LAB2_Group3.ipynb        # Lab 2 notebook: Scheduling & energy-aware UAVs  
├─ Lab_Report_Group3.pdf    # Consolidated report (Lab 1 + Lab 2 results)  
├─ 2022_MCDSN_lab1.pdf      # Lab 1 assignment (official handout)  
├─ 2022_MCDSN_lab2_2.pdf    # Lab 2 assignment (official handout)  
├─ requirements.txt         # Python dependencies  
├─ b04c580d-ea06-4ac9-a034-d61cc3ee97ab.png  # Scenario image  
└─ README.md                # Project documentation

```

---

## 🧪 Labs Summary  

### 📘 Lab 1: Queuing Model of UAV-Assisted BSs  
- **Scenario:** UAV with solar panel and antennas providing extra capacity.  
- **Tasks:**  
  - M/M/1 baseline with/without packet losses  
  - M/M/2 multi-server system with finite & infinite buffers  
  - Impact of varying arrival rates  
  - M/G/1 service distribution analysis  
- **Key Metrics:** average delay, throughput, buffer occupancy, loss probability  

📊 **Result:** A single UAV with **two antennas (M/M/2)** outperforms two UAVs with single antennas each, especially at higher traffic loads.  

---

### 📘 Lab 2: Scheduling Strategies & Energy Constraints  
- **Scenario:** UAVs powered by **battery or battery+PV panel**.  
- **Tasks:**  
  - Scheduling under traffic variations (business vs residential areas)  
  - Constraints on battery charging/discharging cycles  
  - Effect of PV panel capacity (40W, 60W, 70W)  
  - Multi-drone configurations (Types A, B, C)  
- **Key Metrics:** active time, departures, average delay, energy cycles  

📊 **Result:**  
- Larger PV panels → more active time, fewer charging cycles  
- Hybrid drone setups (Type B + Type C) offer the best **trade-off** between handled traffic, battery health, and QoS  

---

## ⚙️ Installation  

### 🔑 Requirements  
- Python **3.9+**  
- Jupyter Notebook / Google Colab  

### 📦 Setup  
1. Clone the repository or upload files to Google Colab.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open `LAB1_Group3.ipynb` or `LAB2_Group3.ipynb` in Jupyter/Colab.  
4. Run the cells to reproduce the simulations and plots.  

---

## 📜 Requirements File  

```txt
numpy
scipy
matplotlib
pandas
seaborn
tqdm
jupyter
ipykernel
```

---

## 👩‍💻 Authors  
- **Asal Malekshahi**   
- **Niloufar Fotouhi** 
- **Mahshid Alamdari** 

**Supervisors:** Prof. Meo, Prof. Renga  

---

## 📜 License  
This repository is for **educational purposes only** under the MCDSN course at Politecnico di Torino.  

---
✈️ *“Optimizing Smart Networks with UAVs – sustainable, flexible, and scalable.”*
