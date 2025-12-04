# Job Market Analysis — Data Science Portfolio Project
**Entry-level / Learning Project**  

This project is part of my learning journey in Data Science. The goal is to clean, explore, and analyze a Job Market dataset to uncover trends and insights about job types, categories, salaries, experience levels, and required skills.

---

## Dataset
The dataset `job_market.csv` contains information about job postings, including:  
- Job Title, Job Type (Full-time, Part-time, Remote, etc.)  
- Category (Technology, HR, Finance, etc.)  
- Skills required  
- Salary Min & Max  
- Experience Required (years)  
- Publication Date  

The cleaned dataset `job_market_cleaned.csv` includes additional features:  
- `salary_avg` — average salary between min and max  
- `salary_range` — difference between max and min salary  
- `experience_level` — categorized experience (0-1, 2-3, 4-5, 6-10, 10+ years)  
- `num_skills` — number of skills listed  
- Normalized `job_type` and translated `job_title` to English  
- Filled missing categories based on job title keywords  

---

## Notebook
The analysis is available in `JobMarket_EDA.ipynb`, which contains:  
1. Data cleaning and preparation  
2. Feature engineering  
3. Exploratory Data Analysis (EDA) with visualizations  
4. Insights and key findings  

---

## Key Insights
- Technology and Software Development dominate the job market.  
- Jobs with higher experience levels generally offer higher salaries, but such positions are less frequent.  
- The number of skills required is positively correlated with salary.  
- HR, Finance, and niche categories are less represented in the dataset.  
- Remote jobs were properly identified and categorized for accurate analysis.  

These insights were derived through visualizations and analysis in the notebook.

---

## Dashboard & Reporting
- A **Power BI dashboard** or **Tableau dashboard** can be created using `job_market_cleaned.csv` for interactive exploration of job trends.  
- Visualizations and charts from the notebook can be exported as images for reporting purposes.  

---

## How to Run
1. Open `JobMarket_EDA.ipynb` in **Jupyter Notebook**.  
2. Ensure `job_market.csv` is in the `data/` folder.  
3. Run all cells sequentially to reproduce the cleaned dataset and visualizations.  
4. Save `job_market_cleaned.csv` for future analysis or dashboard integration.  

---

## Author
**Qusay — Data Science Portfolio Project (Entry-level / Learning Project)**  
[🔗 LinkedIn Profile](https://www.linkedin.com/in/qusay-alhasanat)  
[🔗 GitHub Profile](https://github.com/Qusay-Alhasanat)  
[📧 Email Me](mailto:qusay.alhasanat1@gmail.com)
