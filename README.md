#  A/B Test Dashboard – Gender-Based Ride Matching

This project simulates an **A/B test** for a **gender-based ride-matching feature** in a ride-share app that allows female riders to request female drivers.

The goal: explore how this feature might affect **rider safety, satisfaction, and efficiency** using data-driven analysis.

---

##  Why I Chose This Project

Safety in transportation is something everyone talks about but rarely quantifies.
I wanted to see whether a **human-centered feature** — one designed around comfort and trust — could show real statistical impact without hurting performance.

This project combines **A/B testing, data analysis, and data visualization** to connect human experience with measurable outcomes.

---

##  Experiment Setup

| Group           | Description                                | Sample Size |
| --------------- | ------------------------------------------ | ----------- |
| **A (Test)**    | Female riders could request female drivers | 5 000 rides |
| **B (Control)** | Default experience, no gender preference   | 5 000 rides |

**Total Rides:** 10 000 simulated
**Metrics Tracked:**

* Ride completion rate
* Rider satisfaction (1–5 scale)
* Average wait time (minutes)

---

##  Tools & Workflow

* **Python** – Pandas, NumPy, Matplotlib for data simulation & analysis
* **SQL (SQLite/PostgreSQL)** – Aggregations and summaries
* **Tableau Desktop / Public** – Dashboard creation & visualization
* **Excel** – Quick validation and cross-checks

---

##  Dashboard Preview

![Dashboard Screenshot 1](ABtestRideshare1.png)
![Dashboard Screenshot 2](ABtestRideshare2.png)

➡️ **[Download Tableau Dashboard (.twbx)](ABtestGenderRideshare.twbx)**
*(Open in Tableau Desktop or the free Tableau Reader to explore interactively.)*

---

##  Key Findings

* **Ride Completion**

  * Control ≈ 90 %
  * Test ≈ 95 %
  * ✅ +4–5 pp increase — strongest among female riders

* **Rider Satisfaction**

  * Control = 4.2
  * Test = 4.3
  * ✅ Slight but consistent improvement in comfort perception

* **Wait Times**

  * ≈ 5.7 minutes in both groups
  * ✅ No slowdown introduced by matching filter

* **Correlation Insight**

  * Minimal link between wait time and satisfaction; riders valued comfort & safety over small time differences.

---

##  Takeaway

The simulated test shows that gender-based ride matching can improve safety perception and rider satisfaction without sacrificing efficiency — a small product change with a measurable, meaningful impact.
