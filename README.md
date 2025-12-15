# 🧠 Mindscape: EEG-Based Brain-Computer Interface

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/AI-TensorFlow-orange)
![Status](https://img.shields.io/badge/Status-Prototype-green)
![Award](https://img.shields.io/badge/Award-Best_Project_2025-gold)

> [cite_start]**🏆 Winner:** Mar Mathew Vattakkuzhy Award for Best Project (Mastermind 2025) [cite: 7, 12]

## 📜 Overview
[cite_start]Mindscape is a Proof of Concept (PoC) demonstrating the feasibility of utilizing Electroencephalography (EEG) data to control digital systems[cite: 30]. [cite_start]By processing brain signals through an AI model, the system translates specific thought patterns (Focus, Blink) into actionable cloud triggers[cite: 31, 35].

## 🛠️ Tech Stack
* [cite_start]**Hardware:** EEG Headband (OpenBCI / NeuroSky) [cite: 38]
* [cite_start]**Processing:** Python (NumPy, SciPy) for signal filtering [cite: 39]
* [cite_start]**AI Core:** Scikit-learn / TensorFlow for signal classification [cite: 40]
* [cite_start]**Cloud:** Google Cloud Functions / Firebase for execution triggers [cite: 41]

## ⚙️ System Architecture
1.  [cite_start]**Signal Acquisition:** Captures raw EEG data (0.5-40Hz)[cite: 51].
2.  [cite_start]**Preprocessing:** Applies bandpass filters to remove noise and artifacts[cite: 51].
3.  [cite_start]**Classification:** Neural network identifies patterns: "Focus", "Relax", or "Blink"[cite: 54].
4.  [cite_start]**Cloud Trigger:** Detected patterns fire API calls to execute tasks (e.g., Send Email, Toggle IoT devices)[cite: 57, 62].

## 📊 Performance Results
[cite_start]The prototype achieved high accuracy in controlled environments[cite: 66, 67, 69, 70, 71]:

| Command | Detected Pattern | Execution Time | Accuracy |
| :--- | :--- | :--- | :--- |
| **Send Email** | Focus → Blink | 1.8s | **87%** |
| **Open Website** | High Focus | 1.5s | **90%** |
| **IoT Toggle** | Double Blink | 2.2s | **84%** |

## 🚀 Future Scope (DevSecOps Integration)
* **Neuro-Authentication:** Using unique brainwave signatures as a biological password replacement.
* **Hardening:** Securing the IoT communication channels against interception.

---
*Developed by Nevin Shine. Awarded by Amal Jyothi College of Engineering[cite: 14].*
