# Naukrigulf Data Engineer Job Scraper

This project uses **Python and Selenium** to scrape **Data Engineer job listings** from the **Naukrigulf** website.

The script collects job data from the **first 3 pages** and saves it into a CSV file for analysis.

---

## 🔍 Extracted Data
For each job listing, the following information is collected:
- Job Title  
- Company Name  
- Job Location  
- Required Experience  
- Job Description (from listing page)

✅ Total extracted jobs: **90**

---

## 🛠 Tools Used
- Python  
- Selenium  
- Pandas  
- Chrome WebDriver  

---

## 📊 Sample Extracted Data
*(DataFrame preview from VS Code)*

![DataFrame Preview](/images/df_table.png)

---

## 🌐 Target Website
*(Naukrigulf – Data Engineer Jobs page)*

![Website Screenshot](./images/job_site.png)

---

## ▶️ How to Run
1. Install required libraries:
   ```bash
   pip install selenium pandas
