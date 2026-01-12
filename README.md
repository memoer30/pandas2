# Introduction to Pandas

A comprehensive Jupyter notebook tutorial covering the fundamentals of pandas, the powerful Python library for data analysis and manipulation.

## 📋 Overview

This notebook provides a hands-on introduction to pandas, covering essential concepts and operations needed to work with tabular data in Python. It's designed for beginners who want to learn data manipulation and analysis using real-world examples.

## 🎯 Topics Covered

### 0. Importing pandas
- Setting up and importing the pandas library
- Version checking

### 1. Datatypes
- **Series**: 1-dimensional columns of data
- **DataFrame**: 2-dimensional tables with rows and columns
- Creating Series and DataFrames from scratch

### 2. Importing Data
- Reading CSV files with `pd.read_csv()`
- Loading data from various sources
- Working with spreadsheet data

### 3. Exporting Data
- Saving DataFrames to CSV format with `.to_csv()`
- Exporting to Excel with `.to_excel()`

### 4. Describing Data
- `.dtypes` - Check column data types
- `.describe()` - Statistical summary of numerical columns
- `.info()` - Overview of DataFrame structure and missing values
- `.mean()`, `.sum()` - Statistical operations
- `.columns` and `.index` - Accessing DataFrame structure

### 5. Viewing and Selecting Data
- `.head()` and `.tail()` - View first/last rows
- `.loc[]` - Label-based indexing
- `.iloc[]` - Position-based indexing
- Boolean indexing for filtering data
- `pd.crosstab()` - Cross-tabulation analysis
- `.groupby()` - Group operations
- `.plot()` and `.hist()` - Quick data visualization

### 6. Manipulating Data
- String operations with `.str`
- Handling missing data with `.fillna()` and `.dropna()`
- Creating new columns
- Feature engineering
- Removing columns with `.drop()`
- Sampling data with `.sample()`
- Resetting indexes with `.reset_index()`
- Applying functions with `.apply()` and lambda functions

## 📊 Datasets Used

The notebook works with three CSV files:
- `car-sales.csv` - Complete car sales data
- `car-sales-missing-data.csv` - Car sales data with missing values (for handling NaN)
- `heart-disease.csv` - Patient data for practice exercises

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas matplotlib jupyter
```

### Running the Notebook

1. Clone this repository
2. Navigate to the project directory
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook introduction-to-pandas.ipynb
   ```

## 💡 Key Concepts

- **Series vs DataFrame**: Understanding the difference between 1D and 2D data structures
- **Indexing**: Using `.loc[]` for labels and `.iloc[]` for positions
- **Data Cleaning**: Handling missing values and data type conversions
- **Feature Engineering**: Creating new columns from existing data
- **Data Visualization**: Quick plotting for exploratory data analysis

## 🔧 Common Operations

| Operation | Method | Description |
|-----------|--------|-------------|
| Import CSV | `pd.read_csv()` | Load data from CSV file |
| View data | `.head()`, `.tail()` | Display first/last rows |
| Info | `.info()`, `.describe()` | Get DataFrame summary |
| Select column | `df['column']` | Access specific column |
| Filter rows | `df[df['col'] > value]` | Boolean indexing |
| Handle missing | `.fillna()`, `.dropna()` | Fill or remove NaN values |
| Add column | `df['new'] = values` | Create new column |
| Plot | `.plot()`, `.hist()` | Visualize data |

## 📚 Resources

- [pandas Documentation](https://pandas.pydata.org/docs/)
- [pandas API Reference](https://pandas.pydata.org/docs/reference/index.html)
- [10 Minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)

## 🤝 Contributing

Feel free to fork this repository and submit pull requests with improvements or additional examples.

## 📝 License

This project is open source and available for educational purposes.

## ✨ Acknowledgments

This tutorial covers fundamental pandas operations with practical examples using real-world datasets. Perfect for data science beginners and anyone looking to strengthen their pandas skills.

---

**Note**: Make sure all required CSV files are in the same directory as the notebook before running.
