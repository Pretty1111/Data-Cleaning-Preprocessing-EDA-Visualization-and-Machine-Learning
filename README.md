# Portfolio-Analysis-Data-Preprocessing-EDA-Visualization-and-Machine-Learning

This Jupyter Notebook contains an analysis of a portfolio dataset, covering data preprocessing, exploratory data analysis (EDA), data visualization, and machine learning. The portfolio dataset was sourced from the World Bank's World Development Indicators database [Link to World Bank Data](https://databank.worldbank.org/source/world-development-indicators) and includes various economic and social indicators for different countries over the years.

## Data Preprocessing
The notebook begins with data preprocessing steps to clean and transform the dataset for further analysis. This includes extracting the year from column names, melting the DataFrame to create a tidy format, converting the 'Year' column to datetime format, and dropping irrelevant columns.

## Exploratory Data Analysis (EDA) and Visualization
The next section focuses on EDA and data visualization. It includes various types of plots to analyze the trends and relationships between different indicators over the years. The plots used in the analysis include scatter plots, box plots, violin plots, area plots, 3D scatter plots, polar bar plots, polar scatter plots, polar line plots, and ternary scatter plots.

## Data Normalization
After EDA, the data is normalized using Min-Max normalization to scale all the numeric features between 0 and 1, facilitating better comparison and analysis.

## Correlation Analysis
The notebook also includes a correlation matrix table to explore the relationships between different indicators and identify potential correlations.

## Machine Learning - Linear Regression
Finally, the portfolio analysis includes machine learning using linear regression to predict the proportion of people living below 50 percent of median income based on selected economic and social indicators. The model is evaluated using mean squared error (MSE) and R-squared (R2) metrics.

Please note that this analysis is based on a specific dataset sourced from the World Bank and may be further extended or customized to include additional features or different machine learning algorithms as needed. The code in this notebook provides a comprehensive demonstration of how to preprocess, explore, visualize, and apply machine learning techniques to analyze a portfolio dataset.

For more details, refer to the Jupyter Notebook file in this repository.

## Dependencies
To run the code in this notebook, you will need the following Python libraries:

- pandas
- plotly.express
- sklearn

You can install these libraries using the following command:
pip install pandas plotly scikit-learn

## Usage
Clone the repository and open the Jupyter Notebook file in Jupyter or JupyterLab. Execute each cell sequentially to perform data preprocessing, EDA, visualization, normalization, and machine learning analysis.
