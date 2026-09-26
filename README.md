# 📊 Data Analyst Capstone Project

## Developer Technology Skills Analysis

This project is the final capstone project for the **IBM Data Analyst Professional Certificate**.

The project analyzes the **Stack Overflow Developer Survey** to understand current technology usage, future technology preferences, database trends, programming language trends, and demographic patterns among developers.

The project covers the complete data analysis workflow:

**Data Collection → Data Cleaning → Data Wrangling → Exploratory Data Analysis → Visualization → Dashboard Development → Presentation**

---

## 🎯 Project Overview

Organizations need reliable information about the technologies and skills being used by developers today and the technologies developers are interested in using in the future.

This project analyzes developer survey data to answer questions such as:

* Which programming languages are most commonly used?
* Which programming languages are developers interested in using in the future?
* Which databases are currently popular?
* Which databases are expected to remain important in the future?
* Which platforms and web frameworks are commonly used?
* What technology trends can be observed from developer preferences?
* What demographic patterns exist within the survey population?

The results are presented using **Python data analysis, data visualization, IBM Cognos Analytics dashboards, and a PowerPoint presentation**.

---

## 📁 Project Structure

```text
Data-Analyst-Capstone-Project/
│
├── README.md
│
├── data/
│   └── survey_data_updated.csv
│
├── notebooks/
│   ├── data_collection.ipynb
│   ├── data_cleaning.ipynb
│   ├── exploratory_data_analysis.ipynb
│   └── data_visualization.ipynb
│
├── dashboard/
│   └── IBM_Cognos_Dashboard/
│
├── presentation/
│   └── Data_Analyst_Capstone_Project_Report.pdf
│
└── images/
    └── dashboard_screenshots/
```

> The exact folder and file names may vary depending on how the project is organized in the GitHub repository.

---

# 📚 Project Labs

The project was completed through a series of **26 hands-on labs**, covering data collection, data cleaning, exploratory analysis, visualization, dashboard development, and presentation.

## Module 1 — Data Collection

### Lab 1: Review Of Accessing APIs

Reviewed how APIs can be used to access and retrieve data programmatically.

### Lab 2: Collecting Data Using APIs

Collected data using APIs and explored how programmatic data collection can support data analysis.

### Lab 3: Review Of Web Scraping

Reviewed web scraping concepts and techniques for collecting information from websites.

### Lab 4: Collecting Data Using Web Scraping

Collected data using web scraping techniques and prepared the collected information for analysis.

---

# Module 2 — Exploring and Cleaning Data

### Lab 5: Exploring the Dataset

Explored the structure, variables, data types, and general characteristics of the dataset.

### Lab 6: Finding Duplicates

Identified duplicate records in the dataset.

### Lab 7: Removing Duplicates

Removed duplicate records to improve data quality and reliability.

### Lab 8: Finding Missing Values

Identified missing values across the dataset and examined their distribution.

### Lab 9: Impute Missing Values

Applied appropriate techniques to handle and impute missing values.

### Lab 10: Normalizing Data

Normalized data where necessary to make variables more suitable for analysis.

### Lab 11: Data Wrangling

Performed data transformation, restructuring, cleaning, and preparation for further analysis.

---

# Module 3 — Exploratory Data Analysis

### Lab 12: Exploratory Data Analysis

Performed exploratory data analysis to identify patterns, relationships, and characteristics within the dataset.

### Lab 13: Finding How The Data Is Distributed

Analyzed the distribution of variables using statistical and visual techniques.

### Lab 14: Finding Outliers

Identified potential outliers and examined unusual observations in the dataset.

### Lab 15: Finding Correlation

Analyzed relationships between numerical variables using correlation techniques.

---

# Module 4 — Data Visualization

### Lab 16: Data Visualization

Reviewed and applied visualization techniques to communicate data insights effectively.

### Lab 17: Histograms

Created histograms to examine the distribution of numerical variables.

### Lab 18: Box Plots

Created box plots to visualize distributions and identify potential outliers.

