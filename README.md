## ANUDIp-SQL-PROJECT
# Data Science Job Market Analysis

## 📌 Project Overview
This project analyzes trends in the **Data Science job market** using a dataset containing job-related attributes such as salary, experience level, employment type, remote ratio, and company location. The goal is to extract insights about salary trends, remote work patterns, and industry hiring practices.

## 📂 Dataset Information
The dataset includes the following columns:
- **work_year**: The year of the job listing.
- **experience_level**: Job experience required (`EN`: Entry, `MI`: Mid, `SE`: Senior, `EX`: Executive).
- **employment_type**: Type of employment (`FT`: Full-time, `PT`: Part-time, etc.).
- **job_title**: The role/title of the job.
- **salary**: Salary in the original currency.
- **salary_currency**: Currency in which salary is paid.
- **salary_in_usd**: Salary converted to USD for comparison.
- **employee_residence**: Country of the employee.
- **remote_ratio**: Percentage of remote work (`0`: On-site, `50`: Hybrid, `100`: Fully Remote).
- **company_location**: Country where the company is located.
- **company_size**: Company size (`S`: Small, `M`: Medium, `L`: Large).

## 📊 Key Analyses
- **Salary Trends**: Distribution of salaries by experience level and company size.
- **Remote Work Impact**: How salaries vary between on-site, hybrid, and fully remote jobs.
- **Employment Type Trends**: Differences in salaries and job count for full-time vs. part-time roles.
- **Top-Paying Job Titles**: Identifying roles with the highest average salaries.
- **Geographic Salary Comparison**: Comparing salaries across different countries.

## 🛠️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-science-job-analysis.git
   cd data-science-job-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib mysql-connector-python
   ```
3. Run the analysis script:
   ```bash
   python analysis.py
   ```

## 📈 Sample Visualizations
- Box plot of **Salary vs Experience Level**
- Bar chart of **Top 10 Job Titles by Salary**
- Heatmap of **Feature Correlations**

## 🤝 Contributing
Feel free to fork this repository, improve the analysis, and submit a pull request! 😊

## 📜 License
This project is open-source and licensed under the MIT License.

