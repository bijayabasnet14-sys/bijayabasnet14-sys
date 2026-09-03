# IBM Data Analytics Capstone Project

## Stack Overflow Developer Survey Analysis

This capstone project analyzes Stack Overflow Developer Survey data to identify current technology usage, future technology trends, and respondent demographics.

The project demonstrates an end-to-end data analytics workflow involving data collection, data cleaning, exploratory analysis, visualization, dashboard development, and presentation of findings. It was completed as part of the **IBM Data Analyst Professional Certificate**.

## Project Objectives

This project addresses three main questions:

1. Which programming languages, databases, platforms, and web frameworks are currently used most frequently?
2. Which technologies do developers want to use in the next year?
3. What are the demographic characteristics of survey respondents?

## Project Links

* [Interactive Google Looker Studio Dashboard](https://datastudio.google.com/reporting/3f870e80-7c7e-4e75-a936-3b14cf99c7a5)
* [Google Sheets Data and Calculations](https://docs.google.com/spreadsheets/d/1LILFEQpPUMz7QaDXLO3WLiEDMfq6RycoeBAUhnUL8lw/edit?usp=sharing)
* [Final Presentation PDF](./Presentation/IBM%20Capstone%20Project%20Final%20Presentation.pdf)
* [Final Presentation PowerPoint](./Presentation/IBM%20Capstone%20Project%20Final%20Presentation.pptx)

## Tools and Technologies

* Python
* SQL
* Pandas
* NumPy
* Jupyter Notebook
* APIs
* Web scraping
* Google Sheets
* Google Looker Studio
* Matplotlib
* Seaborn
* Microsoft Excel
* Microsoft PowerPoint
* Git and GitHub

## Project Workflow

### 1. Data Collection

Data was collected and examined using APIs, web scraping, and the Stack Overflow Developer Survey dataset.

The data-collection work included:

* Collecting job-posting data through APIs
* Exploring the survey dataset
* Scraping technology and programming-language data
* Reviewing and validating collected information
* Preparing popular-language and job-posting datasets

### 2. Data Wrangling

The survey data was cleaned and prepared by:

* Identifying duplicate records
* Removing duplicates where appropriate
* Finding missing values
* Imputing missing values
* Normalizing selected data fields
* Reviewing data distributions
* Validating data types and field consistency

Several survey questions allowed respondents to select multiple technologies. These multi-response fields were separated and summarized in Google Sheets so that each technology could be counted individually.

### 3. Exploratory Data Analysis

Exploratory analysis was performed to investigate:

* Data distributions
* Missing-value patterns
* Duplicate records
* Outliers
* Correlations
* Technology popularity
* Respondent demographics

### 4. Dashboard Development

The final visualizations were organized into three Google Looker Studio dashboard pages.

## Dashboard 1: Current Technology Usage

This dashboard presents:

* Top 10 languages currently used
* Top 10 databases currently used
* Top 10 platforms currently used
* Top 10 web frameworks currently used

### Key Insights

* JavaScript was the most commonly used programming language.
* SQL and HTML/CSS were also among the leading languages.
* TypeScript and Python remained widely used.
* PostgreSQL was the leading database.
* Amazon Web Services was the leading cloud platform.
* Node.js and React were the most frequently used web technologies.

## Dashboard 2: Future Technology Trends

This dashboard presents:

* Top 10 languages desired next year
* Top 10 databases desired next year
* Top 10 platforms desired next year
* Top 10 web frameworks desired next year

### Key Insights

* JavaScript remained the most desired programming language.
* SQL, TypeScript, HTML/CSS, and Python continued to show strong future demand.
* Go and Rust appeared among the top desired languages.
* PostgreSQL remained the leading desired database.
* Redis moved higher in the desired database rankings.
* Amazon Web Services remained the most desired platform.
* React and Node.js continued to lead desired web technologies.

## Dashboard 3: Demographics

This dashboard presents:

* Respondents by age
* Respondent count by country
* Respondent distribution by education level
* Respondent count by age classified by education level

### Key Insights

* Respondents between 25 and 34 years old represented the largest age group.
* Respondents between 35 and 44 years old formed the second-largest group.
* Approximately 68.6% of respondents were between 25 and 44 years old.
* The United States had the highest respondent count.
* Bachelor’s and master’s degrees were the most common education levels.
* Bachelor’s degree holders were especially prominent within the largest age categories.

## Selected Results

### Most-Used Programming Languages

| Rank | Programming Language | Respondent Count |
| ---: | -------------------- | ---------------: |
|    1 | JavaScript           |           14,943 |
|    2 | SQL                  |           12,602 |
|    3 | HTML/CSS             |           12,410 |
|    4 | TypeScript           |           10,709 |
|    5 | Python               |            9,590 |

### Programming Languages Desired Next Year

| Rank | Programming Language | Respondent Count |
| ---: | -------------------- | ---------------: |
|    1 | JavaScript           |           11,541 |
|    2 | SQL                  |           10,944 |
|    3 | TypeScript           |           10,437 |
|    4 | HTML/CSS             |           10,016 |
|    5 | Python               |            8,919 |

### Most-Used Databases

| Rank | Database             | Respondent Count |
| ---: | -------------------- | ---------------: |
|    1 | PostgreSQL           |           11,514 |
|    2 | MySQL                |            8,556 |
|    3 | SQLite               |            7,021 |
|    4 | MongoDB              |            5,930 |
|    5 | Microsoft SQL Server |            5,870 |

### Databases Desired Next Year

| Rank | Database   | Respondent Count |
| ---: | ---------- | ---------------: |
|    1 | PostgreSQL |           12,193 |
|    2 | Redis      |            6,384 |
|    3 | SQLite     |            6,295 |
|    4 | MySQL      |            6,204 |
|    5 | MongoDB    |            5,618 |

> Respondents could select more than one technology. Therefore, technology counts overlap and should not be treated as mutually exclusive categories.

## Repository Structure

```text
IBM Data Analytics Capstone Project
│
├── Final Dashboard/
│   ├── Dashboard screenshots
│   └── Prepared Excel dashboard workbooks
│
├── Lab Notebook/
│   ├── Module 1/
│   │   ├── API data collection
│   │   ├── Dataset exploration
│   │   └── Web scraping
│   │
│   ├── Module 2/
│   │   ├── Duplicate identification and removal
│   │   ├── Missing-value analysis
│   │   ├── Missing-value imputation
│   │   └── Data normalization
│   │
│   ├── Module 3/
│   │   ├── Exploratory data analysis
│   │   ├── Distribution analysis
│   │   ├── Outlier analysis
│   │   └── Correlation analysis
│   │
│   └── Module 4/
│       └── Data visualization
│
├── Presentation/
│   ├── Final presentation PDF
│   ├── Final presentation PowerPoint
│   └── Presentation template
│
├── files/
│   ├── API notebook
│   ├── Job-posting workbooks
│   ├── Popular-languages dataset
│   └── Supporting analysis files
│
└── README.md
```

## Data Availability

The prepared dashboard data and calculations can be viewed through the project’s [Google Sheets workbook](https://docs.google.com/spreadsheets/d/1LILFEQpPUMz7QaDXLO3WLiEDMfq6RycoeBAUhnUL8lw/edit?usp=sharing).

Some large working CSV files are not stored in this GitHub repository because they exceed GitHub’s recommended or permitted file-size limits. The repository retains the notebooks, supporting workbooks, dashboard screenshots, presentation, and smaller supporting datasets required to understand the analytical process and results.

## How to Explore the Project

1. Open the notebooks under `Lab Notebook` to review the analysis workflow.
2. Review the supporting files and workbooks under `files` and `Final Dashboard`.
3. View the prepared data through [Google Sheets](https://docs.google.com/spreadsheets/d/1LILFEQpPUMz7QaDXLO3WLiEDMfq6RycoeBAUhnUL8lw/edit?usp=sharing).
4. Explore the [interactive Looker Studio dashboard](https://datastudio.google.com/reporting/3f870e80-7c7e-4e75-a936-3b14cf99c7a5).
5. Open the final presentation under `Presentation` for the complete project summary.

GitHub may not render some large notebooks or spreadsheet files directly. If this occurs, download the file or clone the repository and open it locally.

## Conclusion

The analysis shows that established technologies continue to anchor the developer ecosystem. JavaScript, SQL, HTML/CSS, TypeScript, and Python remain central programming skills, while PostgreSQL and AWS lead their respective technology categories.

Future preferences suggest selective modernization rather than the replacement of established tools. Interest in TypeScript, Go, Rust, and Redis indicates increasing attention to application reliability, performance, cloud-native development, and high-speed data systems.

## Author

**Bijaya Basnet**

Graduate student in Technology Management with experience in data analysis, reporting, dashboard development, and scientific research.

* [LinkedIn](https://www.linkedin.com/in/bijaya-b-2a73471b4/)
* [GitHub](https://github.com/bijayabasnet14-sys)
* [Credly](https://www.credly.com/users/bijaya-basnet)
