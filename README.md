# 🔭 Flying SPAGHETTI – AN2DL Challenge 2026/2027

Image classification project for the **Artificial Neural Networks and Deep Learning (AN2DL)** course, A.Y. 2026–2027.

The goal is to classify 256×256 RGB images captured by the (fictional) SPAGHETTI-1 telescope into **10 classes**, while dealing with corrupted observations (visual artifacts, color distortions and other systematic disturbances) present in the dataset.

## **REMEMBER TO DOWNLOAD THE DATA**

---

## 👥 Team

**Group name:** `bababuba`

| Name | Student ID | GitHub |
|------|-----------|--------|
| Pedro Matusita | [matricola] | [@username] |
| Gustavo Baeta | [matricola] | [@username] |
| Lucas Lacerda | [matricola] | [@username] |
| Andre Rosenburg | [matricola] | [@username] |

---

## 📋 Task

- **Input:** 256×256 RGB images
- **Output:** one class label per image (integer from 0 to 9)
- **Metric:** weighted F1-score (each class weighted by its share of the test set)
- **Platform:** Kaggle competition
- **Deadline:** December 8, 2026, 23:59 CET

---

## 📁 Repository Structure

```
.
├── notebooks/
│   ├── 01_data_exploration.ipynb   # Dataset analysis, class distribution, corrupted image detection
│   ├── 02_baseline.ipynb           # Simple CNN baseline
│   └── 03_final_model.ipynb        # Final model: training, evaluation and submission
├── data/                            # Information provided in the challenge
├── submissions/                    # Generated .csv files for Kaggle
├── report/                         # Final report (PDF, LaTeX template)
├── requirements.txt
└── README.md
```

> ⚠️ The dataset is **not** included in this repository. Download it from the Kaggle competition page and place it in `data/`.

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/[username]/[repo-name].git
cd [repo-name]

# Install dependencies
pip install -r requirements.txt
```

Then open the notebooks in order (locally, on Google Colab or on Kaggle with GPU enabled).

---

## 🧠 Approach

1. **Data exploration** – class distribution, visual inspection, identification of corrupted/anomalous images
2. **Data cleaning** – handling of corrupted observations
3. **Baseline** – simple CNN trained from scratch
4. **Transfer learning** – pretrained backbone + fine-tuning
5. **Improvements** – data augmentation, class imbalance handling, regularization, ensembling / TTA

*(Details and results to be updated as the project progresses.)*

---

## 📊 Results

| Model | Validation F1 | Public Leaderboard F1 |
|-------|---------------|-----------------------|
| Baseline CNN | – | – |
| [Model name] | – | – |
| **Final model** | – | – |

---

## 📤 Submission Format

```
id,label
test_00000,3
test_00001,7
test_00002,0
```

---

## 📄 Report

The final report (max 3 pages, official LaTeX template) is available in [`report/`](report/).

---

## 🛠️ Tech Stack

- Python
- [TensorFlow / Keras | PyTorch]
- NumPy, Pandas, Matplotlib, scikit-learn

---

*Developed for the AN2DL course – Politecnico di Milano.*