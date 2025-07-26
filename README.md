# Gender-Based Ride Matching A/B Test Simulation

**Tools Used:** Python (Jupyter), SQL, Tableau, Excel  
**Primary Skills:** A/B Testing · Experiment Simulation · Statistical Analysis · Data Visualization · Behavioral Analytics

---

## Project Overview

This project simulates an A/B test for a fictional ride-sharing platform that is testing a **gender-based ride-matching feature**: allowing female riders to request female drivers.

The goal is to measure the impact of this feature on:
-  Ride completion rates
-  Rider satisfaction scores
-  Wait times

This project is built entirely from scratch using a simulated dataset to demonstrate my ability to:
- Design A/B tests
- Generate synthetic yet realistic behavioral data
- Analyze outcomes using statistical tests
- Present insights with stakeholder-ready dashboards and summaries

---

##  Background

Gender-based ride-matching has been explored by various platforms in regions where rider safety concerns are prominent. While real-world datasets are not publicly available due to privacy concerns, I simulated a dataset to evaluate:

> “Does allowing female riders to request female drivers lead to improved ride outcomes?”

---

##  Experiment Design

- **Control Group (B):** Riders have no gender-based driver preference.
- **Test Group (A):** Female riders can opt to be matched with female drivers (80% probability).
- **Sample Size:** 10,000 simulated rides (5,000 per group)
- **Other Features:** Rider/driver gender, wait time, region, request timestamp, ride completion, satisfaction score, feedback comment

---

##  Tools & Workflow

| Step                        | Tool(s) Used                       | Description |
|----------------------------|------------------------------------|-------------|
| Data Simulation            | Python (Faker, NumPy, Pandas)      | Generated realistic ride data, timestamps, behaviors |
| Exploratory Analysis       | Jupyter Notebook                   | Summary stats, group-level trends |
| A/B Testing                | Python (SciPy, Statsmodels)        | T-tests, chi-square, effect size analysis |
| SQL Practice               | SQLite + Pandas                    | Queried key metrics by group, gender, region |
| Visualization              | Tableau                            | Built dashboards to compare A vs. B performance |
| Business Summary           | Excel                              | Created stakeholder-friendly summary with recommendations |

---

##  Key Insights

- **Higher ride completion rate** for female riders in the test group
- **Satisfaction scores** were statistically higher when female riders were matched with female drivers
- **Slightly lower wait times** in the test group, potentially due to increased comfort leading to faster ride acceptance
- **Regional differences** emerged, with suburban areas showing greater impact from the feature

---

##  What I Learned

- How to simulate complex behavioral datasets from scratch
- Designing A/B tests with control/test logic baked into generation
- Communicating experiment results to both technical and non-technical audiences
- Using multiple tools (Python, SQL, Tableau, Excel) across the full data science workflow

---
