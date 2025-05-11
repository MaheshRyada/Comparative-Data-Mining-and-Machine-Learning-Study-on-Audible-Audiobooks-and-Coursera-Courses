# Comparative-Data-Mining-and-Machine-Learning-Study-on-Audible-Audiobooks-and-Coursera-Courses

# Project 1: Audible Audiobooks Dataset Analysis & Classification

**Overview**

This project analyzes, cleans, and models the Audible audiobook dataset from Kaggle. It covers:

- Data cleaning (parsing dates, prices, ratings, etc.)
- Exploratory Data Analysis (EDA) with visualizations
- Additional feature engineering
- Predictive modeling (classification of high vs low star rating)
- Model performance evaluation and comparison

**Files Included**
- audible_analysis.ipynb - Main Jupyter notebook containing data loading, cleaning, EDA, feature - engineering, model training and evaluation.
- audible_uncleaned.csv (downloaded via notebook — not included in repo; fetched from Kaggle)

**Requirements & Dependencies**
- Python 3.7+
- KaggleHub (kagglehub)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (sklearn)
- re
- datetime

*To install dependencies:*
`pip install pandas numpy matplotlib seaborn scikit-learn kagglehub`

*Executing the Notebook*
1. Download Dataset:
You must have Kaggle API credentials set up. The dataset is fetched automatically by running the first cell of the notebook:

```
import kagglehub

snehangsude_audible_dataset_path = kagglehub.dataset_download('snehangsude/audible-dataset')
```

You may remove this cell if running locally with the CSV file already downloaded.

2. Run cells in sequence:
Execute each section to perform data cleaning, EDA, feature engineering, and modeling.

3. View Results:
All visualizations, tables, and model evaluation metrics will be displayed inline as notebook output.

# Project 2: Coursera Courses Dataset (Clustering & Classification)

**Overview**

This project works with the Coursera courses dataset from Kaggle, performing:

- Data cleaning and preprocessing (handling text and missing values)
- Exploratory Data Analysis (EDA) including feature engineering and visualizations
- Dimensionality reduction and clustering with TF-IDF + SVD + KMeans
- Building machine learning pipelines for classification (high rating prediction)
- Model selection and evaluation

**Files Included**
- coursera_courses_pipeline.ipynb - Main Jupyter notebook for the entire pipeline: data preprocessing, EDA, feature construction, modeling, and evaluation.
- duplicate_deleted.csv (Coursera dataset, downloaded via notebook — fetched from Kaggle)
(All generated figures and results are within notebook output.)

**Requirements & Dependencies**
- Python 3.7+
- KaggleHub (kagglehub)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (sklearn)
- wordcloud
- scipy

*To install dependencies:*

`pip install pandas numpy matplotlib seaborn scikit-learn kagglehub wordcloud scipy`

*Executing the Notebook*
1. Download Dataset:
The notebook fetches the dataset using KaggleHub with:
```
import kagglehub
janakpariyar_coursera_courses_uncleaned_dataset_to_practice_path = kagglehub.dataset_download('janakpariyar/coursera-courses-uncleaned-dataset-to-practice')
```
You may remove/comment this cell and load your own CSV locally if preferred.

2. Run all cells:
Cells are to be executed top to bottom. The pipeline performs all preprocessing, modeling, and outputs insights, plots, and model metrics inline.

3. Interpret Results:
Key visualizations and outputs like word clouds, cluster plots, confusion matrices, and classification reports are displayed within the notebook.
