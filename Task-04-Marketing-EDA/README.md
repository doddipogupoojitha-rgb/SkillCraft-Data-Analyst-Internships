# TASK 04: Business Insights Report (EDA) - Marketing Campaign

### Intern ID: SCT/OCT26/5217
### Name: Doddipogu Poojitha
### Company: SkillCraft Technology

### Objective (from Task Sheet):
Perform Exploratory Data Analysis (EDA) on a marketing campaign dataset.
Instead of building a Machine Learning model, focus on the 'Why'. Clean the data, visualize the funnel, and write a 1-page summary report recommending which marketing channels should receive more budget based on ROI.

### Dataset: Marketing Campaign Dataset

### Tools Used:
- Python - Pandas, NumPy for Data Cleaning
- Matplotlib, Seaborn for Visualization
- Power BI for Dashboard

### EDA Process:
1. Data Cleaning - Removed nulls, duplicates, converted dates
2. Funnel Analysis - Awareness (10,000) -> Interest (4,200) -> Conversion (1,400) -> Purchase (450)
3. ROI Calculation by Channel
4. Budget vs Revenue Analysis

### Key Insights:
- Total Budget: $120K | Total Revenue: $158.4K | Overall ROI: 32%
- Instagram ROI 35% - Highest performing channel
- Facebook 22%, Google 18%, Email 8% (Lowest)
- Marketing Funnel Drop: 42% Awareness to Interest

### 1-Page Business Summary Report:
Based on EDA, Instagram delivers highest ROI at 35%, outperforming other channels by +13pp vs Facebook. 
**Recommendation:** Reallocate budget from Email (lowest 8% ROI) to Instagram to maximize return and scale conversions.
**Projected Impact:** +22% overall ROI if implemented.

### Files in this folder:
- marketing_eda.ipynb (Python EDA Code)
- marketing_campaign.csv (Dataset)
- Dashboard_Image.png
- Business_Report.pdf (1-Page Summary)

### Dashboard Preview:
![Dashboard](Dashboard_Image.png)
