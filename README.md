# Francesco Scolz

[![Arch Linux Supporter](https://img.shields.io/badge/Arch_Linux-Supporter-green?logo=arch-linux&logoColor=1793D1)](https://archlinux.org/donate/)
![Linux](https://img.shields.io/badge/Platform-Linux-FCC624?logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-Versioning-F05032?logo=git&logoColor=white)

Data Science / Machine Learning student focused on building reliable ML systems for tabular structured data, with emphasis on measurable performance, real-world robustness and interpretability

## Core Focus
- Supervised learning on tabular datasets
- Model evaluation, validation strategies, error analysis
- Feature engineering for structured data
- End-to-end Python ML pipelines

## Technical Stack

**Python:** pandas, numpy, matplotlib, scikit-learn, pytorch, shap

**Tools:** Git, Linux (Arch based), Jupyter, VSCode / NeoVim IDE

---

## Top ML Projects (in [Data Science Projets](https://github.com/FreyFlyy/data-science-projects))

### Taiwan Robust and Explainable Credit Lend 
- **Model**: Triple-scenario model engine (RF and LR)
- **Task**: Predict credit card default from tabular behavioral financial data
- **Result**: positive mean net profit on the test set based on backtested model predictions
- **Notes**: Entirely business driven and tested under real world hypotheses and noisy scenarios

### Weather Rain Prediction S. Osvaldo (binary classification)
- **Model**: Random Forest
- **Task**: Predict next-day rain from past meteorological data
- **Result**: Accuracy 71.35%, ROC-AUC 77.27%
- **Notes**: trained on real-world meteorological data with noisy features

### Youth Stress Prediction (multi-class classification)
- **Model**: Logistic Regression
- **Task**: Predict stress type from a 25-question survey
- **Result**: Macro F1 = 0.8538
- **Notes**: performance achieved under significant class imbalance

## Top non-ML Projects

### [LightIDS](https://github.com/FreyFlyy/light-ids)
- **Description**: Lightweight, heuristic-based **Intrusion Detection System** for real-time network traffic analysis and anomaly detection in home labs.
- **Structure**: Python/Flask backend with `tshark` packet capture and heuristic scoring engine + JavaScript/Chart.js web dashboard; SQLite persistence, configurable thresholds, graylist/watchlist/whitelist and authentication.
- **Result**: **v3.0.0**, tested on a Raspberry Pi 5 with ~10–12 devices and a 20 Mbps network; **<1% CPU** in idle conditions and ~220–330 MB RAM, capable of detecting port scans, flooding/DoS patterns and suspicious service probing.

### [Redoubt](https://github.com/FreyFlyy/Redoubt)
- **Description**: Peer-to-peer messaging application providing **end-to-end encryption**, authenticated contacts and protection against passive network observation and active MITM attacks.
- **Structure**: Python CLI/TUI using X25519, HKDF, AES-GCM, Argon2id and SQLCipher; encrypted identity vault, fixed-size 4096-byte packet padding, out-of-band fingerprint verification and hardened storage/memory handling.
- **Result**: **v0.0.1 experimental / V1**, with a documented threat model and explicit security limitations; packaged for Arch Linux and designed with a roadmap toward **Double Ratchet/X3DH**, post-compromise security and memory-safe critical components.
- 
### [Recto](https://github.com/FreyFlyy/Recto)
- **Description**: Free, open-source, self-hosted flashcard platform combining **Vaia/StudySmarter-style rating** with Anki's openness, but without forced spaced repetition.
- **Structure**: Minimal Python HTTP server using only the standard library + vanilla JavaScript frontend; filesystem-based CSV decks, persistent JSON ratings, REST API, HTML sanitization, import/export and systemd support.
- **Result**: **v1.0.0**, fully self-hosted and device-independent, with mobile-friendly UI, editable decks, filtering by rating/tag/subdeck and direct **CSV import**.

---

## Current Work
* **Model Robustness & Stress-Testing:** Analyzing ensemble performance decay under progressive feature omission and noise injection.
* **Explainability & Decision Limits:** Studying global and local interpretability in tree-based models (SHAP/tree-priors) to evaluate threshold sensitivity under asymmetric loss regimes.
* **Production-Ready Engineering:** Developing vectorized validation pipelines, probability calibration logic, and empirical performance testing using frequentist confidence intervals.

---

## Contacts
- GitHub: [FreyFlyy](https://github.com/FreyFlyy)
- LinkedIn: [Francesco Scolz](https://www.linkedin.com/in/francesco-scolz)
- Hugging Face: [FreyFlyy](https://huggingface.co/FreyFlyy)
