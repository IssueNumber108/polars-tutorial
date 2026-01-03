# Polars Tutorial Project 🚀

A comprehensive tutorial project for learning **Polars** - the blazingly fast DataFrame library for Python and Rust.

## 📋 Table of Contents

- [About Polars](#about-polars)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Tutorial Notebooks](#tutorial-notebooks)
- [Sample Data](#sample-data)
- [Key Features Covered](#key-features-covered)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Why Polars?](#why-polars)

## 🎯 About Polars

Polars is a lightning-fast DataFrame library implemented in Rust and designed to be a high-performance alternative to Pandas. It offers:

- **Speed**: Up to 10-100x faster than Pandas for many operations
- **Memory Efficiency**: Lower memory footprint
- **Parallel Processing**: Built-in multi-threading support
- **Lazy Evaluation**: Query optimization through lazy execution
- **Expressive API**: Clean and intuitive syntax

## 📁 Project Structure

```
polars-tutorial-project/
├── README.md
├── requirements.txt
├── notebooks/
│   ├── 01_installation_and_basics.ipynb
│   ├── 02_data_import_export.ipynb
│   ├── 03_data_manipulation.ipynb
│   ├── 04_data_visualization.ipynb
│   ├── 05_parallel_processing.ipynb
│   ├── 06_lazy_evaluation.ipynb
│   └── 07_polars_vs_pandas.ipynb
└── data/
    ├── sales_data.csv
    ├── employees.json
    ├── transactions.parquet
    └── students.xlsx
```

## 🔧 Installation

### Basic Installation

```bash
pip install polars
```

### Full Installation (with all optional dependencies)

```bash
pip install polars[all]
```

### Required Dependencies for This Tutorial

```bash
pip install polars pyarrow matplotlib seaborn plotly openpyxl xlsxwriter jupyter
```

Or simply:

```bash
pip install -r requirements.txt
```

## 📓 Tutorial Notebooks

### 1. Installation and Basics
- Installing Polars
- Creating DataFrames
- Basic operations
- Data types and schema

### 2. Data Import/Export
- Reading CSV, JSON, Parquet, Excel files
- Writing data to different formats
- Handling different file encodings
- Working with compressed files

### 3. Data Manipulation
- Filtering and selecting data
- Sorting and grouping
- Aggregations and transformations
- Joining and merging DataFrames
- Window functions

### 4. Data Visualization
- Integration with Matplotlib
- Creating plots with Seaborn
- Interactive visualizations with Plotly
- Custom visualization techniques

### 5. Parallel Processing
- Understanding Polars' parallel execution
- Multi-threading capabilities
- Performance optimization
- Batch processing

### 6. Lazy Evaluation
- Introduction to lazy DataFrames
- Query optimization
- Execution plans
- Best practices for lazy evaluation

### 7. Polars vs Pandas
- Performance comparisons
- Memory usage analysis
- API differences
- Migration guide from Pandas to Polars

## 📊 Sample Data

The project includes sample datasets for hands-on practice:

- **sales_data.csv**: Product sales data with dates, categories, and revenue
- **employees.json**: Employee information with salaries and performance scores
- **transactions.parquet**: Transaction records in Parquet format
- **students.xlsx**: Student grades in Excel format

## ✨ Key Features Covered

- ✅ DataFrame creation and manipulation
- ✅ Reading/writing multiple file formats (CSV, JSON, Parquet, Excel)
- ✅ Data cleaning and transformation
- ✅ Aggregations and grouping operations
- ✅ Joining and merging datasets
- ✅ Visualization with popular libraries
- ✅ Parallel and lazy execution
- ✅ Performance optimization techniques
- ✅ Comparison with Pandas

## 📚 Prerequisites

- Python 3.8 or higher
- Basic understanding of DataFrames and data analysis
- Familiarity with Pandas (helpful but not required)
- Jupyter Notebook or JupyterLab

## 🚀 Getting Started

1. **Clone or download this project**

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

4. **Start with the first notebook:**
   Open `notebooks/01_installation_and_basics.ipynb`

5. **Follow the tutorials in order:**
   Each notebook builds upon concepts from the previous ones.

## 🎓 Why Polars?

### Speed Comparison
Polars can be significantly faster than Pandas:
- **Filtering**: 5-10x faster
- **Groupby operations**: 10-50x faster
- **Joins**: 5-20x faster
- **Reading large files**: 2-5x faster

### Memory Efficiency
- Optimized memory layout
- Efficient string handling
- Lower overhead for categorical data

### Modern Design
- Built from the ground up with modern hardware in mind
- Leverages all CPU cores automatically
- Query optimization through lazy evaluation

## 📖 Additional Resources

- [Official Polars Documentation](https://pola-rs.github.io/polars/)
- [Polars GitHub Repository](https://github.com/pola-rs/polars)
- [Polars User Guide](https://pola-rs.github.io/polars-book/)
- [Polars API Reference](https://pola-rs.github.io/polars/py-polars/html/reference/)

## 🤝 Contributing

Feel free to submit issues, suggestions, or improvements to this tutorial project.

## 📄 License

This tutorial project is available for educational purposes.

---

**Happy Learning! 🎉**

Start your journey with Polars and experience the speed of modern data processing!
