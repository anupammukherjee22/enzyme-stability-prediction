## Enzyme Stability Prediction using Huber Regression

This project aims to predict the thermal stability (melting temperature, Tm) of protein enzymes using machine learning. The model is built using **Huber Regression**, a robust algorithm suited for noisy biochemical data. It uses sequence-derived features like amino acid composition, gravy score, aromaticity, charge, and sequence length. The model provides a faster and cost-effective alternative to traditional lab methods like Differential Scanning Calorimetry (DSC), with applications in drug discovery, protein engineering, and molecular biology.

---

### Files Included

- `model.ipynb` — End-to-end notebook with data cleaning, feature engineering, model training, and evaluation.
- `train.csv`, `test.csv`, `train_updates_20220929.csv`, `test_labels.csv` — Protein sequence data and labels.
- `Report.pdf` — Project report explaining the methodology, results, and conclusions in detail.

---

### Algorithm Used

- Huber Regression

---

### Features Engineered

- Amino acid composition
- Sequence length
- Charge at pH 7
- Aromaticity
- Isoelectric point
- Gravy (hydropathy index)

---

### Evaluation Metrics

- Mean Absolute Error (MAE): **7.46**
- Mean Squared Error (MSE): **78.75**
- R² Score

---

### Author

**Anupam Mukherjee**  
📧 anupammukherjee2003@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/anupammukherjee03)
