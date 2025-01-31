# Market Study with Python

## Overview
This project presents a comprehensive market study using Python, leveraging data from the Food and Agriculture Organization (FAO) and the World Bank. The analysis includes dimensionality reduction through Principal Component Analysis (PCA) and clustering techniques to identify market segments. The PESTEL framework is applied to understand the macro-environmental factors influencing the market.

## Data Pipeline
The main steps of the project include:
- **PESTEL Analysis:** A strategic tool was applied to analyze the macro-environmental factors affecting the market.
- **Data Cleaning and Preparation:** Data from FAO and the World Bank were collected, cleaned, and preprocessed for analysis.
- **Exploratory Data Analysis (EDA):** Initial insights and visualizations were generated to understand the data.
- **PCA and Clustering:** Dimensionality reduction was performed using PCA, followed by clustering techniques such as Hierarchical Clustering and K-Means.


## Files
- `datasets/` : Contains the raw and cleaned data files.
  - `DisponiAlim.csv`
  - `Emissions.csv`
  - `Population.csv`
  - `indice_logistique.csv`
  - `pays_partenaire.csv`
  - `pib_habitant.csv`
  - `stab_politique.csv`
- `notebooks/` : Includes separate notebooks for EDA, PCA, and clustering analysis.
  - `Melchior_Manuel_1_preparation_nettoyage_analyse_exploratoire_122024.ipynb`: Data exploration, cleaning, and initial insights.
  - `Melchiori_Manuel_2_clustering_visualisations_122024.ipynb`: Clustering and visualizations using PCA and clustering techniques.
- `choix_indicateurs.txt`: Documentation justifying the chosen indicators based on the PESTEL method.

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the notebooks in the `notebooks/` directory to explore the analysis.

## Key Features
- Comprehensive market analysis using real-world data.
- Application of PCA for dimensionality reduction.
- Clustering analysis to segment the market.
- PESTEL framework for macro-environmental analysis.

## Future Improvements
- Integrate additional data sources for a more robust analysis.
- Develop predictive models to forecast market trends.
- Enhance visualizations for better interpretability.
