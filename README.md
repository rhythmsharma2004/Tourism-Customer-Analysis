# Tourism Customer Analysis
### Who buys, why they buy, and who to target next

---

## What This Project Does

A travel company was contacting customers **at random** to sell tour packages — and only **18% were buying**.

This project digs into **4,886 customer records** to find out exactly who buys, what drives the decision, and which customers the company should be calling first for their upcoming **Wellness Tourism Package** launch.

The goal isn't just EDA — it's building a targeting strategy that could lift conversion from 18% to 25%+, which on the same customer base means **38% more revenue without spending a rupee on new leads**.

---

## Key Questions Answered

- Which customer segments convert the most — and why?
- What's the ideal sales process (how many calls, how long a pitch)?
- What does the typical buyer look like for each of the 5 packages?
- Who should be targeted first for the Wellness Package?

---

## What I Found

**The best customers to target:**
Salaried Executives, age 30–45, monthly income ₹20K–₹27K, living in Tier-1 cities. They convert well above the 18% baseline.

**Passport = buying intent:**
Customers with a passport convert at nearly **2x the rate** of those without. A simple filter the sales team can apply immediately.

**Sales process sweet spot:**
3–4 follow-up calls with a 10–15 minute pitch. More calls don't help — they hurt. This alone can save significant sales team time.

**Package buyer profiles:**

| Package | Income | Age | Who They Are |
|---------|--------|-----|--------------|
| Basic | ₹17K–23K | 25–40 | Young salaried Executives, group trips |
| Standard | ₹22K–32K | 30–50 | Mid-career managers, family of 3 |
| Deluxe | ₹19K–25K | 25–45 | Married Managers, most popular segment |
| Super Deluxe | ₹27K–33K | 40–55 | AVPs, frequent travelers, Tier-1 cities |
| King | ₹33K–40K | 45–60 | VPs and above, passport holders |

**Wellness Package — recommended target:**
Salaried professionals, age 35–55, income above median, passport holders, group of 2–3.

---

## Analysis Breakdown

```
1. Data Cleaning
   - 8 columns had missing values — imputed using logical groupings
     (income by occupation+designation, age by gender+designation)
   - Fixed gender data entry error ('Fe Male' → 'Female')
   - Capped outliers using IQR — no rows deleted

2. Exploratory Data Analysis
   - Conversion rate across every demographic variable
   - Sales process effectiveness (follow-ups, pitch duration, satisfaction)
   - Correlation matrix to find real drivers vs noise

3. Customer Profiling
   - Detailed buyer profile for all 5 packages
   - Side-by-side comparison charts

4. Targeting Strategy
   - Age x Income conversion heatmap
   - Wellness segment identification with data evidence
   - 6 actionable business recommendations
```

---

## Tech Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

---

## How to Run

▶️ **Run directly in Google Colab** (no setup needed):  
[Open in Colab](https://colab.research.google.com/drive/1eWsdE79WtWfO_W-kwebaVZSadcSLCpi-?usp=sharing)

**Or run locally:**

```bash
git clone https://github.com/rhythmsharma2004/tourism-customer-analysis
cd tourism-customer-analysis
pip install pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook Tourism_Customer_Analysis.ipynb
```

> Keep `Tourism.xlsx` in the same folder as the notebook.

---

*Rhythm Sharma · IIT Jodhpur · [LinkedIn](https://www.linkedin.com/in/rhythm-sharma-433428253/) · [GitHub](https://github.com/rhythmsharma2004)*
