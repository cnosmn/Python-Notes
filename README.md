# Python Data Manipulation with Pandas

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3-green.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21-yellow.svg)](https://numpy.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11-red.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains practical examples and tutorials on data manipulation and analysis using Python's Pandas library. The notebooks demonstrate various data handling techniques, from basic operations to advanced data transformations, grouping, and aggregation methods.

## Table of Contents

- [Python Data Manipulation with Pandas](#python-data-manipulation-with-pandas)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Example Datasets](#example-datasets)
  - [Data Manipulation Techniques](#data-manipulation-techniques)
    - [Basic Operations](#basic-operations)
    - [Data Transformation](#data-transformation)
    - [Advanced Techniques](#advanced-techniques)
  - [Installation](#installation)
  - [Usage](#usage)
  - [File Descriptions](#file-descriptions)
  - [Dependencies](#dependencies)

## Introduction

Data manipulation is a fundamental skill for data analysis, machine learning, and data science projects. This repository serves as a practical guide to handling data with Python's Pandas library, showcasing various techniques through examples using real-world datasets.

## Features

- Basic and advanced Pandas operations
- Data filtering and selection techniques
- Grouping, aggregation, and transformation methods
- Pivot tables and cross-tabulations
- Data exploration and basic statistical analysis
- Working with different data types and structures

## Example Datasets

The examples use several built-in datasets provided by Seaborn:

1. **Titanic Dataset** - Passenger data from the Titanic disaster
2. **Planets Dataset** - Data about exoplanets discovered by NASA
3. **Custom Generated Data** - Simple NumPy arrays converted to DataFrames

## Data Manipulation Techniques

This repository demonstrates the following data manipulation techniques:

### Basic Operations
- Creating DataFrames from different data sources
- Selecting columns and rows
- Filtering data with conditions
- Handling missing values

### Data Transformation
- Grouping data with `groupby()`
- Aggregation with multiple functions
- Applying custom functions to groups
- Data binning with `pd.cut()`

### Advanced Techniques
- Creating pivot tables
- Multi-level indexing and hierarchical data
- Reshaping data with `unstack()`
- Advanced filtering using `filter()` method
- Statistical operations across groups

## Installation

1. Clone this repository
```bash
git clone https://github.com/cnosmn/Python-Notes.git
cd Python-Notes
```

2. Install required packages
```bash
pip install pandas numpy seaborn matplotlib pandas-datareader
```

## Usage

The examples are provided as text files containing Python code snippets. You can run these examples in any Python environment:

1. Copy the code snippets into your Python IDE or Jupyter Notebook
2. Execute the code blocks sequentially
3. Experiment with modifying the parameters to see how results change

## File Descriptions

- **python_not_1.py** - Contains examples focusing on:
  - Creating and manipulating DataFrames
  - Basic pandas Series operations
  - Filtering and conditional selection
  - Advanced grouping and aggregation
  - Working with astronomical datasets

- **python_not_2.py** - Contains examples focusing on:
  - Working with the Titanic dataset
  - Pivot table operations
  - Data binning with `pd.cut()`
  - Multi-level indexing
  - Survival rate analysis by multiple factors

## Dependencies

- Python 3.x
- Pandas: For data manipulation and analysis
- NumPy: For numerical operations
- Seaborn: For access to example datasets
- Matplotlib: For visualization (implicitly used by Seaborn)


---

Feel free to contribute to this repository by adding more examples or improving the existing ones. If you have any questions or suggestions, please open an issue or submit a pull request.