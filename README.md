# Movie-data-analysis
## Goal
Exploratory data analysis (EDA)
## Summary 
1. Take the data from excel and use python to read it
2. Understand the data (read the columns using df.head(), and understand their data types using df.dtypes)
3. Check if there is data missing and clean it. If there is any missing data use df.dropna()
4. visualize the data using matplotlib and investigate any trends
## key challenges and solutions
1. Deciding on how to deal with missing data (delete the row or give a default value). I decided to delete the rows as default values could possibly be incorrect data.
2. Trying to extract the year released from the date released that was formatted with the date and the country. **fix:** using regex: `df['yearcorrect'] = df['released'].astype(str).str.extract(r'(\d{4})')`
## What I learned
- Learned how to use pandas and numpy to clean data
- learned how to use matplotlib to visualize data
- learned how to perform EDA (reading and cleaning data, viewing the correlation between different columns, etc.)
## Why it matters
- This demonstrates my ability to investigate data and draw insightful conclusions from it
