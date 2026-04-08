# 🕷️ Naukrigulf Job Scraper

A Python-based web scraper that automates the extraction of **Data Engineer job listings** from [Naukrigulf](https://www.naukrigulf.com), collecting structured data across multiple pages and exporting it to CSV.

---

## 📸 Preview

### Website
![Naukrigulf Website](images/website.png)

### Scraped Data (DataFrame)
![DataFrame Output](images/df_output.png)

---

## ⚙️ How It Works

1. Launches a Chrome browser using **Selenium WebDriver** with anti-detection options.
2. Navigates to the Naukrigulf Data Engineer jobs page.
3. Loops through the **first 3 pages**, scraping each job card.
4. Extracts: **Job Title**, **Company**, **Experience**, **Location**, and **Description**.
5. Stores all results in a **Pandas DataFrame** and exports to `Jobs.csv`.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `selenium` | Browser automation & scraping |
| `pandas` | Data structuring & CSV export |
| `time` | Page load delays |

---

## 🚀 Getting Started

```bash
pip install selenium pandas
```

> Make sure you have **ChromeDriver** installed and compatible with your Chrome version.

Then run the notebook `scraper.ipynb` cell by cell.

---

## 📁 Output

The scraped data is saved as **`Jobs.csv`** with the following columns:

| title | company | experience | location | description |
|-------|---------|------------|----------|-------------|

---

**Created by:** ESAB &nbsp;|&nbsp; **Date:** 07-04-2026 &nbsp;|&nbsp; Digital Egypt Pioneers Initiative
