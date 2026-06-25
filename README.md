SOM-Based Country Clustering

Overview

This project explores how Self-Organizing Maps (SOM) can be used to group countries according to selected numerical indicators. Instead of assigning countries to predefined categories, the model learns patterns from the data itself and places similar countries closer to each other on a two-dimensional map.

The project was prepared as an unsupervised machine learning study. Its main purpose is not only to build a clustering model, but also to understand how multidimensional country-level data can be interpreted visually.

Motivation

Country-level datasets often include many variables at the same time, such as demographic, economic, social, or development-related indicators. When these variables are analyzed together, similarities between countries may not be easy to observe with basic tables or direct comparisons.

Self-Organizing Maps provide a useful way to reduce this complexity. By mapping high-dimensional data onto a simpler visual structure, SOM can make hidden relationships more understandable. This makes the method suitable for exploratory analysis, especially when the goal is to observe patterns rather than predict a fixed target label.

Methodology

The workflow of the project includes:

* Loading and reviewing the dataset
* Selecting relevant numerical features
* Cleaning and preparing the data
* Applying normalization to make variables comparable
* Training a Self-Organizing Map
* Mapping countries onto the SOM grid
* Visualizing the clustering structure
* Interpreting similarities between country groups

Since the project is based on unsupervised learning, no target label was used during model training. The clustering behavior was shaped by the selected input features and their distribution within the dataset.

Machine Learning Approach

The main method used in this project is the Self-Organizing Map. SOM is a neural network-based clustering technique that projects high-dimensional data into a lower-dimensional space while trying to preserve the relationships between data points.

In this project, SOM was used to examine whether countries with similar characteristics would appear close to each other on the map. This provided a more visual and interpretable way to analyze country similarities.

Results and Interpretation

The results suggest that countries with similar indicator patterns tend to be positioned near each other on the SOM grid. This helped reveal groups of countries that share comparable characteristics based on the selected features.

The visual outputs are included in the `results/` folder. These figures are intended to support the interpretation of the clustering structure and make the model output easier to understand.

Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* MiniSom
* Jupyter Notebook

Project Structure

```text
som-country-clustering/
├── README.md
├── requirements.txt
├── notebooks/
├── data/
├── results/
└── docs/
```

Dataset

The dataset used in this project contains country-level numerical indicators.

Raw dataset files are not included in this repository if redistribution is restricted or if the original source requires separate access. When available, the dataset source should be cited in this section.

Future Improvements

This project can be improved by:

* Testing different SOM grid sizes
* Comparing SOM results with other clustering methods such as K-Means
* Adding more country-level indicators
* Improving the visual presentation of the clusters
* Providing a deeper interpretation of each country group
* Creating an interactive visualization for easier comparison

Author

Bensu Varol
MSc Computer Engineering Student
Research interests: Machine Learning, Deep Learning, Medical Image Analysis, Computer Vision, and Explainable AI
