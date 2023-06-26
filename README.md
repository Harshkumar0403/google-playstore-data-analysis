
# Exploratory Data Analysis on Google Playstore App Data

This project is a part of the course "Data Analysis: Zero to Pandas" offered by Jovian. The project focuses on performing exploratory data analysis on the Google Playstore App data using Python libraries such as Pandas, Matplotlib, and Seaborn.

## Project Overview

The project analyzes a dataset containing information about various apps available on the Google Playstore. The dataset consists of 10,481 entries and 11 columns. The columns in the dataset are as follows:

1. **App Name**: The name of the app.
2. **Category**: The category to which the app belongs.
3. **Reviews**: The number of user reviews received for the app.
4. **Rating**: The average rating given by users for the app.
5. **Installs**: The number of times the app has been installed.
6. **Genre**: The genre of the app.
7. **Type**: Indicates whether the app is free or paid.
8. **Price**: The price of the app, if it is a paid app.
9. **Content Rating**: The target audience for the app (e.g., everyone, adult, unrated, 18+, 17+).
10. **Last Updated**: The date when the app was last updated.

## Project Goals

The main objectives of this project are as follows:

1. Perform data cleaning and preprocessing to ensure the dataset is suitable for analysis.
2. Gain insights into the distribution and characteristics of the available app categories, ratings, installs, and other relevant factors.
3. Visualize the data using matplotlib and seaborn to better understand the patterns and relationships within the dataset.
4. Extract meaningful conclusions and observations from the analysis.

## Libraries Used

The project relies on the following Python libraries:

1. **Pandas**: Used for data manipulation, cleaning, and preprocessing.
2. **Matplotlib**: Used for creating various types of visualizations such as bar plots, scatter plots, and histograms.
3. **Seaborn**: Built on top of Matplotlib, Seaborn provides a higher-level interface for creating visually appealing statistical graphics.

## Project Structure

The project is organized as follows:

- `data/`: Directory containing the dataset file (`googleplaystore.csv`).
- `google_Playstore_data.ipynb`: Jupyter Notebook containing the project code, analysis, and visualizations.
- `README.md`: This README file, providing an overview of the project.

## Getting Started

To run the project and reproduce the analysis:

1. Clone the project repository:

   ```
   git clone <repository-url>
   ```

2. Install the required dependencies:

   ```
   pip install pandas matplotlib seaborn jovian
   ```

3. Open and run the `google_Playstore_data.ipynb` notebook using Jupyter Notebook or any compatible environment.

4. Follow the instructions in the notebook to execute the code cells and explore the data analysis and visualizations.

## Acknowledgments

This project was completed as part of the "Data Analysis: Zero to Pandas" course offered by Jovian (www.jovian.ai). The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/lava18/google-play-store-apps).
