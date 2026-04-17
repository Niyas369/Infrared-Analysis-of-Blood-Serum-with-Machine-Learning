# 🔬 Infrared Analysis of Blood Serum with Machine Learning

**MSc Data Science Thesis — University of York (2024)**

---

## 📋 Overview
This project applies machine learning to predict protein secondary structure 
(α-helix and β-sheet content) from Two-Dimensional Infrared (2D-IR) spectroscopy 
data of blood serum samples.

The focus was on building interpretable, efficient ML pipelines that can support 
biomedical screening — with a long-term vision toward low-resource, on-device 
diagnostic systems.

---

## 📊 Results

| Model | Metric | Score |
|-------|--------|-------|
| Random Forest | R² | **0.99** |
| RBF-SVM | MSE | **0.21** |
| Neural Network | R² | 0.94 |

---

## 🧪 Dataset
- 8,000+ infrared spectra from blood serum samples  
- Targets: α-helix (%) and β-sheet (%) content  
- Preprocessing:
  - Denoising and baseline correction  
  - Feature extraction from spectral signatures  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Scikit-learn, NumPy, Pandas, Matplotlib  
- **Environment:** Jupyter Notebook, Git  
- **Models:** Random Forest, SVM (RBF kernel), Neural Networks  

---

## 📁 Project Structure
## 📁 Project Structure

```
data/        # Sample data (anonymised)
notebooks/   # Jupyter notebooks for analysis
models/      # Trained model files
results/     # Plots, metrics, outputs
README.md
```


---

## 🔑 Key Findings
- Random Forest achieved **R² = 0.99** for α-helix prediction  
- RBF-SVM achieved **MSE = 0.21** for β-sheet estimation  
- Interpretable models provide usable insights for non-technical users  
- Pipeline designed for reproducibility and low-resource deployment  

---

## 👤 Author
**Niyas Yasin**  
MSc Data Science, University of York  

[LinkedIn](https://www.linkedin.com/in/niyas-yasin)  
[GitHub](https://github.com/Niyas369)
