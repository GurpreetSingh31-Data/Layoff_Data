# Layoff_Data
## MySql and Power BI Project    

## Data Cleaning
#### The data cleaning script contains several important steps that help in preparing the dataset for further analysis.  


**Creation of Staging Table**:A staging table layoffs_staging was created as a working copy of the original layoffs table to clean and modify data without affecting the original dataset.  

**Removal of Duplicates**:The script includes logic to identify and remove duplicate records based on a combination of columns like company, industry, total_laid_off, date, and other relevant fields. This ensures that each record in the dataset is unique and accurate.  

**Handling Null and Blank Values**:The script likely includes steps to handle null and blank values (though the exact handling is not detailed in the part I analyzed). This is crucial for ensuring that the data is complete and reliable for analysis.  

**Standardization and Formatting**:The script seems to have focused on standardizing and formatting the data to ensure consistency across fields like date, location, industry, etc.  

**Filtering and Aggregating Data**:The cleaned data is then filtered and aggregated by various dimensions such as company, location, industry, country, and year. This allows for insights into the total number of layoffs by these categories.  

**Advanced Queries**:More complex queries, such as rolling totals of layoffs per month, ranking companies by layoffs per year, and cumulative sums, were also included. These provide deeper insights into trends over time and the impact on specific companies or industries.  

## EDA(Exploratory Data Analysis)  
​​
#### Insights from the "Exploratory Data Analysis (EDA)" Script The EDA script provides insights by exploring trends, patterns, and anomalies in the dataset.  

**Maximum and Minimum Layoff Percentages**:The script identifies the maximum and minimum layoff percentages, which helps to understand the extremes in the data. For instance, some companies laid off nearly 100% of their workforce, indicating they went out of business or had drastic downsizing.  

**Companies with 100% Layoffs**:A specific query focuses on identifying companies where the layoff percentage was 100%, which are mostly startups that likely shut down during this period. Examples include companies that raised significant funds but still failed, such as BritishVolt and Quibi.  

**Largest Single-Day Layoffs**:The EDA script identifies the companies with the largest number of layoffs on a single day, which gives insight into the most severe layoffs. This can help identify critical incidents or economic events leading to mass layoffs.  

**Companies with the Most Total Layoffs**:The analysis reveals the top companies with the highest total layoffs over time. This is useful to identify which companies were the most impacted or made the largest workforce reductions.  

**Location-Based Layoff Analysis**:Layoffs are also grouped by location, highlighting the regions most affected by workforce reductions. This can indicate economic downturns in specific areas or sectors that are heavily concentrated in those regions.  

**Yearly Layoff Trends**:The script examines layoffs by year, which helps to understand how layoffs have trended over time. This could reveal the impact of global or regional events on employment, such as economic recessions or pandemics.  

**Industry-Specific Layoff Trends**:By grouping layoffs by industry, the script provides insights into which sectors were most impacted. This can highlight which industries faced the most challenges during the period analyzed.  

**Company Rankings by Year**:The script ranks companies by the number of layoffs each year, providing a temporal perspective on which companies led layoffs in each year. This is useful for identifying trends and shifts in company strategies or economic pressures.  

**Rolling Total of Layoffs Per Month**:A rolling total of layoffs is calculated monthly, offering a clear view of how layoffs accumulated over time. This could be indicative of trends like increasing economic stress or recovery phases.  



![Screenshot 2024-09-02 172129](https://github.com/user-attachments/assets/1d0a8563-ae5a-4f13-9cad-2c76cc27217d)    

## KEY INSIGHT  


**1)Total Layoffs and Fund Raised**: There have been 0.36 million (360,000) layoffs in total, with $1.60 million raised in funding.  

**2)Top Companies by Layoffs**:Amazon leads with the highest number of layoffs (18K), followed by Google (12K), Meta (11K), and Microsoft (10K).
Smaller companies such as Philips, Ericsson, and Uber also experienced significant layoffs.  

**3)Top Companies by Layoff Percentage**:The highest layoff percentages are seen in companies like Service, Airy Rooms, Medly, and Pollen.
The percentages range between 1.2% to 2.0%, indicating a more substantial impact on their workforce relative to their size.  

**4)Industries with the Highest Layoffs**:The Consumer industry leads with 45K layoffs, followed by Retail (44K), and Other categories like Transportation, Finance, and Healthcare.
The spread of layoffs across industries indicates a broader economic impact, with the Tech and Retail sectors being particularly affected.  

**5)Countries with the Highest Layoffs**:The United States is the most affected country with the highest number of layoffs, followed by India and the Netherlands.
The United States also has the highest layoff percentage, suggesting a significant concentration of layoffs in the region.  

**6)Monthly Layoff Trends**:The month filter in the top right suggests that this dashboard can show monthly trends. If you select different months, it would likely reveal periods with spikes in layoffs, which could correspond with economic downturns or company-specific issues.

