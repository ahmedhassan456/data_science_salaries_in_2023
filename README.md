# Data Science Salaries Analysis and Prediction

This project analyzes data science salaries across various roles, experience levels, and locations. The analysis is performed using a dataset containing salary information for data science-related jobs.


## Dataset

The dataset `data/ds_salaries.csv` contains the following columns:

- `work_year`: The year the salary was paid.
- `experience_level`: The experience level in the job role.
- `employment_type`: The type of employment (e.g., full-time, part-time).
- `job_title`: The job title.
- `salary`: The salary amount.
- `salary_currency`: The currency of the salary.
- `salary_in_usd`: The salary amount in USD.
- `employee_residence`: The country of residence of the employee.
- `remote_ratio`: The ratio of remote work.
- `company_location`: The location of the company.
- `company_size`: The size of the company.


## Analysis

The analysis is performed in the Jupyter notebook `data_science_salaries_analysis.ipynb`. The notebook includes the following steps:

1. Importing necessary libraries.
2. Loading the dataset.
3. Check of Data.
4. Exploratory data analysis (EDA).

## Requirements

- Python 3.8 or later

**Install Python using MiniConda**
1. Download and install MiniConda from 	[here](https://docs.anaconda.com/miniconda/)
2. Create a new environment using the following command:
```sh
conda create -n data_science_salaries python=3.8
```
3. Activate the environment:
```sh
conda activate data_science_salaries
```

## Installation

To install the required dependencies, run:
```sh
pip install -r requirements.txt
```

## Usage

To run the analysis, open the Jupyter notebook data_science_salaries.ipynb and execute the cells.

## License
This project is licensed under the MIT License.
