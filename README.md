
# Exploratory Data Analysis (EDA) on Crop Recommendation Dataset

## Steps Performed

### 1. Loading the Dataset
- Imported necessary libraries such as `numpy`, `pandas`, `matplotlib.pyplot`, and `seaborn`.
- Loaded the dataset using `pd.read_csv()`.

### 2. Initial Data Inspection
- Used `crop.head()` and `crop.tail()` to preview the first and last few rows of the dataset.
- Checked the dataset dimensions with `crop.shape`.
- Examined data types and memory usage using `crop.info()`.

### 3. Data Quality Checks
- Checked for missing values with `crop.isnull().sum()`.
- Identified duplicate entries using `crop.duplicated().sum()`.

### 4. Statistical Analysis
- Generated descriptive statistics using `crop.describe()`.
- Analyzed the distribution of the target feature (crop labels) with `crop['label'].value_counts()`.

These steps provide an overview of the dataset, help identify potential data quality issues, and offer initial insights into the data distribution.

