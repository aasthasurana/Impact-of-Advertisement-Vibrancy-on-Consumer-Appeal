# Impact of Advertisement Vibrancy on Consumer Appeal

This repository contains a research project exploring how **advertisement vibrancy** and **call-to-action (CTA) elements** influence consumer appeal and engagement. The work includes a Jupyter Notebook with data cleaning, statistical analysis, and visualization, along with a full research report.

---

## 📌 Research Overview
- **Research Question:**  
  Does the vibrancy of a print advertisement influence consumer appeal, and does the addition of a call-to-action further enhance engagement?

- **Hypotheses:**  
  - *H0 (Null):* No significant difference in consumer appeal between minimalist and vibrant ads, with or without a CTA.  
  - *H1 (Alternative):* Vibrant ads increase appeal, and adding a CTA further enhances engagement.  

- **Experiment Design:**  
  - **Control Group:** Minimalist ads  
  - **Treatment 1:** Vibrant ads  
  - **Treatment 2:** Vibrant ads + CTA  
  - **Participants:** 66 respondents (BU students + international participants)  
  - **Brands Tested:** Apple, McDonald’s, Pepsi, Nike, Grey Goose, Emirates  

- **Data Collected:**  
  - Brand interaction history  
  - Appeal rating (1–10)  
  - Click likelihood (1–10)  
  - Demographics (age, gender, country)  

---

## 📊 Key Findings
- **Click Likelihood:**  
  - Vibrant ads moderately increased likelihood of clicks (**Cohen’s d = 0.35**).  
  - Adding a CTA did **not consistently improve engagement** and sometimes reduced it.  

- **Appeal Rating:**  
  - Minimal differences across designs; vibrancy and CTAs did not significantly increase perceived appeal.  

- **Demographic Insights (CATE analysis):**  
  - Effects varied by gender, age, and region.  
  - Example: Female respondents showed higher click likelihood for vibrant ads vs. CTA-enhanced ads.  

- **Regression Analysis:**  
  - Engagement was more influenced by demographics (e.g., age, gender, ad frequency) than ad vibrancy.  
  - Both treatments (vibrancy + CTA) tended to reduce appeal compared to control.  

- **Conclusion:**  
  - Vibrant ads can drive clicks but don’t necessarily enhance appeal.  
  - CTAs may not always help, sometimes lowering effectiveness.  
  - A one-size-fits-all strategy doesn’t work — ad design must be **tailored to target audience segments**.  

---

## ⚙️ Repository Contents
- `Impact of Advertisement Vibrancy on Consumer Appeal.ipynb` — Notebook with data loading, cleaning, and analysis.  
- `Report_Impact of Advertisement Vibrancy on Consumer Appeal.pdf` — Full academic-style report.  
- `BECM_Final_not_clean.csv` *(not included here, but used as the raw dataset)*.  

---

## 🛠️ Tools & Libraries
- Python: `pandas`, `scipy`, `statsmodels`  
- Data Collection: **Qualtrics survey**  
- Analysis: t-tests, Chi-square, regression, Cohen’s D, ATE/CATE  

---

## ▶️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
