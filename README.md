# 🏋️‍♀️ Peak Performance Age in Female Powerlifting

## 📊 Project Overview
This project explores the age at which female powerlifters tend to reach peak performance, using publicly available data from the [Open Powerlifting database](https://www.openpowerlifting.org/), donwloaded on 05/28/25. By analyzing both **DOTS** and **Total** as performance metrics, the project investigates:

- What is the average and median age of top-performing female lifters?
- How does the choice of metric (DOTS vs Total) impact perceived peak age?
- Are there noticeable differences between **tested** and **untested** lifters in the top 1%?

---

## 🎯 Motivation
Powerlifting is a sport where peak strength does not necessarily coincide with youth. This analysis aims to demystify when women tend to hit their strongest lifts, offering insights into:
- Long-term strength development
- Gender-specific performance trends
- Scoring biases and metric selection
- Differences in competitive environments (tested vs untested)

---

## 🛠️ Methods

### Data Wrangling
- Filtered the Open Powerlifting dataset to include:
  - Female lifters
  - Non-null values for age, total, and DOTS
  - Reasonable age range (13–70)
- Added performance flags:
  - Top 1% by DOTS
  - Top 1% by Total
  - Top 1% in both
- Labeled lifters as **Tested** or **Untested** based on the `tested` column

### Analysis
- Compared mean and median ages across performance groups
- Visualized age distributions using:
  - Scatterplots
  - Boxplots
- Explored the intersection between scoring method and competition type

---

## 🔍 Key Findings
- The average age of top-performing female lifters (DOTS and Total) centers around **29–31 years old**.
- The **general population** of female lifters skews younger, with a median age around **27**.
- **Tested lifters** in the top 1% tend to be slightly **younger** than untested counterparts.
- The **choice of performance metric** (DOTS vs Total) affects who is seen as “elite” — and their average age.
- We see untested women around the 40 age range with exceptionally high DOTS scores.
- A few tested women have exceptionally high DOTS scores between the 40 and 50 age range.
- Tested women reach higher totals around or nearing the 30 age range. 


---

## 📌 Future Improvements
- Add trend analysis by year to explore shifting age patterns over time
- Refactor DOTS scoring to address known biases in female lifter coefficients
- Analyze performance by weight class and training age 

---

## 📬 Contact
Made with love and heavy deadlifts by Fabiola Velasco.  
If you'd like to connect to talk about powerlifting or to gush over how amazing Open Powerlifting is, reach out to me on IG @meatsuit5000 


