# Linkedin-Job-Scraping-and-Analysis

# Project Background

Data analysis is a systematic review process that enables informed decisions to be made by transforming raw data into meaningful information. As data has become much more widespread and important in the digital world, the search for data analysts has also increased in recent years. Since data analysts need to have many skills and programs, in this project, we have converted Linkedin job postings into csv files by web scraping using "requests" and "BeautifulSoup" in Python to examine the most needed tools for the "Data Analyst" position in Türkiye and then analyzed this data using Google Sheets.

You can reach the code used to scrape job postings in [here](linkedin_job_scraping.ipynb)
You can find the data [here](filtered_linkedin_jobs.csv)


# Information about Data

* **job_id**: Unique ID of the job
* **date**: The date job posting is scraped
* **url**: Url of the job page
* **company_name**: Name of the company that posted the ad
* **location**: Location of the job
* **day_posted**: Time passed after the job posting
* **description**: Description of the job, necessary requirements and more.
* Other columns include tools like Python, SQL, R and more that returns TRUE or FALSE values. TRUE If the job posting includes named tool; FALSE otherwise.


# Executive Summary

Based on the comprehensive web scraping analysis of LinkedIn job postings, the data analyst job market in Turkey shows a concentrated landscape with 51 total positions across 44 companies. The market is heavily centralized in Istanbul (92.2%) with strong demand for traditional data analysis tools, particularly SQL and Excel, while also showing growing adoption of modern data technologies.


## Job Market Scale

* **Total Positions**: 51 data analyst roles

* **Company Diversity**: 44 unique companies posting positions

* **Geographic Concentration**: Heavily Istanbul-focused market


# Technology Demand Analysis

The Turkish data analyst job market demonstrates a clear hierarchy of technology demands, with foundational tools dominating the landscape. SQL leads with 39 mentions (76% of positions), followed by Excel (32), Python (24), and Power BI (23), establishing these as the core skill set that defines most data analyst roles. Emerging technologies show moderate adoption, with Tableau (19), ETL processes (16), and Qlik (13) gaining traction as organizations evolve their data practices. Advanced technologies like Machine Learning, AWS, and Azure (5-8 mentions each) represent niche demands, while big data tools remain rarely requested, indicating the market hasn't yet fully embraced large-scale data processing capabilities. This distribution suggests a market still rooted in traditional analysis but gradually incorporating modern visualization and cloud technologies.


# Geographic Distribution Analysis

The data analyst job market in Turkey shows extreme geographic centralization, with Istanbul dominating 47 positions (92.2%) while Ankara and Antalya each offer only 2 positions (3.9%). This concentration reflects Istanbul's role as Turkey's financial and technological hub, where major corporations establish their data operations. The centralized nature effectively requires relocation to Istanbul for career advancement, suggesting limited remote work options and potentially contributing to talent drain from other regions. This geographic imbalance creates challenges for both job seekers outside Istanbul and companies in other cities seeking qualified data analysts.


# Competition Landscape Analysis

The data analyst job market in Turkey presents an exceptionally competitive environment, with 41 positions (80.4%) attracting over 200 applicants each, while only 1 position (2.0%) receives fewer than 25 applications. This intense competition suggests that data analysis has become a highly desirable career path, potentially driven by growth prospects and the increasing digitalization of Turkish businesses. The high application volumes indicate strong interest in the field but may also reflect a gap between the number of interested candidates and those possessing the specific technical skills employers seek. This competitive landscape requires job seekers to develop strong differentiation strategies through specialized skills and compelling application narratives to stand out among hundreds of other candidates.


# Hiring Activity Patterns

## Recent Posting Activity

The temporal distribution of job postings reveals interesting patterns in hiring activity that suggest both seasonal trends and market dynamics. Positions posted within the last week show peak activity with 14 openings, indicating either a surge in hiring demand or the natural cycle of companies refreshing their recruitment efforts. The combined 20 positions posted 2-3 weeks ago demonstrate sustained market demand, suggesting that data analyst hiring isn't merely a temporary spike but represents consistent organizational needs across multiple companies. The declining frequency of postings for positions older than 4 weeks follows normal market cycles, where older postings either get filled, expire, or companies pause their recruitment efforts to evaluate existing candidates.

## Company Hiring Behavior

The analysis of company hiring patterns reveals intriguing insights about organizational growth and talent strategies in the data analytics space. OBSS and GALIGO each show the highest activity with 3 positions posted, while sahibinden.com, Garanti BBVA Teknoloji, and DeFacto each maintain 2 active listings, indicating significant investment in data analytics capabilities. This pattern of multiple postings from single companies suggests several possible scenarios: rapid team expansion as these organizations scale their data operations, high turnover rates requiring frequent replacement hiring, or the existence of multiple specialization areas within data analyst roles that require different skill sets and experience levels. The prevalence of repeat hiring also indicates that these companies have either identified data analytics as a critical growth area requiring substantial human resources investment or are experiencing challenges in retaining data analysts, possibly due to competitive market conditions or rapid career advancement opportunities that lead to frequent departures.


# Conclusion

The Turkish data analyst job market presents a concentrated, highly competitive landscape dominated by Istanbul-based opportunities. While traditional analytical skills remain crucial, there's clear movement toward modern data science capabilities. Success in this market requires mastery of core technologies, geographic flexibility, and strategic skill development in emerging areas. The high competition levels suggest strong market interest but also indicate the need for candidates to differentiate themselves through specialized expertise and comprehensive skill sets.
