
# Francesco Scolz

[![Arch Linux Supporter](https://img.shields.io/badge/Arch_Linux-Supporter-green?logo=arch-linux&logoColor=1793D1)](https://archlinux.org/donate/)
![Linux](https://img.shields.io/badge/Platform-Linux-FCC624?logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-Versioning-F05032?logo=git&logoColor=white)

Student focused on computer science, mathematics, and systems engineering, with hands-on experience developing software, managing Linux systems, analyzing network traffic, and building machine learning pipelines.

I work across the stack, from system configuration and network analysis to application development, data analysis, and model evaluation. My projects emphasize practical engineering, measurable results, reliability, and a clear understanding of system behavior.

## Core Focus

- Linux systems administration and service management
- Network traffic analysis and intrusion detection
- Software development and system architecture
- Applied machine learning and statistical evaluation
- Data analysis, model robustness, and interpretability

## Technical Stack

**Languages:** Python (proficient), C and SQL (basics)

**Systems & Networking:** Linux, Arch Linux, systemd, tshark, TCP/IP

**Data Science & ML:** NumPy, pandas, scikit-learn, PyTorch, SHAP, Matplotlib

**Development Tools:** Git, Jupyter, VS Code and derivatives

---

## Featured Projects

### [LightIDS](https://github.com/FreyFlyy/light-ids)

Lightweight, heuristic-based Intrusion Detection System for real-time network traffic analysis and anomaly detection in home labs.

- **Implementation:** Python/Flask backend, `tshark` packet capture, heuristic scoring engine, JavaScript/Chart.js dashboard, and SQLite persistence.
- **Features:** Configurable thresholds, graylist/watchlist/whitelist, authentication, and real-time traffic monitoring.
- **Deployment:** Tested on a Raspberry Pi 5 in a home network with approximately 10–12 devices and a 20 Mbps connection.
- **Resource usage:** Under 1% CPU direct at idle and approximately 220–330 MB RAM.
- **Detection capabilities:** Port scans, flooding/DoS patterns, and suspicious service probing.
- **Status:** v3.0.0.

### [Redoubt](https://github.com/FreyFlyy/Redoubt)

Peer-to-peer messaging application providing end-to-end encryption, authenticated contacts, and protection against passive network observation and active man-in-the-middle attacks.

- **Implementation:** Python CLI/TUI using X25519, HKDF, AES-GCM, Argon2id, and SQLCipher.
- **Security features:** Encrypted identity vault, fixed-size 4096-byte packet padding, out-of-band fingerprint verification, and hardened storage/memory handling.
- **Security model:** Documented threat model and explicit security limitations.
- **Status:** Experimental early release, with a roadmap toward Double Ratchet/X3DH, post-compromise security, and memory-safe critical components.
- **Packaging:** Arch Linux.

### [Recto](https://github.com/FreyFlyy/Recto)

Free, open-source, self-hosted flashcard platform combining rating-based study workflows with Anki-style openness, without mandatory spaced repetition.

- **Implementation:** Minimal Python HTTP server using only the standard library, with a vanilla JavaScript frontend.
- **Storage:** Filesystem-based CSV decks and persistent JSON ratings.
- **Features:** REST API, HTML sanitization, import/export, editable decks, filtering by rating/tag/subdeck, and mobile-friendly UI.
- **Deployment:** Self-hosted, device-independent, and compatible with systemd.
- **Status:** v1.0.0.

---

## Machine Learning Projects

### [Taiwan Robust and Explainable Credit Lending](https://github.com/FreyFlyy/data-science-projects)

- **Model:** Triple-scenario model engine using Random Forest and Logistic Regression.
- **Task:** Predict credit card default from structured financial and behavioral data.
- **Evaluation:** Positive mean net profit on the test set based on backtested model predictions.
- **Focus:** Business-driven evaluation under real-world hypotheses and noisy scenarios.

### Weather Rain Prediction — S. Osvaldo

- **Model:** Random Forest.
- **Task:** Predict next-day rain from historical meteorological data.
- **Results:** Accuracy 71.35%, ROC-AUC 77.27%.
- **Focus:** Classification using real-world meteorological data with noisy features.

### Youth Stress Prediction

- **Model:** Logistic Regression.
- **Task:** Predict stress type from a 25-question survey.
- **Results:** Macro F1 = 0.8538.
- **Focus:** Multiclass classification under significant class imbalance.

---

## Current Work

- **Model Robustness & Stress Testing:** Analyzing ensemble performance degradation under progressive feature omission and noise injection.
- **Explainability & Decision Limits:** Investigating global and local interpretability in tree-based models, including SHAP, and evaluating threshold sensitivity under asymmetric loss.
- **Production-Oriented ML Engineering:** Developing vectorized validation pipelines, probability calibration, and empirical performance evaluation using frequentist confidence intervals.

---

## Profiles & Contacts

- **GitHub:** [FreyFlyy](https://github.com/FreyFlyy)
- **LinkedIn:** [Francesco Scolz](https://www.linkedin.com/in/francesco-scolz)
- **Kaggle:** [freyfly](https://www.kaggle.com/freyfly)
- **Hugging Face:** [FreyFlyy](https://huggingface.co/FreyFlyy)
