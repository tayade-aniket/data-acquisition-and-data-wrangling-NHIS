# Data Acquisition and Data Wrangling Project
## Project Overview
This project focuses on performing data wrangling techniques on multiple datasets and merging them for further analysis. The goal is to clean and preprocess the data for meaningful insights while handling issues like missing values, duplicates, and outliers.

## Datasets Used
- **Dataset 1**: Contains ride-sharing data with attributes like date, season, weather conditions, and rental counts.
- **Dataset 2**: Contains additional ride-sharing data with overlapping attributes.
- **Dataset 3**: Contains 390 records of bike-sharing data, including date, season, weather conditions, temperature, humidity, windspeed, and hourly bike rentals.

## Tasks Performed
### Week 1: Data Wrangling on Dataset 1 and Dataset 2
- Standardized column names.
- Merged Dataset 1 and Dataset 2.
- Checked for missing values and treated them accordingly.
- Removed duplicate records.

### Week 2: Merging with Dataset 3 & Handling Issues
- Merged the combined dataset (Dataset 1 & 2) with Dataset 3.
- Identified and handled missing values post-merge.
- Applied outlier detection and removal using the **IQR method**.

### Week 3: Skewness and Correlation Analysis
- Checked for skewness in numerical features.
- Created a **heatmap** to visualize feature correlations.

## Key Features & Techniques Used
- **Pandas**: Data manipulation and merging.
- **NumPy**: Handling numerical data.
- **Seaborn & Matplotlib**: Visualization (correlation heatmap, data distribution).
- **Outlier Handling**: IQR method.
- **Missing Value Treatment**: Using mode for categorical features and median for numerical ones.
- **Duplicate Handling**: Removal before merging.

## Results & Final Deliverable
- The final dataset is saved as `merged_dataset/final_merge.csv` for further analysis.
- The project was executed in **Jupyter Notebook**, which is available in this repository.
- Data is cleaned, structured, and ready for machine learning or business insights.

## How to Use This Repository
1. Clone the repository:
   ```bash
      git clone https://github.com/tayade-aniket/data-acquisition-and-data-wrangling-NHIS.git
   ```
2. Open the Jupyter Notebook to view the step-by-step process.
3. Run the notebook or modify it to explore further insights.

## Author
- **Mr. Aniket G. Tayade**

## License
This project is licensed under the MIT License. 🎉