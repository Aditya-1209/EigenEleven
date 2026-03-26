### Sports Performance Analyzer and Player Recommendation System Using a Linear Algebra Pipeline


---

## 📌 Problem Statement

Sports teams and analysts need to evaluate player performance, predict missing stats,
and identify playing styles from raw data. This project builds a end-to-end Linear 
Algebra pipeline that takes raw cricket/football player statistics and produces 
meaningful insights — similar players, predicted performance, and dominant playing styles.

---

## 🔢 Linear Algebra Pipeline

| Step | Concept | What We Do |
|------|---------|------------|
| 1 | Matrix Representation | Player stats → Matrix A (players × features) |
| 2 | Matrix Simplification | RREF to find independent stat patterns |
| 3 | Structure of the Space | Rank, nullity, column & null space analysis |
| 4 | Remove Redundancy | Linear independence → select basis stats |
| 5 | Orthogonalization | Gram–Schmidt to create clean performance factors |
| 6 | Projection | Project partial player data onto performance subspace |
| 7 | Least Squares | Predict missing player stats |
| 8 | Pattern Discovery | Eigenvalues to find dominant playing styles |
| 9 | System Simplification | Diagonalization for final reduced model |

---

## 📁 Project Structure
```
EigenEleven/
│
├── data/               # Raw dataset (CSV files)
├── src/
│   ├── step1_matrix.py
│   ├── step2_rref.py
│   ├── step3_spaces.py
│   ├── step4_independence.py
│   ├── step5_gramschmidt.py
│   ├── step6_projection.py
│   ├── step7_leastsquares.py
│   ├── step8_eigenvalues.py
│   └── step9_diagonalization.py
├── main.py
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
python main.py
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
- Akshath Girish Shirolkar
- Akshay Gudur

---

## 📊 Dataset

We use IPL / FIFA player statistics available on
[Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/ipl-player-performance-dataset).

---
