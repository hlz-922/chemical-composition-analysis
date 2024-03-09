# chemical-composition-analysis

## Project description

The project aims to analyze the chemical composition of iron slag found at an archaeological site in East Africa called Kilwa. Iron slag, a byproduct of iron production, was analyzed to test the hypothesis that two different production processes might have been employed at the site. The goal is to perform principal component analysis (PCA) on the chemical composition data to determine if the archaeological hypothesis is correct, specifically by identifying whether the PCA plot reveals one, two, or more distinct clusters.

## Key steps

- **Initial Data Preparation:** Making a copy of the dataset for cleaning, dropping non-numeric columns, and removing columns that contain only zeros, which are considered to contain no valuable information.
- **Principal Component Analysis (PCA):** Conducting PCA on the cleaned dataset to extract the principal components that explain the most variance in the data. This step is critical for identifying patterns in the chemical composition that may indicate different production processes.
- **Visualization:** Using seaborn to plot the first two principal components in a scatterplot, with additional annotations to enhance interpretability. This visualization aims to reveal any distinct clusters corresponding to different iron slag production techniques.
