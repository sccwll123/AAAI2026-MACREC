This repository contains the official implementation of  
**MACRec: Multi-view Subspace Alignment for Contrastive Recommendation (AAAI 2026)**

MACRec is a **Graph Contrastive Learning (GCL)** framework designed to address the **persistent false negative problem** in recommender systems.  
Unlike heuristic or local neighborhood-based approaches, MACRec adopts a **global, data-driven calibration strategy** to accurately distinguish true positives from false negatives, offering improved flexibility and robustness.

---

## 🔍 Motivation

Most GCL-based recommendation models rely on the InfoNCE loss, which indiscriminately treats all non-anchor samples as negatives.  
This often leads to the **false negative problem**, where semantically similar users or items are incorrectly repelled, degrading representation quality.

MACRec mitigates this issue by explicitly modeling global semantic affinities and interaction-aware signals to calibrate contrastive sampling.

---

## 🚀 Method Overview

MACRec consists of three core components:

- **Multi-view Subspace Affinity Modeling**  
  Learns latent global semantic similarity among users and items via self-expression and multi-view reconstruction.

- **Cross-Subspace Semantic Alignment (CSA)**  
  Aligns user and item subspaces through interaction-aware propagation to ensure semantic consistency.

- **Contrastive Calibration Reweighting (CCR)**  
  Dynamically reweights negative samples based on subspace affinity and behavioral indicators, effectively suppressing false negatives.

---

## 📄 Paper

- **Title:** MACRec: Multi-view Subspace Alignment for Contrastive Recommendation  
- **PDF:** ✅ Available (uploaded)

Please refer to the paper for detailed methodology, theoretical analysis, and experimental results.

---

---

## 💻 Code

🚧 **Code will be released soon.**

The codebase is currently being organized and cleaned for public release. The repository will be updated soon.

---

## 📬 Contact

For questions or discussions, please contact:

- **Mingchao Yu**
- Kidkdd78@gmail.com

---

