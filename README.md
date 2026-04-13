# 📊 Gaming & Kids: EDA on PUBG / Free Fire Impact

A responsible exploratory data analysis (EDA) notebook examining how heavy mobile gaming — specifically **PUBG** and **Free Fire** — may affect children's daily lives across key wellness dimensions.

> ⚠️ **Framing Note:** This analysis does not blame games. Its goal is to understand balance and encourage healthy digital habits.

---

## 📁 File

`pubg-free-fire-child-outcomes-data-ethics.ipynb`

---

## 🎯 Objective

Investigate potential correlations between daily gaming hours and:
- 📚 Study hours
- 😴 Sleep hours
- 😡 Aggression levels

---

## 📦 Dataset

A **synthetic dataset** of 21 child profiles, created for illustrative and ethical analysis purposes. Each record contains:

| Column | Description |
|---|---|
| `Kid_Name` | Child's name |
| `Daily_Play_Hours` | Hours spent gaming per day |
| `Study_Hours` | Hours spent studying per day |
| `Sleep_Hours` | Hours of sleep per night |
| `Aggression_Level` | Self/observer-rated aggression score (1–10) |

---

## 🛠️ Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Statistical visualizations |

---

## 🔍 Notebook Structure

| Section | Description |
|---|---|
| 1. Importing Libraries | Setup and style configuration |
| 2. Synthetic Dataset | Dataset creation and preview |
| 3. Exploratory Data Analysis | Distribution plot + scatter plot (play hours vs. study hours, colored by aggression) |
| 4. Correlation Analysis | Heatmap of correlations between all numeric variables |
| 5. Insights & Conclusion | Summary of key findings |

---

## 📈 Key Findings

- **⏱️ More gaming → less study & sleep:** Higher daily play hours are associated with reduced study and sleep time.
- **😡 Aggression rises with play hours:** A positive correlation exists between gaming duration and aggression levels.
- **⚖️ Balance is key:** Recreational gaming is fine; moderation is what matters.

---

## ✅ Ethical Stance

This notebook promotes **healthy digital habits** — not a ban on gaming. The analysis is framed to help parents, educators, and researchers understand risk factors and encourage balanced screen time for children.

---

## 🚀 How to Run

```bash
# Install dependencies if needed
pip install pandas numpy matplotlib seaborn

# Launch the notebook
jupyter notebook pubg-free-fire-child-outcomes-data-ethics.ipynb
```

> **Kernel:** Python (`python_eda` environment)
