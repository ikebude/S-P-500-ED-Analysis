# S&P 500 Expalanatory Data Analysis
## Background Information
# 📊 Exploratory Data Analysis of S&P 500 Companies

## 🧠 Background Information

The S&P 500 index represents the performance of 500 of the largest companies listed on U.S. stock exchanges. These companies span across major sectors of the U.S. economy and provide a comprehensive snapshot of corporate America’s financial health and market behavior.

Understanding the composition, financial metrics, and industry representation of these companies is essential for investors, analysts, and business strategists alike.

## 🎯 Project Objectives

The objective of this project is to perform an Exploratory Data Analysis (EDA) on a dataset containing information on S&P 500 companies. The goals include:

- Understanding the distribution of companies across sectors and industries.
- Analyzing key financial metrics such as market capitalization, EBITDA, revenue growth, and stock prices.
- Exploring geographical distributions of company headquarters.
- Identifying standout companies and patterns in growth, profitability, and employee size.
- Preparing insights that can inform investment decisions or further financial modeling.

## 📁 Data Description

The dataset (`sp500_companies.csv`) consists of 502 rows and 16 columns, with each row representing a publicly listed company. Below are the columns in the dataset:

| Column Name           | Description |
|-----------------------|-------------|
| `Exchange`            | Stock exchange the company is listed on |
| `Symbol`              | Stock ticker symbol |
| `Shortname`           | Short name of the company |
| `Longname`            | Full legal name of the company |
| `Sector`              | Sector of operation |
| `Industry`            | Specific industry classification |
| `Currentprice`        | Latest trading price |
| `Marketcap`           | Market capitalization (in USD) |
| `Ebitda`              | Earnings before interest, tax, depreciation, and amortization |
| `Revenuegrowth`       | Year-over-year revenue growth rate |
| `City`, `State`, `Country` | Location of company headquarters |
| `Fulltimeemployees`   | Number of full-time employees |
| `Longbusinesssummary` | Brief company profile |
| `Weight`              | Weight of the company in the S&P 500 index |

## 🛠️ Deliverables

- A well-commented Jupyter Notebook (`sp500_eda.ipynb`) containing:
  - Data cleaning and preparation
  - Univariate and bivariate visualizations
  - Summary statistics
  - Key observations
- Summary visualizations (bar charts, histograms, boxplots, etc.)
- This `README.md` file summarizing the project

## 📌 Summary of Findings

> *(To be updated after analysis)*

Here’s a preview of what we aim to uncover:
- Top 10 companies by market capitalization
- Most represented sectors and industries
- Relationships between company size, revenue growth, and profitability
- Geographical concentrations of S&P 500 companies
- Noteworthy outliers or trends in financial performance

## 💡 Key Insights (To Be Prepared)

> *(These will be added upon completing the analysis, but may include findings such as:)*

- Technology and Healthcare are the most dominant sectors.
- Companies headquartered in California contribute significantly to the index weight.
- There is a positive correlation between revenue growth and EBITDA in specific industries.
- A few companies heavily skew the overall index due to their market cap size.

---

📌 **Note**: All analysis is done using Python in a Jupyter Notebook, using libraries such as `pandas`, `matplotlib`, `seaborn`, and `plotly`.