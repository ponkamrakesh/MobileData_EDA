# EDA for Mobile Specifications and Price using pandas,seaborn and matplotlib

This project performs Exploratory Data Analysis (EDA) on a dataset containing mobile phone specifications and their launch prices in various countries. The dataset includes information such as company name, model name, mobile weight, RAM, camera details, processor, battery capacity, screen size, launch prices in different currencies, and launch year.

## Dataset

The dataset used is `Mobiles.csv`. It contains the following columns:

* **Company Name:** The name of the mobile phone company.
* **Model Name:** The model name of the mobile phone.
* **Mobile Weight:** The weight of the mobile phone in grams.
* **RAM:** The RAM size of the mobile phone in GB.
* **Front Camera:** The front camera specifications.
* **Back Camera:** The back camera specifications.
* **Processor:** The processor details.
* **Battery Capacity:** The battery capacity in mAh.
* **Screen Size:** The screen size in inches.
* **Launched Price (Pakistan):** The launch price in Pakistani Rupees (PKR).
* **Launched Price (India):** The launch price in Indian Rupees (INR).
* **Launched Price (China):** The launch price in Chinese Yuan (CNY).
* **Launched Price (USA):** The launch price in US Dollars (USD).
* **Launched Price (Dubai):** The launch price in UAE Dirhams (AED).
* **Launched Year:** The year the mobile phone was launched.

## Project Structure

The project is contained within a Jupyter Notebook (`.ipynb`) file. The notebook performs the following tasks:

1.  **Data Loading and Inspection:**
    * Loads the dataset using pandas.
    * Checks for missing values and duplicates.
    * Removes rows with invalid model names.
    * Removes duplicate model names.
2.  **Data Cleaning and Preprocessing:**
    * Converts relevant columns to appropriate data types (e.g., numeric).
    * Standardizes company names.
    * Extracts numeric values from columns like RAM, mobile weight, and screen size.
    * Converts all launched prices to INR for uniform comparison.
3.  **Exploratory Data Analysis (EDA):**
    * Visualizes the distribution of mobile phones by company using count plots.
    * Analyzes the average mobile weight and battery capacity per company using bar plots and line plots.
    * Examines the launch year trends for each company.
    * Visualizes the average screen size per company using scatter plots.
    * Compares launch prices across different countries using bar plots.
4.  **Data Visualization:**
    * Uses `matplotlib` and `seaborn` for creating visualizations.

## Key Findings

* Oppo has produced the most mobile phone models in the dataset.
* IQOO tends to have the highest average mobile weight and battery capacity, likely due to its production of tablets.
* Sony has the lowest average mobile weight.
* Honor has the largest average screen size for phones.
* The project provides insights into the price variations of mobile phones across different countries.
* The starting and ending years of mobile phone production for each brand is clearly shown.

## Requirements

* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn

## Installation

To install the required libraries, run the following command:

```bash
pip install numpy pandas matplotlib seaborn
