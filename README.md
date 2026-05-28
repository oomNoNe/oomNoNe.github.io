<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>{{ page.title | default: site.title }}</title>
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
  </head>
  <body>
    <div class="wrapper">
      <header>
        <img src="{{ '/profile.jpg' | relative_url }}" 
          width="150" height="150"
          style="border-radius:50%; object-fit:cover;"/>
        <h1>{{ site.title }}</h1>
        <p>{{ site.description }}</p>
        <p>
          <a href="https://github.com/oomNoNe" target="_blank">GitHub</a><br>
          <a href="mailto:non0992727@gmail.com">non0992727@gmail.com</a>
        </p>
      </header>
      <section>
        {{ content }}
      </section>
    </div>
  </body>
</html>

**Chiang Mai University** — Economics / Data Science  
GPA: 3.23 / 4.00  
Relevant courses: Econometrics, Statistics, Financial Markets,
Machine Learning, Time Series Analysis

---

## About Me

Economics & Data Science student at Chiang Mai University
passionate about financial market analysis and ML systems.
I believe in intellectual honesty in research —
when results don't support the hypothesis, document it clearly.

Currently seeking **Data Analyst / Data Science Internship**.

---

## Technical Skills

- **Languages:** Python, SQL
- **Domain:** Econometrics, Financial Analysis, 
  Backtesting, Time Series
- **Tools:** Git, GitHub, Streamlit (basic)

---
## Work Experience

---
## Project

### 🚨 Black Swan Risk Indicator

Early-warning system for financial market crises combining:
- 📰 **FinBERT NLP** — sentiment analysis from global headlines
- 📊 **XGBoost** — 7-day VIX forecasting
- 🤖 **Regime Detector** — rule-based market mood classifier

**Key Findings:**
- ✅ Flagged COVID-19 crash **7 days early** before VIX peaked at 82.69
- 🎓 Naive baseline beat all ML models — validates Efficient Market Hypothesis
- ⚙️ Disk cache reduced build time from 60s → 8.7s (7× speedup)
- 🧪 16 pytest tests · Walk-forward CV · MLflow tracking

**Stack:** Python · XGBoost · FinBERT · Streamlit · Docker · GitHub Actions

**My role:** Problem definition, methodology design,
critical evaluation, verification & deployment

**AI-assisted:** Code scaffolding, debugging, documentation

[View on GitHub](https://github.com/oomNoNe/black-swan-indicator) · 
[Live Report](https://oomNoNe.github.io/black-swan-indicator/)

---

## Contact

- 📧 non0992727@gmail.com
- 📧 nonchaphat_ithiroj@cmu.ac.th
- 💻 [github.com/oomNoNe](https://github.com/oomNoNe)
- 🌐 [Live Project](https://oomNoNe.github.io/black-swan-indicator/)
