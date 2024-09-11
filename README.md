# Big Data in Social Sciences course project

## Project Overview
This project analyzes the relationship between childcare services and fertility rates in Italy. The analysis was conducted using R, employing techniques like data preprocessing, regression analysis, and clustering (K-means). The datasets used were sourced from ISTAT and processed for the purposes of this project.

## Folder Structure

- **data/**: Contains the dataset used in the analysis.
    - `Enviroment_Fertility.RData`: A processed dataset on fertility rates and childcare services in Italy.

- **reports/**: Contains final reports.
    - `big data final report.qmd`: The Quarto markdown file for the final report.
    - `Final Report Big Data in Social Sciences 23_24.pdf`: The final report in PDF format.

- **notebooks/**: Contains the code for data analysis.
    - `Dataset tidying and merging.qmd`: Quarto markdown notebook for data cleaning and merging.

## Instructions

1. **Viewing the Code:** Navigate to the `notebooks/` folder and open the `.qmd` files in a Quarto-compatible editor for the full code.
2. **Data Analysis:** The data is stored in the `data/` folder. Load the `.RData` file using the following R command:
    ```R
    load("data/Enviroment_Fertility.RData")
    ```
3. **Reports:** Final reports, both in `.qmd` and `.pdf` formats, are available in the `reports/` folder.

## Dependencies

Make sure you have the following installed to run the code and analysis:
- **R** (latest version recommended)
- **Quarto** for running `.qmd` files
- **Required R Packages**: Install the necessary R packages using:
    ```R
    install.packages(c("ggplot2", "dplyr", "viridis", "eurostat"))
    ```
## Acknowledgements

This project was a collaborative effort completed as part of the Big Data in Social Sciences course under the guidance of Professor Barban. I would like to express my gratitude to my fellow group members, whose dedication and teamwork were instrumental in the successful completion of this project:

- **[Sarah Bertoni](https://github.com/sarah-bertoni)**
- **[Antonio Caggianelli](https://github.com/antoniocaggianelli)**
- **Maria Carlotta Magnaguagno**
- **Mattia Malipiero**

Each member contributed equally to the project's development and execution.
