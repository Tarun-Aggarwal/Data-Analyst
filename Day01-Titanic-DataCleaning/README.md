# Day 01 - Titanic Data Cleaning & Exploration

### Dataset Source:
- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

### Tasks Performed:
- Loaded data using Pandas
- Explored dataset using `.info()`, `.describe()`, `.isnull()`
- Dropped the `Cabin` column due to excessive missing values
- Filled missing `Age` values using mean
- Dropped remaining rows with missing data
- Filtered data using both boolean indexing and `.query()`
- Exported cleaned dataset to CSV

### Key Observations:
- Cabin had ~77% missing values and was dropped
- Age had missing values and was imputed with mean
- Cleaned dataset has ~889 records after processing

### Tools Used:
- Python, Pandas, NumPy
- Jupyter Notebook
