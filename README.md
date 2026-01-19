# Internship Program — Data Analytics  
## Task 1 – Web Scraping  
### Project Title: Job Listings Extraction from Static HTML (2025)


### Objective
This task focuses on developing a functional web scraper to extract structured job listing data from a static HTML page. 
The main goals were to navigate raw HTML using Python, parse relevant content like job titles and companies, and transform it into a clean dataset suitable for analysis or integration.


### Dataset Overview
- **Source**: Static sample HTML page
- **Type**: Job listing data
- **Volume**: 100 job records extracted
- **Fields Extracted**:
  - Job Title  
  - Company  
  - Location  
  - Date Posted  
  - Apply Link  


### Tools & Libraries
- **Python**: Core scripting
- **BeautifulSoup**: HTML parsing and tag selection
- **requests**: Fetching HTML content
- **pandas**: Data structuring and CSV export
- **Jupyter Notebook**: Interactive coding environment
- **Chrome DevTools**: HTML structure inspection and tag identification


### Key Steps
- Inspected HTML structure using Chrome DevTools to identify relevant tags (`h2`, `h3`, `p`, `time`, `a`).
- Parsed job listings using `BeautifulSoup` and extracted key elements.
- Stored structured results in a `pandas` DataFrame.
- Exported the dataset to `fake_job_listings.csv` for future use.
- Performed basic verification using `.head()` to inspect data integrity.


### What Was Analyzed
- Basic preview of the scraped dataset using `.head()`
- Checked structure and consistency of scraped values across all 100 records
- Verified that no key fields were missing
- Ensured the scraping logic consistently extracted all necessary elements from each job listing


### Key Insights
- All 100 job listings were successfully extracted from the static HTML.
- Each record contains complete and correctly structured data, indicating accurate tag targeting.
- The scraper design is robust and modular enough to be adapted for future scraping tasks or real job boards.


### What Could Be Improved
- Include pagination logic for dynamic/multi-page sites.
- Add exception handling for missing or broken tags.
- Expand the analysis to visualize hiring patterns using bar plots or word clouds.


### Files Included
- `Code_Alpha_Internship_Task_1.ipynb`: Notebook with all scraping logic and output
- `fake_job_listings.csv`: Final structured dataset created from scraped HTML
- `Data Analytics Tasks & Instructions — CodeAlpha.pdf`: Official task list and guidelines
- `Task_1_Report.docx`: A polished summary report outlining the objective, methodology, insights, and outcomes


### References
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Python requests module](https://docs.python-requests.org/en/master/)
- [W3Schools HTML Reference](https://www.w3schools.com/tags/)


### Connect With Me
If you'd like to explore this project or collaborate on data challenges, feel free to reach out:
- **LinkedIn**: [Diya Menghani](https://www.linkedin.com/in/diya-menghani-ab409031a/)
- **Email**: diyamenghani00@gmail.com


#### Tags  
#WebScraping #BeautifulSoup #Python #InternshipProject #DataExtraction #CodeAlpha
