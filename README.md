# Haberman's Survival Dataset EDA Project

Welcome to the GitHub repository for our exploratory data analysis (EDA) project on the Haberman's Survival Dataset. This project aims to provide comprehensive insights into the dataset through various statistical and visual analysis techniques, including Probability Density Functions (PDFs), Cumulative Distribution Functions (CDFs), violin plots, pair plots, and box plots. Our goal is to uncover patterns, trends, and relationships that can inform further research and predictive modeling on survival rates following breast cancer surgeries.

## Dataset Overview

The Haberman's Survival Dataset contains cases from a study conducted between 1958 and 1970 at the University of Chicago's Billings Hospital on the survival of patients who had undergone surgery for breast cancer. The dataset includes the following attributes:

- **Age**: Age of patient at the time of operation (numerical)
- **Operation Year**: Year of operation (1958-1970, numerical)
- **Axillary Nodes**: Number of positive axillary nodes detected (numerical)
- **Survival Status**: Survival status (1 = the patient survived 5 years or longer, 2 = the patient died within 5 years)

## Project Structure

This project is organized as follows:

- `README.md`: Provides an overview of the project, dataset, and instructions on how to navigate and use the analysis.
- `data/`: Contains the Haberman's Survival Dataset in CSV format.
- `notebooks/`: Jupyter notebooks with the EDA steps, including data preprocessing, analysis, and visualization.
- `requirements.txt`: A list of Python packages required to run the notebooks.

## Setup and Installation

To get started with this project, please follow these steps:

1. Clone this repository to your local machine using `git clone <repository-url>`.
2. Ensure that Python 3.x is installed on your system.
3. Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

4. Navigate to the `notebooks/` directory and launch Jupyter Notebook or JupyterLab to open the EDA notebooks.

## Key Analyses

The notebooks within this project cover a range of analyses and visualizations, specifically:

- **PDFs (Probability Density Functions)**: Used to visualize the distribution of individual features.
- **CDFs (Cumulative Distribution Functions)**: Provides cumulative probability associated with a function.
- **Violin Plots**: Offers a deeper insight into the distribution of the data, combining aspects of box plots and density plots.
- **Pair Plots**: Helps in understanding the pairwise relationship between all the features.
- **Box Plots**: Used to visualize the distribution of the data through quartiles and to detect outliers.

Each of these techniques provides unique insights into the dataset and helps in understanding the factors that might influence the survival of breast cancer patients.
