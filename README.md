# Marketing-ROI-Analysis-for-FreshBites

### 1. Business Overview

FreshBites is a snack & beverage brand operating across four regions. Over six months, they invested in Email, Social Media, and In-Store campaigns. This analysis evaluates which channels and regions performed best in engagement, conversions, and ROI.

### 2. Dataset

[Dataset:](https://docs.google.com/spreadsheets/d/1wPQ-JPX7bdm6bEROPsFGYeUQ1XVqWStX/edit?usp=sharing&ouid=111705402339782691602&rtpof=true&sd=true)

|    Column    |                  Description                         |
|--------------|------------------------------------------------------|
|Month	      |  Month of campaign                  |
|Region	      |  Region where the campaign ran                       |
|Channel	      |  Marketing channel (Email, Social Media, In-Store)   |
|Impressions	|  Total reach for the campaign                        |
|Clicks	      |  User engagement actions                             |
|Conversions	|  Number of users who completed a purchase            |
|Spend	      |  Total marketing budget spent                        |
|Revenue	      |  Sales generated from the campaign                   |

##### *Dataset Notes*
* The file contains dirty data such as typos, inconsistent formatting, and spacing issues.
* Several values required standardization before analysis.

### 3. Data Cleaning Steps

To ensure accurate analysis and reporting, the following cleaning steps were performed in Excel:
 
#### Removed Formatting & Unnecessary Characters
* Removed extra spaces before/after text using:
  ##### =TRIM(A2)
* Removed symbols from numeric columns (e.g., $ in Spend/Revenue).
  
#### Corrected Typos and Inconsistent Labels

* Fixed region spelling errors (e.g., S0uth → South).
* Corrected incorrect month names (Jn → June).
* Standardized all channels to:
  ##### i.   Email,
  ##### ii.  Social Media,
  ##### iii. In-Store
  
#### Standardized Text Case

* Converted categories to Proper Case to prevent duplicates using :
  ##### =PROPER(A2)
  
#### Checked for & Removed Duplicates :
* selcted the data using → Control A
* Used: Data → Remove Duplicates
* Ensured only unique campaign rows remained
  
#### Verified Data Types

* Ensured numeric fields (Impressions, Clicks, Spend, Revenue) were formatted as numbers
* Ensured Month and Region were formatted as text categories

#### Calculated New Analytical Metrics (KPI's Used)

These were added as new columns:
* CTR (Click-Through Rate)
##### =Clicks / Impressions
* CVR (Conversion Rate)
##### =Conversions / Clicks
* ROI (Return on Investment)
##### =(Revenue - Spend) / Spend

---- These metrics helped reveal trends in channel efficiency, regional performance, and overall campaign profitability

### 4. Tools Used

 * Excel — data cleaning, formulas, pivot tables, Graphs (visuals)
 * PowerPoint — presentation design (insights + reccomendations )
 * GitHub — version control + project tracking

### 5. Analysis & Insights

##### Channel Performance
* Social Media → highest conversion efficiency (26.6%)
* Email → highest total engagement & conversions
* In-Store → highest ROI ($1 → $9.41 return)

![alt text](https://raw.githubusercontent.com/nnodebejudith/Marketing-ROI-Analysis-for-FreshBites/refs/heads/main/Click%20Through%20Rate%20vs%20Conversion%20Rate%20by%20Channels%20%20.jpg)
![alt text](https://raw.githubusercontent.com/nnodebejudith/Marketing-ROI-Analysis-for-FreshBites/refs/heads/main/Impressions%20by%20Channels%20.jpg)
![alt text](https://raw.githubusercontent.com/nnodebejudith/Marketing-ROI-Analysis-for-FreshBites/refs/heads/main/ROI%20By%20Channel%20%20.jpg)

##### Regional Performance
* East → strongest ROI, most efficient region
* South → most active and engaged audience
* West → balanced performance with steady returns
* North → weakest performance, needs improveme

##### Monthly Trends
* February → highest conversion rate
* March → highest engagement (CTR)

### 6. Data & Supporting Materials

Excel file : [Freshbite Data & Assets](

### 7. Final Presentation + Recommendations

Presentation: [FreshBites Presentation](https://docs.google.com/presentation/d/1NukL_XI2hUFO4Rf24UdMkg4H4HiVB93f/edit?usp=sharing&ouid=111705402339782691602&rtpof=true&sd=true)

