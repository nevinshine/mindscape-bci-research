# 🧠 Mindscape: BCI System Architecture (Proof of Concept)

![Status](https://img.shields.io/badge/Status-Research_PoC-blue)
![Award](https://img.shields.io/badge/Award-Best_Project_2025-gold)
![Tech](https://img.shields.io/badge/Focus-System_Design-green)

> **🏆 Winner:** Mar Mathew Vattakkuzhy Award for Best Project (Mastermind 2025)

## 📜 Project Overview
**Mindscape** is a comprehensive **Proof of Concept (PoC)** designed to demonstrate the feasibility of converting brain signals into digital commands. This project focuses on the **System Architecture** and **Feasibility Study** of integrating EEG hardware with Cloud APIs to control digital environments using AI-interpreted thought patterns.

## 🏗️ Proposed Architecture
The system is designed to operate on a 4-stage data pipeline:

1.  **Acquisition:** Capturing raw EEG data via wearable headsets (e.g., OpenBCI, NeuroSky).
2.  **Processing:** Applying Bandpass filters (0.5-40Hz) using **Python (NumPy/SciPy)** to remove noise.
3.  **Classification:** Utilizing an AI Model (TensorFlow/Scikit-learn) to detect specific neural patterns:
    * *Focus* (Concentration)
    * *Relax* (Neutral)
    * *Blink* (Confirmation Trigger)
4.  **Execution:** Sending verified signals to **Cloud Functions** to trigger real-world actions (e.g., Sending an Email, Toggling IoT lights).

## 📊 Feasibility Results
The research validated the core logic for interpreting signals with the following projected metrics based on the prototype design:

| Command | Detected Brain Pattern | Est. Execution Time | Target Accuracy |
| :--- | :--- | :--- | :--- |
| **Send Email** | Focus → Blink | < 2.0s | ~87% |
| **Open Website** | High Focus | < 1.5s | ~90% |
| **IoT Toggle** | Double Blink | < 2.5s | ~84% |

## 🏆 Awards & Recognition
* **Best Project Award:** Won the *Mar Mathew Vattakkuzhy Award* at the AJCE Mastermind 2025 contest.
* **Innovation:** Recognized for applying signal processing and AI to solve accessibility challenges.

## 📄 Documentation
* [View Proof of Concept Document (PDF)](PoC_Mindscape.pdf)

---
*Conceptualized by Nevin Shine. Awarded by Amal Jyothi College of Engineering (Kanjirapally).*
