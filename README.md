# 3_Google_play_store
# Google Play Store Apps - Exploratory Data Analysis (EDA)

This project is an exploratory data analysis (EDA) focused on analyzing the Google Play Store dataset. By cleaning and filtering the raw application data, the notebook uncovers trends related to app categories, pricing models, user reviews, ratings, and download counts.


## Project Structure

The repository includes:
* **`4_Google_play_store_eda_project_answers.ipynb`**: The Jupyter Notebook containing the data analysis steps, cleaning operations, and Python code.
* **`4-googleplaystore.csv`**: The dataset containing mobile application attributes from the Google Play Store.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

The `4-googleplaystore.csv` dataset tracks mobile applications across the following key attributes:
* **App:** The name of the application.
* **Category:** Operational classification (e.g., Business, Family, Tools, Games).
* **Rating:** Overall user rating score out of 5.
* **Reviews:** Total count of user reviews received.
* **Size:** Total memory footprint of the application file.
* **Installs:** Approximate download bucket thresholds.
* **Type:** Pricing identifier (Free or Paid).
* **Price:** The specific cost value of the application.
* **Content Rating:** Target age group classification (Everyone, Teen, Mature, etc.).
* **Genres:** Sub-category listings.


## Key Tasks & Insights Covered

The notebook handles data cleaning and walks through essential data manipulation queries:
1. **Initial Exploration:** Displaying the top and bottom rows of the data, inspecting column data types, and calculating structural shape and row counts.
2. **Data Cleaning:** Identifying total missing null values across columns and dropping records with incomplete data.
3. **Descriptive Statistics:** Finding descriptive statistics for the numerical metrics like App Ratings.
4. **Targeted Value Filters:** Isolating specific rows based on specific rating conditions or categorical variables.
5. **Sorting and Aggregation:** Finding out distribution counts and sorting files sequentially by key application metrics.


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Move your dataset (`4-googleplaystore.csv`) into the same folder if it isn't already there.
4. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy notebook
   jupyter notebook
