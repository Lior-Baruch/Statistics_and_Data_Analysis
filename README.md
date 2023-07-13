# Statistics and Data Analysis

This repository is an academic project part of the Statistics and Data Analysis course in the MS.c studies in Computer Science Reichman university. It includes four Jupyter notebooks that cover various topics in statistics and data analysis.

## Repository Overview

Each notebook in the repository focuses on a distinct topic in statistics and data analysis, providing practical implementations and rich visualizations. The topics covered range from foundational concepts such as probability distributions and correlations to applied data analysis in the context of differential gene expression.

### Distributions (`HW1_Distributions.ipynb`)

This notebook provides a comprehensive exploration of various probability distributions, both discrete and continuous. It includes discussions and practical examples of the normal, binomial, and Poisson distributions, among others. Furthermore, the notebook explores the concept of mixture distributions and provides an implementation of the Expectation-Maximization (EM) algorithm for fitting them.

### Data Exploration and Visualization (`HW2_Data_exploration_and_visialization.ipynb`)

This notebook covers the critical first steps of any data analysis project: data exploration and visualization. It provides techniques for understanding the structure of data, identifying potential issues such as missing data and outliers, and transforming data as required. The notebook also showcases various data visualization techniques, including histograms, box plots, scatter plots, and heatmaps.

### Correlations (`HW3_Correlations.ipynb`)

This notebook delves into the concept of correlations, providing implementations to compute and interpret Pearson's correlation coefficient and Spearman's rank correlation coefficient. The notebook discusses the significance of these correlation measures and provides visualizations of correlation matrices and heatmaps.

### Differential Gene Expression in Acute Myocardial Infraction (`HW4_Differential_Gene_Expression_in_Acute_Myocardial_Infraction.ipynb`)

This notebook is a detailed case study on analyzing gene expression data within the context of acute myocardial infraction. It covers the following steps:

- **Data processing**: Loading the data, handling missing values, and preparing the data for analysis.

- **High-level data analysis**: Provides a high-level overview of the data, including the number of genes profiled, the total number of samples, the number of samples in each class (M and H), and the number of columns (genes) left after removing those with missing values.

- **Gene expression visualization**: The notebook randomly selects 20 genes and provides a visual comparison of their expression levels in the two classes (M and H) using box plots.

The subsequent sections of the notebook cover more advanced topics such as normalization, statistical testing, and interpretation of the results. 

## Running the Notebooks

Each notebook can be run independently. Make sure you have Jupyter Notebook installed and the required Python libraries specified in each notebook.

## Dependencies

Ensure these libraries are installed in your Python environment to run the notebooks successfully:

- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scipy
- Statsmodels
- Scikit-learn

## Contribution

This repository is an academic project created by Lior-Baruch. Contributions, issues, and feature requests are welcome!

## License

This project is licensed under the MIT License.
