# TASK 02: Data Cleaning & Preparation

**Intern ID:** SCT/OCT26/5217  
**Name:** Doddipogu Poojitha  
**Tool:** Python Pandas, Jupyter Notebook

### Objective:
Load Global Superstore dataset into Python using Pandas

### Goal Achieved:
- **Before:** 15 Missing Values, 12 Duplicates
- **After:** 0 Missing, 0 Duplicates ✅
- Converted Order Date (string -> date format)

### Code Used:
```python
1. df.isnull().sum() # Check missing
2. df.dropna() # Remove nulls
3. df.drop_duplicates() # Remove duplicates
4. pd.to_datetime(df["Order Date"]) # Date conversion
df.to_csv("Cleaned_Data.csv")
