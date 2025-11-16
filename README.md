# Simulation of a Microstrip Patch Antenna for Brain Tumor Detection

**Tags:** `RF Design`, `Electromagnetics`, `CST Studio Suite`, `Simulation`, `Antenna Design`

> A simulation and analysis study of a two-element microstrip patch antenna array designed for non-invasive brain tumor detection, modeled in CST Studio Suite.

---
<img width="758" height="358" alt="Image" src="https://github.com/user-attachments/assets/09aee52d-91a8-4bf1-a859-4a3e27ae2373" />

## 1. The Problem

Non-invasive detection of brain tumors is a significant challenge. Microwave Imaging (MWI) is a promising, non-ionizing, and low-cost alternative to MRIs, but it requires highly specialized antennas that can effectively transmit and receive signals through the complex layers of the human head.

## 2. My Solution

For my "Elektromagnetika RF Medis" project, I personally designed and simulated a **two-element microstrip patch antenna array** for brain tumor detection.

The entire project was designed and analyzed in **CST Studio Suite**:
1.  **Antenna Design:** A two-element array was designed on an FR-4 substrate, operating at 1.005 GHz.
2.  **Head Phantom:** A three-layer head phantom (skin, skull, brain) was modeled.
3.  **Simulation:** The antenna's performance was analyzed in both "healthy" and "tumorous" (with a virtual tumor) conditions.

## 3. My Role & Key Contributions

I was the **Sole Researcher and Designer** for this project.

* Designed the microstrip patch antenna array from scratch.
* Built the complex 3-layer head phantom in CST Studio Suite.
* Ran all simulations and analyzed key performance metrics.
* **Key Findings:** The antenna showed excellent impedance matching (S11 < -10 dB) and high isolation. A measurable shift in S-parameters was observed between the healthy and tumorous models, confirming the system's detection capability.
* **Safety Analysis:** Performed a Specific Absorption Rate (SAR) analysis, which yielded a safe value of 0.778 W/kg at 0.01 W input power.

## 4. Technology Stack

* **Software & Tools:** `CST Studio Suite`
* **Concepts:** `RF Electromagnetics`, `Antenna Design`, `Microstrip Patch Array`, `Microwave Imaging`, `S-Parameters`, `Specific Absorption Rate (SAR)`

## 5. Proof & Key Results

* **[CST Simulation File]:** The complete, runnable CST Studio Suite simulation file is located in this repository.
    * **[CST_ProyekAkhir_Deteksi_Brain_Tumor.cst]**
* **[Research Paper]:** The final project report (save as PDF) detailing the design, simulation, and analysis.
    * **[LaporanProyek2025_ElektromagnetikaPerancanganDivaisRFMedis]**

## 6. Project Status

**Status: [Complete]**
*This project was successfully completed for the Elektromagnetika RF Medis course.*