### Lab 19: Scatter Plot

Created scatter plots to investigate relationships between numerical variables.

### Lab 20: Bubble Plots

Created bubble plots to compare multiple dimensions of data visually.

### Lab 21: Pie Charts

Created pie charts to display proportions and categorical distributions.

### Lab 22: Stacked Charts

Created stacked charts to compare categories across groups.

### Lab 23: Line Charts

Created line charts to visualize trends and changes across categories or time.

### Lab 24: Bar Charts

Created bar charts to compare values across different categories.

---

# Module 5 — Dashboard and Presentation

### Lab 25: Building A Dashboard With IBM Cognos Analytics

Created an interactive dashboard using **IBM Cognos Analytics**.

The dashboard contains three main tabs:

### Tab 1 — Current Technology Usage

Analyzes the top technologies currently used by developers:

* Top 10 Programming Languages
* Top 10 Databases
* Top 10 Platforms
* Top 10 Web Frameworks

### Tab 2 — Future Technology Trend

Analyzes technologies developers want to use in the future:

* Top 10 Desired Programming Languages
* Top 10 Desired Databases
* Top 10 Desired Platforms
* Top 10 Desired Web Frameworks

### Tab 3 — Demographics

Analyzes demographic characteristics of survey respondents:

* Age distribution
* Respondent count by country
* Formal education level
* Age classified by education level

---

### Lab 26: PowerPoint Presentation

Created a final presentation summarizing the project methodology, findings, dashboard analysis, and conclusions.

The presentation covers:

* Project introduction
* Executive summary
* Methodology
* Programming language trends
* Database trends
* Dashboard analysis
* Findings and implications
* Overall conclusions

---

# 📊 Dataset

The primary dataset used in this project is based on the **Stack Overflow Developer Survey**.

The dataset contains information about developers, including:

* Programming languages
* Databases
* Platforms
* Web frameworks
* Education
* Age
* Country
* Technology preferences
* Other developer-related information

The analyzed dataset contains approximately:

* **18,845 responses**
* **114 variables**

Technology fields containing multiple responses were transformed so that individual technologies could be analyzed separately.

For example:

```text
Python;JavaScript;SQL
```

was processed so that:

```text
Python
JavaScript
SQL
```

could be counted individually.

---

# 🛠️ Technologies and Tools

## Programming

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite

## Data Analysis

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis
* Statistical Analysis
* Correlation Analysis
* Outlier Detection

## Data Visualization

* Histograms
* Box Plots
* Scatter Plots
* Bubble Plots
* Pie Charts
* Stacked Charts
* Line Charts
* Bar Charts

## Business Intelligence

* IBM Cognos Analytics

## Presentation

* Microsoft PowerPoint
* PDF

## Development Environment

* Jupyter Notebook
* IBM Skills Network / Coursera

---

# 🔄 Data Analysis Workflow

The overall workflow followed in this project was:

```text
1. Data Collection
        ↓
2. Data Exploration
        ↓
3. Data Cleaning
        ↓
4. Data Wrangling
        ↓
5. Exploratory Data Analysis
        ↓
6. Statistical Analysis
        ↓
7. Data Visualization
        ↓
8. IBM Cognos Dashboard
        ↓
9. Findings & Insights
        ↓
10. Final Presentation
```

---

# 🔎 Key Findings

Based on the analysis of the survey data:

### Programming Languages

JavaScript was the most frequently reported programming language in the current-usage data, followed by SQL and HTML/CSS.

Other highly represented technologies included:

* TypeScript
* Python
* Bash/Shell
* C#
* Java
* PHP
* PowerShell

The future-preference data also showed strong interest in established technologies while highlighting technologies such as **TypeScript, Go, and Rust**.

---

### Databases

The analysis showed strong representation of:

* PostgreSQL
* MySQL
* SQLite
* MongoDB
* Microsoft SQL Server

The future-preference data also showed continued interest in established databases along with technologies such as **Redis, Elasticsearch, and Supabase**.

