# 🌍 Causal Impact of Micro-Irrigation on Groundwater Depletion in India


---

## 📌 Project Overview
India faces a critical **groundwater depletion crisis**, with agriculture accounting for
**over 80% of groundwater extraction**.  
This project applies **Causal Machine Learning** to estimate the **true causal effect**
of **micro-irrigation adoption** on groundwater depletion across Indian agricultural regions.

Unlike correlation-based studies, this analysis identifies **causal impact**, making the
results **policy-relevant, interpretable, and robust**.

---

## ❓ Research Question
**Does micro-irrigation causally reduce groundwater depletion in India?**

---

## 🧠 Why Causality (Not Correlation)?
Correlation alone is misleading due to:
- Selection bias
- Confounding variables (rainfall, soil, crop patterns)
- Reverse causality (depletion may trigger adoption)

This project explicitly addresses these challenges using **modern causal inference techniques**.

---

## 🛠️ Methodology
The analysis integrates econometrics with machine learning:

- **Double Machine Learning (DML)** for unbiased causal estimation
- **Cross-fitting** to prevent overfitting
- **Fixed Effects** to control time-invariant unobserved heterogeneity
- **Clustered Robust Standard Errors** at regional level
- **Sensitivity Analysis** to test robustness against unobserved confounding

---

## 📊 Dataset
- **Type:** Panel data
- **Coverage:** Indian agricultural regions (2000–2020)
- **Key Variables:**
  - Treatment: Micro-irrigation adoption
  - Outcome: Groundwater levels
  - Controls: Rainfall, crop yield, regional indicators

---

## 🧪 Model Architecture
- **Treatment Model:** Predicts probability of micro-irrigation adoption
- **Outcome Model:** Predicts groundwater depletion
- Residuals are combined via **Double Machine Learning** to estimate the causal effect

---

## 📌 Key Findings (Causal Results)
- Micro-irrigation adoption leads to a **statistically significant reduction**
  in groundwater depletion.
- Results remain **robust under sensitivity analysis**, indicating resistance
  to unobserved confounding.
- **Policy implication:** Scaling micro-irrigation subsidies can materially
  improve long-term groundwater sustainability.

---

## 💻 Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn
- EconML
- DoubleML
- Linearmodels
- Matplotlib

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Causal-Impact-of-Micro-Irrigation-on-Groundwater-Depletion-India.git
cd Causal-Impact-of-Micro-Irrigation-on-Groundwater-Depletion-India
