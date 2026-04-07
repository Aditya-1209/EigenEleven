### Sports Performance Analyzer and Player Recommendation System Using a Linear Algebra Pipeline

---

## 📌 Problem Statement

Sports teams and analysts need to evaluate player performance, predict missing stats,
and identify playing styles from raw data. This project builds a end-to-end Linear
Algebra pipeline that takes raw cricket/football player statistics and produces
meaningful insights — similar players, predicted performance, and dominant playing styles.

---

## 🔢 Linear Algebra Pipeline

| Step | Concept                | What We Do                                            |
| ---- | ---------------------- | ----------------------------------------------------- |
| 1    | Matrix Representation  | Player stats → Matrix A (players × features)          |
| 2    | Matrix Simplification  | RREF to find independent stat patterns                |
| 3    | Structure of the Space | Rank, nullity, column & null space analysis           |
| 4    | Remove Redundancy      | Linear independence → select basis stats              |
| 5    | Orthogonalization      | Gram–Schmidt to create clean performance factors      |
| 6    | Projection             | Project partial player data onto performance subspace |
| 7    | Least Squares          | Predict missing player stats                          |
| 8    | Pattern Discovery      | Eigenvalues to find dominant playing styles           |
| 9    | System Simplification  | Diagonalization for final reduced model               |

---

## 📁 Project Structure

```
EigenEleven/
│
├── data/
│   └── ipl_player_stats.csv        # Your downloaded Kaggle dataset
│
├── notebooks/
│   ├── step1_matrix_representation.ipynb
│   ├── step2_matrix_simplification.ipynb
│   ├── step3_structure_of_space.ipynb
│   ├── step4_remove_redundancy.ipynb
│   ├── step5_orthogonalization.ipynb
│   ├── step6_projection.ipynb
│   ├── step7_least_squares.ipynb
│   ├── step8_eigenvalues.ipynb
│   ├── step9_diagonalization.ipynb
│   └── EigenEleven_full_pipeline.ipynb   # Combined final notebook for demo
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup & Installation

```bash
# Clone the repository
git clone https://github.com/your-username/EigenEleven.git
cd EigenEleven

# Install dependencies
pip install -r requirements.txt

# Run the full pipeline
python (step).py
```

---

## 📦 Dependencies

- Python 3.8+
- numpy
- pandas
- matplotlib
- scipy

---

## 👥 Team

- Aditya Sanjay Patil
- Adithya Ajeeth

---

## 📊 Dataset

We use IPL player statistics available on
[Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/ipl-player-performance-dataset).

---