---

### Platforms

Cloud and development platforms such as:

* AWS
* Azure
* Google Cloud
* Cloudflare
* DigitalOcean

appeared prominently in the survey data.

---

### Web Frameworks

Commonly reported web technologies included:

* Node.js
* React
* jQuery
* Express
* Next.js
* ASP.NET Core
* Angular
* Vue.js
* Spring Boot

---

# 📈 Dashboard Insights

The IBM Cognos dashboard provides three perspectives:

### Current Technology Usage

Shows technologies developers reported using currently.

### Future Technology Trend

Shows technologies developers indicated they would like to use in the future.

### Demographics

Provides context about the survey population by examining age, country, and education.

These dashboards make it easier to compare technology usage and future preferences while also understanding the demographic characteristics of respondents.

---

# 💡 Business and Industry Implications

The analysis can provide useful information for organizations interested in:

* Workforce planning
* Developer skill development
* Technology training
* Recruitment
* Technology adoption
* Curriculum planning
* Developer education

However, survey preferences should not be interpreted as direct measurements of job-market demand.

For a broader workforce analysis, survey data could be combined with:

* Job postings
* Recruitment data
* Training platforms
* Technology market data
* Industry reports

---

# ⚠️ Important Data Interpretation Note

This project is based on **developer survey responses**.

Therefore:

> **Current technology usage represents technologies reported by survey respondents, while future technology trends represent technologies respondents expressed interest in using.**

These results should not be treated as direct measurements of employment demand or job-posting requirements.

Combining developer survey data with job-market and industry data would provide a broader view of technology demand.

---

# 🎓 Learning Outcomes

Through this project, I practiced the complete data analysis lifecycle, including:

* Collecting data from APIs
* Web scraping
* Exploring datasets
* Finding and removing duplicates
* Handling missing values
* Normalizing data
* Data wrangling
* Exploratory data analysis
* Distribution analysis
* Outlier detection
* Correlation analysis
* Data visualization
* Dashboard development
* Data storytelling
* Presenting analytical findings

---

# 📌 Project Deliverables

The main deliverables of this project include:

1. **Data Collection and Analysis**
2. **Data Cleaning and Wrangling**
3. **Exploratory Data Analysis**
4. **Data Visualizations**
5. **IBM Cognos Analytics Dashboard**
6. **PowerPoint Presentation**
7. **Final PDF Report**

---

# 📊 Dashboard

The final IBM Cognos dashboard contains:

| Dashboard Tab            | Main Analysis                                                           |
| ------------------------ | ----------------------------------------------------------------------- |
| Current Technology Usage | Current programming languages, databases, platforms, and web frameworks |
| Future Technology Trend  | Desired programming languages, databases, platforms, and web frameworks |
| Demographics             | Age, country, education, and age by education                           |

---

# 📑 Final Presentation

The final presentation summarizes:

* Project objectives
* Business problem
* Data sources
* Methodology
* Data preparation
* Programming language trends
* Database trends
* Dashboard findings
* Overall findings and implications
* Conclusions

📄 **Final Report:** `Data_Analyst_Capstone_Project_Report.pdf`

---

# 👨‍💻 Author

**Kaung Htet**

Data Analyst / Software Developer

### Skills demonstrated in this project

* Python
* SQL
* Pandas
* NumPy
* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis
* Data Visualization
* IBM Cognos Analytics
* Dashboard Development
* Data Storytelling

---

# 🏆 Certification

This project was completed as part of the:

**IBM Data Analyst Professional Certificate**

The project demonstrates an end-to-end approach to collecting, cleaning, analyzing, visualizing, and communicating data-driven insights.

---

## ⭐ Project Summary

This capstone project demonstrates how raw developer survey data can be transformed into meaningful insights through a structured data analysis workflow.

**Collect → Clean → Explore → Analyze → Visualize → Dashboard → Communicate**

The project combines Python-based analysis with IBM Cognos Analytics to provide both detailed analytical work and business-friendly visualizations.
