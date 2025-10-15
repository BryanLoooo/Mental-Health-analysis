### 📘 **README.md**

````markdown
# 🧠 Mental Health Data Analysis — Programming with Data

A comprehensive **data analytics project** investigating global and U.S. mental health trends using multiple real-world datasets.  
This analysis uses **Python, Pandas, Matplotlib, Seaborn, and BeautifulSoup** to visualize insights and understand how **age, gender, education, and environment** impact mental health.

---

## 🎯 Objectives

- Identify which **age groups** and **genders** experience higher mental health challenges.
- Analyse **state-level mental health patterns** across the United States.
- Clean and prepare messy survey datasets for accurate analysis.
- Compare **student mental health** data to national trends.
- Explore **web-scraped content** to validate findings with public reports.

---

## 🧩 Datasets Used

| Dataset Source | Description |
|----------------|-------------|
| [Data.gov - Mental Health Care in the Last 4 Weeks](https://catalog.data.gov/dataset/mental-health-care-in-the-last-4-weeks) | U.S. Department of Health and Human Services dataset from 2020. |
| [Kaggle - Student Mental Health Dataset](https://www.kaggle.com/datasets/shariful07/student-mental-health) | Student survey responses about education and mental well-being. |

---

## ⚙️ Technologies and Libraries

- **Python 3**
- **Pandas** – data cleaning and analysis  
- **Matplotlib & Seaborn** – visualization  
- **Requests & BeautifulSoup** – web scraping  
- **Regex** – validation and data filtering  
- **CSV I/O** – handling datasets efficiently

---

## 🧮 Key Processes

### 🧹 Data Cleaning
- Removed irrelevant columns (`Suppression Flag`) and null values.  
- Validated missing or illegal values using **regex**.  
- Standardized inconsistent data (e.g., gender variations like `Male`, `M`, `male`).

### 📊 Analysis
- Identified **Utah** as the U.S. state with the highest mental illness rates.  
- Discovered **18–29 years** as the age group most affected by mental health issues.  
- Found **Bachelor of Computer Science (BCS)** students (especially Year 1) exhibited the highest frequency of reported conditions.  
- Gender distribution revealed **74% male**, **24% female**, and **2% others** facing mental health challenges.

### 🌐 Web Scraping
- Used BeautifulSoup to extract confirmation data from credible sources such as **ABC4 News** and **Commonwealth Fund** to validate findings.

---

## 📈 Visualization Examples

- **Bar Graphs** — frequency of mental health cases by U.S. state.  
- **Pie Charts** — gender distribution.  
- **Line Plots** — survey participation rates by country.  
- **Countplots** — student responses for panic attacks, CGPA, and treatment-seeking behavior.

---

## 🧠 Insights and Conclusions

- The **18–29** age group showed the highest frequency of mental health issues, aligning with early adult stress factors.  
- **First-year Computer Science students** reported the greatest impact, likely due to steep academic pressure and adaptation stress.  
- Highlighted the importance of **mental health support systems** for youth and students entering higher education.

---

## 🧩 Potential Future Work

- Integrate machine learning to predict risk factors.  
- Expand datasets to include cultural and lifestyle variables.  
- Visualize global trends using geospatial heat maps.

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/BryanLoooo/Programming-with-Data-Mental-Health-Analysis.git
cd "Mental Health Data Analysis"
````

### 2. Install Dependencies

```bash
pip install pandas matplotlib seaborn requests beautifulsoup4
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Project Notebook

Navigate to:

```
Mental_Health_Analysis.ipynb
```

---
