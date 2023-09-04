# Food Food Case Study: McDonalds

An analysis of customer food preferences based on a McDonalds dataset. The analysis explores the relationship between various food attributes, customer demographics, and their perceptions of food.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Notebook Description](#notebook-description)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Food businesses often strive to understand customer preferences to better cater to their needs. This project aims to analyze customer food preferences by examining McDonalds dataset containing information about food attributes, customer demographics, and customer ratings.

The objectives of this analysis are as follows:
- Explore the relationships between food attributes (e.g., taste, healthiness) and customer ratings.
- Understand Market Segementation using the dataset.
- Visualize key insights to aid in decision-making for food-related businesses.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine using the following command:

-  git clone https://github.com/jasmeetsingh-028/Fast-Food-Case-Study

2. Install requirements.txt using:

- pip install -r requirements.txt

3. Open the Jupyter Notebook `notebook.ipynb` to view the analysis.

## Usage

To reproduce the analysis, open the Jupyter Notebook `notebook.ipynb` inside Notebooks and Dataset and follow the step-by-step instructions provided in the notebook. The notebook covers the following areas:

- Data preprocessing: Cleaning and preparing the dataset for analysis.
- Exploratory data analysis (EDA): Descriptive statistics, data visualization, and pattern discovery.
- PCA: For performing principal components analysis, and creating a perceptual map. A perceptual map offers initial insights into how attributes are rated by respondents and, importantly, which attributes tend to be rated in the same way.
- K-Means clustering: For calculating solutions for two to eight market segments using standard k-means analysis

## Notebook Description

The Jupyter Notebook `notbook.ipynb` contains detailed explanations and code for each step of the analysis. Here's an overview of the notebook sections:

1. **Data Loading and Preprocessing:**
- Load the dataset.
- Handle missing values and data cleaning.

2. **Exploratory Data Analysis (EDA):**
- Explore data distribution.
- Visualize customer ratings and attribute preferences.
- Investigate demographic characteristics.
- Profile Report of the dataset using Pandas Profiling.

3. **PCA:**
- Perform PCA to identify significant relationships.

4. **K-Means clustering:**
- Perform Market Segmentation.
- Implementing Bootstrap resampling with K-Means.

## Contributing

Contributions to this project are welcome. If you'd like to report issues, suggest improvements, or contribute code, please follow these guidelines:

- Open an issue to discuss proposed changes or report problems.
- Fork the repository and create a pull request with your changes.
- Follow the code of conduct while participating in the project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.