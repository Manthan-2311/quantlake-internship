### Day 1 - June 16, 2025

**Environment**: Google Colab / Jupyter Notebook

**What I did**:
- Created internship folder structure
- Initialized GitHub repository
- Learned Git basics (add, commit, push)
- Practiced Python basics (variables, lists, control flow)

**Challenges**:
- None so far, everything worked smoothly

**Reflection**:
- Excited to start my internship journey. Day 1 was smooth and productive!


### Day 2 - June 17, 2025

**What I learned:**
- Lists, sets, tuples, and nested dictionaries
- Writing functions like factorial and prime checker
- Using built-in modules: math, random, datetime
- Exception handling using try-except
- Solved FizzBuzz, max finder, and string reverse

**Challenges:**
- Accessing deeply nested dictionary values took a bit of thinking

**Easiest vs Hardest:**
- Easiest: FizzBuzz and reversing a string
- Hardest: Custom error handling

### Day 3 - June 18, 2025

**Dataset Used**: Iris dataset from seaborn

**What I practiced:**
- Created Series and DataFrames manually
- Loaded and explored datasets using `.info()`, `.describe()`, `.isnull()`
- Used `.loc[]`, `.iloc[]` to access rows
- Added and dropped columns
- Explored `.value_counts()`, `.unique()`, `.mean()` etc.

**What I learned:**
- Difference between Series vs DataFrame
- Filtering and sorting real-world data
- Clean way to explore a dataset using just a few Pandas methods

**Hardest Part:**
- Remembering when to use `loc[]` vs `iloc[]`


### Day 4 - June 19, 2025

**What I practiced:**
- Used `.loc[]` and `.iloc[]` to access rows and columns
- Filtered data using conditions (`&`, `|`)
- Handled missing values with `dropna()` and `fillna()`
- Grouped data using `groupby()` and `agg()`
- Merged two DataFrames using `merge()` with different join types

**Challenges:**
- Remembering join types: `inner`, `outer`, etc.
- Some columns had unexpected nulls — had to clean them manually

**What I learned:**
- How powerful groupby can be for aggregation
- How to clean messy real-world datasets before analysis

### Day 5 - June 20, 2025

**What I did:**
- Used pivot and pivot_table to summarize sales/profit
- Used melt() to flatten wide data
- Applied custom functions to classify profit margins
- Used map() and replace() to clean labels
- Combined small dataframes using concat (axis 0 and 1)

**Hardest part:** Understanding when pivot vs pivot_table is more useful  
**Learned:** How to build a mini data pipeline start to finish


### Day 6 - June 21, 2025

**What I learned:**
- Line, scatter, box, histogram, and heatmap plots
- Customizing plots with titles, labels, grids, and legends
- Seaborn makes plots simpler and more attractive

**Dataset used**: superstore.csv

**Favorite chart**: Heatmap of correlation between sales, profit, and discount


### Day 7 - June 22, 2025

**DB Used**: Chinook (music store)

**Interesting Queries:**
1. Total spent by each customer
2. Top 5 most expensive tracks
3. All customers from Canada
4. Track count per album
5. Artists with more than 5 albums

**Tools**: Used sqliteonline.com

**Reflection**: Writing SQL felt very natural after pandas! GROUP BY and WHERE feel super useful for filtering real business data.

### Day 8 - July 10, 2025

**What I Did:**
- Ran advanced SQL queries (GROUP BY, AVG, COUNT)
- Used subqueries inside SELECT
- Loaded SQL results into Pandas for analysis
- Merged Customer and Invoice tables using `pd.merge()`

**What I Learned:**
- SQL is powerful for filtering and grouping
- Pandas makes further analysis easier
- `merge()` is like JOIN in SQL


### Day 9 - July 11, 2025

**Tasks Completed:**
- Ran multi-table joins to get customer revenue
- Used window functions to rank customer orders
- Wrote CTEs to simplify average order value and 3-month filter
- Identified products with decreasing sales (business case)

**Learnings:**
- First time using `RANK()` and `DENSE_RANK()` — super powerful
- Learned how `OVER()` lets you avoid GROUP BY limitations
- CTEs improve readability in large queries

**Challenges:**
- Tracking declining trends over multiple months using SQL only was tricky

