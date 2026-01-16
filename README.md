# 🌳 Decision Tree using PlayTennis Dataset (Machine Learning)

This project demonstrates the implementation of a **Decision Tree (ID3 Algorithm)** using the classic **PlayTennis dataset**.  
The goal is to calculate **Probability, Entropy, and Information Gain** to determine the root node of a decision tree.

---

## 📌 Dataset Description

**Dataset Name:** PlayTennis  
**Total Records:** 14  
**Target Attribute:** `PlayTennis` (Yes / No)

### Attributes:
- Day
- Outlook (Sunny, Overcast, Rain)
- Temperature (Hot, Mild, Cool)
- Humidity (High, Normal)
- Wind (Weak, Strong)
- PlayTennis (Target)

---

## 📊 Class Distribution

| Class | Count | Probability |
|-----|------|------------|
| Yes | 9 | 9/14 = 0.643 |
| No  | 5 | 5/14 = 0.357 |

---

## 🧮 Entropy of Dataset

**Formula:**
Entropy(S) = - Σ p log₂(p)

markdown
Copy code

**Calculated Entropy:**
Entropy(S) = 0.94

yaml
Copy code

---

## 🔥 Information Gain Calculation

Information Gain is calculated for each attribute to select the **best split**.

### Gain Comparison Table

| Attribute | Information Gain |
|---------|------------------|
| Outlook | **0.247 (Highest)** |
| Humidity | 0.151 |
| Wind | 0.048 |
| Temperature | 0.029 |

---

## 🌟 Final Result

- **Root Node:** `Outlook`
- Reason: It has the **highest Information Gain**

---

## 🧠 Concepts Covered

- Probability calculation
- Entropy
- Information Gain
- Decision Tree (ID3 algorithm)
- Categorical data handling

---

## 🛠 Tools & Technologies

- Python
- Pandas
- Google Colab / Jupyter Notebook
- Git & GitHub

---
