##  Project Summary

This repository presents a novel, explainable, and energy-efficient framework for **Malicious URL Detection** using a **Weighted Tsetlin Machine (WTM)**. Designed specifically for resource-constrained edge devices and firewalls, the framework replaces traditional, compute-heavy floating-point operations with lightweight bitwise Boolean AND logic and integer clause voting.

 Key Highlights
* **Reduced Floating-Point Operations:* Replaces multiplication-heavy deep learning architectures with fast Boolean logic operations.
* **Ultra-Low Latency:** Requires only 2,660 2-input AND gates per pass, delivering microsecond-level inference latency (~38× faster than meta-learning DL baselines).
* **High Performance:** Achieves **97.64% accuracy** on the benchmark ISCX-URL-2016 dataset across 5 threat classes (Benign, Defacement, Phishing, Malware, Spam).
* **Native & Post-Hoc Explainability:** Features the **Multi-Perspective Logic Attribution (MPLA)** algorithm, which combines internal Tsetlin Automata clause weights with Discrete Mutual Information to yield transparent feature rankings.
* **Leakage-Free Binarization & Pruning:** Uses dynamic thermometer encoding to convert continuous lexical URL features into binary representations, alongside a Zero-Frequency Feature Audit to automatically strip uninformative noise channels.# Tsetlin_Machine_URL_classification
