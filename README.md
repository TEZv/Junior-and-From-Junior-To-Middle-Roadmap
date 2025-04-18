# 📊 Data Analyst Roadmap: Newbie to Junior-Level 
[by Digital Kosatiks | Oksana Kolisnyk Edition]

*Streamlined foundational program with deep practical focus - "Learn to walk before you fly!"* ✨

---

# >> Table of Contents

## 🌟 Foundational Modules
1. **[Module 0: Analytics Essentials](#-module-0-analytics-essentials)**  
   - Data types & measurement  
   - Bias detection & validity  
   - Practical: Spotify Wrapped analysis

2. **[Module 1: Statistics Deep Dive](#-module-1-statistics-deep-dive)**  
   - Probability theory (Bayes)  
   - Inferential statistics (CLT, p-values)  
   - Practical: Titanic survival analysis

3. **[Module 1.5: Statistical Methods](#-module-15-statistical-methods-mastery)**  
   - Categorical data (χ²)  
   - Regression & ANCOVA  
   - Practical: Salary analysis

## 💻 Technical Skills
4. **[Module 2: Python for DA](#-module-2-python-for-da-jedi)**  
   - Pandas/NumPy mastery  
   - Data cleaning techniques  
   - Practical: Spotify song analysis

5. **[Module 3: SQL](#-module-3-sql---the-data-language)**  
   - Joins & subqueries  
   - Query optimization  
   - Practical: SQL Murder Mystery

6. **[Module 4: ML Basics](#-module-4-ml-for-humans)**  
   - Linear/logistic regression  
   - Gradient descent  
   - Practical: Exam pass prediction

## 📊 Business Applications
7. **[Module 5: Business Analytics](#-module-5-business-analytics)**  
   - A/B testing & metrics  
   - Quality management  
   - Practical: Store optimization

8. **[Module 5.5: Research Design](#-module-55-research--critical-analysis)**  
   - Experimental vs observational  
   - Statistical criticism  
   - Practical: Study debunking

## 🛠️ Professional Skills
9. **[Module 6: Git & Workflow](#-module-6-git--workflow)**  
   - Version control best practices  
   - Practical: GitHub repo creation

10. **[Module 7: Data Ethics](#-module-7-data-governance--ethics)**  
    - Privacy & compliance  
    - Practical: Data anonymization

11. **[Module 8: Communication](#-module-8-communication--leadership)**  
    - Statistical storytelling  
    - Executive summaries  
    - Practical: Report transformation

## 🏁 Final Project
12. **[Capstone Project](#-final-project)**  
    - COVID-19 data analysis  
    - SQL + Python + business recs  
    - Rubber duck presentation 🦆

## 📖 Appendices
- [Resources](#-resources)  
- [Integration Map](#-integration-map-of-modules)  
- [Difficulty Legend](#-legend)

---

## 🌟 **Module 0: Analytics Essentials**  
### Theory & Jokes  
  - "Data analytics is like being a translator 🔡 - you turn numbers into business decisions!"
  - "Analytics is like being a detective 🕵️♂️, but for business mysteries!"  
### **Key Foundations**
  - Data types (Nominal/Ordinal/Interval/Ratio)  
  - Bias types (Sampling, Confirmation) → "Confirmation bias is why horoscopes 'work'" ♋  
  - Reliability (Cronbach's α) vs. Validity → "A reliable scale weighs you the same daily; valid scale shows your real weight 🏋️♂️" / "Does this thermometer measure *temperature* or just *length*?"

### ⁉️**Must-Know**
  - **Validity ≠ Reliability**: "A broken clock is reliable (shows same time) but not valid!"
  - **Ordinal Trap**: "Never calculate means from star ratings ⭐⭐⭐⭐"

### Practical  
- **Task 1**: Analyze your Spotify Wrapped data → Find 3 biases in their yearly summary  
- **Task 2**: Calculate "Coffee Productivity Ratio" ☕📈 = (Tasks completed)/(Cups consumed)  

### 📚 Resources

---

## 📈 **Module 1: Statistics Deep Dive**  
### Core Concepts  
- **Probability Theory**  
  - **Bayes' Theorem**: Prior/Posterior Probabilities
  - **Practice**: Calculate spam email probability given keyword triggers  

- **Inferential Statistics**  
  - **Central Limit Theorem** demo with cookie prices 🍪  
  - **Hypothesis Testing**: "Is your coworker's coin toss *really* fair?" → "P-values: Not a measure of truth, just weirdness"
  - Nonparametric Tests (Wilcoxon, Kruskal-Wallis)
  - Time Series Analysis (ARIMA, Seasonality)
  - Power Analysis (Sample Size Calculation)
  - Effect Sizes (Cohen’s d, Odds Ratio)
 
- **Edge Cases**  
  - Time Series Analysis (ARIMA, Seasonality)
    
     *Note: While time series is often considered its own domain,
    ARIMA modeling involves inferring future trends from historical data, making it partially inferential.*  

   **Exploratory data analysis (EDA)**
    - Descriptive stats (Mean/Median/Mode) → "The 3 Musketeers of Central Tendency!"  
 
### ⁉️**Must-Know**  
  - **CLT Magic**: "30+ samples make any distribution normal-ish!"  
  - **P-Value Truth**: "It's the probability of data GIVEN null hypothesis, not vice versa"
  - Central Limit Theorem → "Why 30 samples is the magic number 🎱"  
  - Bayesian Basics → "Updating beliefs like a poker player 🃏"

### Practical  
- **Dataset**: [Titanic Survival Data](https://www.kaggle.com/c/titanic)  
- **Task**:  
  1. Calculate survival probability for 1st vs 3rd class  
  2. Make a 1-min TikTok-style explainer 📱 ("Why rich people survived? 💰")  

### 📚 Resources

---

## 🔬 **Module 1.5: Statistical Methods Mastery**  
### Theory  
- **Categorical Data Analysis**  
  - χ² Test: "Do cats 🐈⬛ prefer boxes by color?"  
  - Likert Scales: "When 'Strongly Agree' needs a number"  

- **Regression & ANOVA**  
  - ANCOVA: "Controlling for caffeine intake in productivity studies ☕"  
  - Polynomial Regression: "When relationships aren't straight-laced"  

### ⁉️**Must-Know**  
  - **Chi-Squared Limitation**: "Never use with expected counts <5"  
  - **ANCOVA Secret**: "Always check homogeneity of slopes first"

### Practical  
- **Task**: Analyze salary differences by education level *while controlling for age*  

### 📚 Resources

---

## 🐍 **Module 2: Python for DA Jedi**  
### Lightsaber Skills ⚔️  
- Pandas (🐼 Mastery) 
  - "Merge datasets like arranging a wedding 👰♀️🤵♂️"  
  - Handle missing data → "NaN is not your friend. Use `.fillna()`!"  
### **Key Libraries**  
  - NumPy → "Math magic for arrays 🎩"  
  - Matplotlib → "Make charts even your grandma understands 👵"  

### ⁉️**Must-Know**
  - **NaN Danger**: ".isna().sum() first, ask questions later"  
  - **Merge Types**: "Inner vs outer joins = Venn diagram logic 🔵🔴"

### Practical  
- **Project**: Analyze [Spotify Top Songs](https://www.kaggle.com/leonardopena/top-spotify-songs-2023)  
  - Task: Find why Ed Sheeran's songs are longer than Taylor Swift's 🎤  
  - Joke Requirement: Add "🐍 Snake Plot" title if using Python  

### 📚 Resources

---

## 🗃️ **Module 3: SQL - The Data Language**  
### Talk Like a Pro  
- `SELECT * FROM life WHERE happiness > 8 😎`  
### **Focus Areas**
  - Joins → "Venn diagrams with data 🟢🔵"  
  - Subqueries → "Queries within queries, like Inception 🌀"

### ⁉️**Must-Know**
  - **JOIN Logic**: "LEFT JOIN keeps all orphans from the left table"  
  - **WHERE vs HAVING**: "Filter before vs after aggregation"

### Practical  
- **Simulator**: [SQL Murder Mystery](https://mystery.knightlab.com/) 🕵️♂️  
- **Task**: Solve 3 cases → Screenshot your solutions with emoji reactions 🎉

### 📚 Resources

---

## 🤖 **Module 4: ML for Humans**  
### No-BS Theory  
- Linear Regression
  - "It's just y=mx+b from school... but with matrices 🧮"  
  - Cost Function → "Penalty for wrong predictions ❌"  
  - Gradient Descent → "Rolling down a hill to find the best slope 🏔️"  
- Logistic Regression  
  - "When your outcome is yes/no → Use sigmoid magic 🎲"  

### ⁉️**Must-Know**
  - **Overfitting Sign**: "Training accuracy >> test accuracy"  
  - **Gradient Descent**: "Learning rate = step size down the hill"

### Practical  
- **Task 1**: Manually calculate the slope for 5 data points (pen/paper allowed!)  
- **Task 2**: Predict exam pass/fail using [Student Performance Data](https://www.kaggle.com/datasets/whenamancodes/student-performance)  

### 📚 Resources

---

## 📉 **Module 5: Business Analytics**  
### Real-World Skills
- **Quality Management**  
  - Control charts: "Is this month's sales drop normal or alarming?"  
  - Risk vs Odds: "Why 80% success ≠ 20% failure"

- A/B Testing → "Is the red button better than blue? 🟥🟦"  
### **Metrics Mastery**:  
  - ROI → "Money earned ÷ money spent 💵"  
  - CTR → "How many clicked your cat meme 🐈⬛"  

### ⁉️**Must-Know**
  - **CTR Reality**: "2% is great for banners, terrible for emails"  
  - **A/B Test Sin**: "Never stop early based on interim results"

### Practical  
- **Project**: Optimize [Google Merchandise Store](https://support.google.com/analytics/answer/6367342)  
  - Task: Increase sales by 10% using only 3 dashboard changes  
  - Present findings as a 3-panel comic strip 🎨  

### 📚 Resources

---

## 🔍 **Module 5.5: Research & Critical Analysis**  
### Theory  
- **Study Design**  
  - Experimental vs Observational: "Lab coats 🥼 vs binoculars 🔭"  
  - Confounding variables: "The hidden puppeteers of data"  

- **Statistical Criticism**  
  - Spotting p-hacking: "When researchers cheat like gamers 🎮"  

### Practical 
- Debunk a news headline: "Study shows chocolate causes Nobel Prizes 🍫🏆"  

### ⁉️**Must-Know**
  - **Confounding Rule**: "If it affects both X & Y, it's a confounder"  
  - **P-Hacking Red Flag**: "Multiple hypothesis testing without correction"

### 📚 Resources

---

## 🛠️ **Module 6: Git & Workflow**  
### Survival Skills  
- `git commit -m "Fixed everything 🔧"` → (Never do this!)  
- **Golden Rules**
  - Commit often → "Like saving a video game 🎮"  
  - Write meaningful messages → "No 'stuff' or 'things'"  

### ⁉️**Must-Know** 
  - **Commit Philosophy**: "Atomic commits = one change per commit"  
  - **Message Rule**: "Verbs first: 'Add' not 'Added'"

### Practical  
- **Task**: Create GitHub repo with your Titanic analysis → Get 3 stars ⭐ from friends  

### 📚 Resources

---

## 🔒 Module 7: Data Governance & Ethics
### Theory
- Data Privacy (Pseudonymization, k-Anonymity)
- Compliance (HIPAA, CCPA)
- Metadata Management (Data Catalogs)
- Audit Trails
- AI Ethics (Fairness, Accountability)

### ⁉️**Must-Know** 
  - **Pseudonymization**: "Reversible vs irreversible transforms"  
  - **HIPAA Basics**: "Never store SSNs with diagnoses"

### Practical 
Anonymize a dataset of patient records (use hashing and generalization).

### 📚 Resources

---

## 🗣️ Module 8: Communication & Leadership
### Theory
- **Statistical Storytelling**  
  - "Make ANOVA results exciting like a Netflix plot 📺"  
- **Psychometrics**  
  - Standardized scores: "Why 'top 10%' beats '80 points'"
    
- Stakeholder Mapping
- Data Storytelling (Story Arc, Hero’s Journey)
- Executive Summaries
- Change Management
- Mentorship

### ⁉️**Must-Know**
  - **Exec Summary Rule**: "One insight per slide + dollar impact"  
  - **Meme Wisdom**: "Humor increases recall by 40% (citation needed 😉)"

### Practical 
Turn a technical ML report into a 3-slide exec summary with a meme on slide 2.

### 📚 Resources

---

## 🧩 Integration Map of Modules

| Theme                       | Your Module       | Key Additions                                | Practical Task Example                          | Difficulty |
|-----------------------------|-------------------|----------------------------------------------|-------------------------------------------------|------------|
| **Measurement Fundamentals** | Module 0          | Validity/reliability metrics                 | Audit Spotify Wrapped for measurement bias      | ⭐          |
| **Probability Theory**       | Module 1          | Bayes' Theorem games                         | Calculate spam probability given keywords       | ⭐⭐        |
| **Inferential Statistics**   | Module 1          | CLT visualizations                           | Cookie price sampling simulation 🍪             | ⭐⭐        |
| **Categorical Data Analysis**| Module 1.5        | Chi-squared case study                       | Test if cat color 🐈⬛ affects box preference    | ⭐⭐        |
| **ANOVA/Regression**         | Module 1.5        | ANCOVA with Python                           | Salary analysis controlling for age             | ⭐⭐⭐       |
| **Python Data Management**   | Module 2          | Missing data handling + codebooks            | Analyze Spotify song lengths (🐍 Snake Plot)    | ⭐⭐        |
| **SQL Query Mastery**        | Module 3          | Joins/Subqueries as Inception 🌀             | Solve SQL Murder Mystery cases 🕵️♂️            | ⭐⭐        |
| **ML Basics**                | Module 4          | Gradient descent visualization 🏔️           | Predict exam pass/fail with logistic regression  | ⭐⭐⭐       |
| **Business Metrics**         | Module 5          | A/B testing + ROI/CTR focus                  | Optimize Google Merchandise Store (comic strip)  | ⭐⭐        |
| **Research Design**          | Module 5.5        | Experimental vs observational studies        | Design mock A/B test (🟥 vs 🟦 buttons)         | ⭐⭐⭐       |
| **Statistical Criticism**    | Module 5.5        | P-hacking detection                          | Debunk "Chocolate = Nobel Prizes" study 🍫🏆     | ⭐⭐⭐       |
| **Git Workflow**             | Module 6          | Meaningful commit messages                   | Titanic analysis repo with 3 stars ⭐           | ⭐          |
| **Data Ethics**              | Module 7          | Pseudonymization techniques                  | Anonymize patient records 🏥                    | ⭐⭐        |
| **Statistical Storytelling** | Module 8          | Netflix-style ANOVA explanations 📺          | Turn ML report into 3-slide meme summary        | ⭐⭐        |

### 📌 Legend  
- 🐈⬛ = Categorical data task  
- 🍪 = Simulated dataset  
- 🟥/🟦 = A/B testing  
- 🍫 = Critical analysis case  
- ⭐ = Foundational  
- ⭐⭐ = Intermediate  
- ⭐⭐⭐ = Advanced  

### 💡 Pro Tip:  
Use `> [!NOTE]` for important callouts:  
> [!NOTE]  
> **Module 1.5** (ANCOVA) requires Python + stats basics from Modules 1-2.  
> **Module 5.5** is best taken after completing Modules 1-5.

## 🎯 **Final Project**  
**Build a Portfolio Piece**:  
1. **Dataset**: [COVID-19 Data](https://ourworldindata.org/covid-deaths)  
2. **Requirements**:  
   - 1 SQL query with JOIN  
   - 1 Python visualization  
   - 1 Business recommendation ("If I were CEO...")  
3. **Presentation**: Explain to a rubber duck 🦆 (video optional!)  

---

### 📚 **Resources**  
- **Math for ML**: [3Blue1Brown's Essence of Calculus](https://www.3blue1brown.com/topics/calculus)  
- **SQL Fun**: [SQL Island Game](https://sql-island.informatik.uni-kl.de/)
- Roadmaps:
  - [Raccomandazione principale](https://cdn.codewithmosh.com/image/upload/v1722374155/guides/data-analyst-roadmap.pdf)
  - [YouTube Raccomandazione](https://www.youtube.com/watch?v=gQRYqlFQNK8)
     - [GitHub Raccomandazione 1](https://github.com/mrankitgupta/Data-Analyst-Roadmap)
     - [GitHub Raccomandazione 2](https://github.com/mtahiraslan/data-analyst-roadmap)
     - [GitHub Raccomandazione 3](https://roadmap.sh/data-analyst)
     - [GitHub Raccomandazione 4](https://github.com/krishnaik06/Data-Analyst-Roadmap)
     - [GitHub Raccomandazione 5](https://github.com/rishabhnmishra/YouTube-Resources/blob/main/Data%20Analyst%20Roadmap%20by%20Rishabh%20Mishra.pdf)
     - [GitHub Raccomandazione 6](https://github.com/ezsudeep/data-analyst)
     - [GitHub Raccomandazione 7](https://github.com/andresvourakis/free-6-week-sql-roadmap-data-science)
     
  - **1 Non-Funny Joke**: Why did the data analyst break up with Excel? Because they wanted a *relation*ship! 💔
  - **2 Non-Funny but closer to Joke**: "Why was the SQL query sad? Too many `GROUP BY`s, no `FUNNY BY`s!" 🎉
     - [Google Docs Formattazione](https://docs.google.com/document/d/1z4ErLYlnAcwZEbXqJ9SM_AJ-AojH6kQrCU0lV_5G5Ek/edit?usp=sharing)
