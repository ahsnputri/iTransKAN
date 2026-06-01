# iTransKAN: A Deep Chemometric Model for Enhanced Heavy Metal Quantification via Multi-Scan Cyclic Voltammetry

This repository contains the official source code implementation for the paper:  
**"iTransKAN: A Deep Chemometric Model for Enhanced Heavy Metal Quantification via Multi-Scan Cyclic Voltammetry"**

### Authors
Fadlilatul Taufany, Rizqy Ahsana Putri, Riyanarto Sarno, Wahyu Prasetyo Utomo, Kelly Rossa Sungkono, and Arif Abdullah Sagran

---

## 📌 Overview

This repository is dedicated to providing the source code for reproducibility and transparency of the proposed **iTransKAN** framework. The model leverages an inverted Transformer backbone coupled with a Kolmogorov-Arnold Network (KAN) regression head, specifically optimized for deep chemometric analysis and heavy metal ($\text{Pb}^{2+}$ and $\text{Cd}^{2+}$) quantification using multi-scan cyclic voltammetry data.

For convenience and keeping the workspace tidy during the review/publication process, the entire codebase has been packaged into a single archive file.

---

## 📂 Repository Contents

*   **`iTransKAN_source_code.zip`**: The core package containing:
    *   Model architecture definitions (iTransKAN, Learnable Positional Embeddings, and KAN regression modules).
    *   Ablation and comparative baseline scripts (standard iTransformer, etc.).
    *   Training, optimization (Optuna/TPE), and evaluation pipelines.

---

## 🚀 Getting Started

1. **Download and Extract:**
   Download the `iTransKAN_source_code.zip` file from this repository and extract it to your local working directory.
   
2. **Environment Setup:**
   Ensure you have Python installed. It is highly recommended to use a virtual environment. Install the required dependencies listed inside the extracted folder (typically via `pip install -r requirements.txt`).

3. **Running the Model:**
   Follow the execution instructions provided in the detailed `README` or script comments inside the zip archive to train or evaluate the network.

---

## ✉️ Contact & Data Requests

The datasets used in this study and any supplementary material are available upon reasonable request. If you have any questions regarding the code implementation, hyperparameters, or require access to the data for replication, please feel free to contact:

*   **Email:** [rizqyahsana1@gmail.com](mailto:rizqyahsana1@gmail.com)

---

## 📝 Citation

If you find this code useful for your research, please consider citing our journal paper once it is officially published:

```bibtex
@article{taufany2026itranskan,
  title={iTransKAN: A Deep Chemometric Model for Enhanced Heavy Metal Quantification via Multi-Scan Cyclic Voltammetry},
  author={Taufany, Fadlilatul and Putri, Rizqy Ahsana and Sarno, Riyanarto and Utomo, Wahyu Prasetyo and Sungkono, Kelly Rossa and Sagran, Arif Abdullah},
  journal={[Journal Name]},
  year={2026},
  publisher={[Publisher]}
}
