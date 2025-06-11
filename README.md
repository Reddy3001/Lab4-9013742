# Lab4-9013742
# Week 5 Lab - Data Cleaning and Outlier Detection

This lab explores some core data preprocessing concepts like:

- Tidying data with `melt()`
- Handling missing data using `SimpleImputer`
- Outlier detection and removal with Z-Score and IQR
- Visualizing data through boxplots and scatterplots

---
- Converted dataset with `pandas.melt()`
- Searched structure with `head()`, `iloc`, and `loc`

### 2. Billboard Dataset
- Cleansed weekly rank columns with `melt()`
- Extracted week numbers with regex
- Computed actual ranking dates with `date.entered + timedelta`
- Dropped null values and renamed columns

### 3. Cars Dataset
- Omitted metadata row and converted numeric columns
- Handled missing values with `SimpleImputer` (median strategy)
- Removed duplicate values

### 4. Diabetes Dataset (`load_diabetes`)
- Loaded in-built dataset from `sklearn`
- Displayed features via boxplot and scatterplot
- Applied Z-Score and IQR filtering to eliminate outliers

---

## How to Run

1. Clone the repository:
   ```bash
git clone https://github.com/YourUsername/YourRepositoryName.git
   cd YourRepositoryName

2. Create a virtual environment using 
```bash
python3 -m venv .venv
source ./.venv/Scripts/activate
```
3. Install dependencies using the following
```bash
pip install -r requirements.txt
```

