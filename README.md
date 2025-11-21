# Marketing-ROI-Analysis-for-FreshBites

### 📘 1. Business Overview

FreshBites is a snack & beverage brand operating across four regions. Over six months, they invested in Email, Social Media, and In-Store campaigns. This analysis evaluates which channels and regions performed best in engagement, conversions, and ROI.

### 📊 2. Dataset

📎 [Dataset:](https://docs.google.com/spreadsheets/d/1wPQ-JPX7bdm6bEROPsFGYeUQ1XVqWStX/edit?usp=sharing&ouid=111705402339782691602&rtpof=true&sd=true)

|    Column    |                  Description                         |
|--------------|------------------------------------------------------|
|Month	      |  Month of campaign (e.g., Jan–Jun)                   |
|Region	      |  Region where the campaign ran                       |
|Channel	      |  Marketing channel (Email, Social Media, In-Store)   |
|Impressions	|  Total reach for the campaign                        |
|Clicks	      |  User engagement actions                             |
|Conversions	|  Number of users who completed a purchase            |
|Spend	      |  Total marketing budget spent                        |
|Revenue	      |  Sales generated from the campaign                   |

##### 📌 *Dataset Notes*
* The file contains dirty data such as typos, inconsistent formatting, and spacing issues.
* Several values required standardization before analysis.

### 🧹 3. Data Cleaning Steps

To ensure accurate analysis and reporting, the following cleaning steps were performed in Excel:
 
#### 1. Removed Formatting & Unnecessary Characters
* Removed extra spaces before/after text using:
  ##### =TRIM(A2)
* Removed symbols from numeric columns (e.g., $ in Spend/Revenue).
  
#### 2. Corrected Typos and Inconsistent Labels

* Fixed region spelling errors (e.g., S0uth → South).
* Corrected incorrect month names (Jn → Jan).
* Standardized all channels to:
  =Email=
  ii.  Social Media,
  iii. In-Store
  
3. Standardized Text Case
Converted categories to Proper Case to prevent duplicates (Excel function: =PROPER(A2)).
4. Checked for & Removed Duplicates
Used: Data → Remove Duplicates
Ensured only unique campaign rows remained.
5. Verified Data Types
Ensured numeric fields (Impressions, Clicks, Spend, Revenue) were formatted as numbers.
Ensured Month and Region were formatted as text categories.
6. Calculated New Analytical Metrics
These were added as new columns:
CTR (Click-Through Rate)
=Clicks / Impressions
CVR (Conversion Rate)
=Conversions / Clicks
ROI (Return on Investment)
=(Revenue - Spend) / Spend
These metrics helped reveal trends in channel efficiency, regional performance, and overall campaign profitability.




📈 5. Tools Used
List the tools clearly:
Excel — data cleaning, formulas, pivot tables
PowerPoint — presentation design
GitHub — version control + project tracking
Optional:
Power BI / Tableau (if used)
📐 6. Key Metrics Calculated
Recruiters LOVE seeing formulas.
Use this format:
CTR (Click-Through Rate) = Clicks ÷ Impressions
Conversion Rate (CVR) = Conversions ÷ Clicks
ROI = (Revenue − Spend) ÷ Spend
Engagement Rate = Clicks ÷ Impressions
You can even paste your Excel formulas:
=Clicks/Impressions
=(Revenue-Spend)/Spend
=Conversions/Clicks
📊 7. Analysis & Insights
Write short, bullet-style insights:
Channel Performance
Social Media → highest conversion efficiency (26.6%)
Email → highest total engagement & conversions
In-Store → highest ROI ($1 → $9.41 return)
Regional Performance
East → strongest ROI
South → most active audience
North → underperforming
Monthly Trends
February → highest conversion rate
March → highest engagement (CTR)
🎨 8. Visualizations
Instead of screenshots, you can upload your charts inside a /charts folder.
Structure:
/charts
   - roi_by_channel.png
   - conversion_rate_monthly.png
   - regional_performance.png
Then display them in the README:
### ROI by Channel
![ROI by Channel](charts/roi_by_channel.png)
I can help you create PNGs from your PPT if needed.
📝 9. Final Presentation
Attach the final slide deck here:
📎 Presentation: [FreshBites Presentation](/mnt/data/F&B (Food & Beverage) Business Plan by Slidesgo.pptx)
This shows you know how to turn data → insights → recommendations.
💡 10. Recommendations
Make them short and strong:
Increase budget for East + South (high ROI + strong activity)
Improve Email targeting to match Social Media efficiency
Push In-store campaigns during Feb–Mar (peak season)
📁 11. Project Folder Structure
Display this so your repo looks organized:
FreshBites-Marketing-Analysis/
│
├── README.md  
├── data/
│   └── FreshBites_Dataset.xlsx
├── docs/
│   └── Evaluating Marketing ROI at FreshBites_ Email vs.docx
├── visuals/
│   └── charts.png (optional)
└── presentation/
    └── F&B Business Plan by Slidesgo.pptx
