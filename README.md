# Computational Techniques for Data Science

This course provides a practical introduction to the data science workflow using Python. Successful completion of the course will involve using advanced features of Python, retrieving information in data files, working with `numpy` and `pandas` library, visualizations with `matplotlib` and `seaborn`, and machine and deep learning with `scikit-learn`, `pytorch` (or `keras`).   Participants will complete an end to end data science project.  


## Data Science Process

One common data science project lifecycle is the OSEMN:

1. **Obtain** - query database, web scrape, web APIs, read file.  If it is big data, you will use: distributed storage like Apache Hadoop, or Spark. 
2. **Scrub** - clean, wrangle, replace, normalize, standardize, handle outliers, feature engineer. Big data may require MapReduce.
3. **Explore** - Exploratory Data Analysis (EDA).  Determine data types (categorical, numeric, ordinal, etc.).  Are there any correlated data?  Can you reduce the number of factors/dimensions?  Look for patterns.  Run summary statistics and plot.  
4. **Model and Assess** - Select machine learning method, tune hyperparameters, train, and cross validate.  Use Sci-kit Learn with python and CARET with R.  For regressions, be familiar with R-square to measure goodness-of-fit, and use error scores including MAE (Mean Average Error), or RMSE (Root Mean Square Error) to measure the distance between the predicted and observed data points.
5. **Interpret** - Present to non-technical persons, and actionable insight is a key outcome.  Data visualization include Matplotlib, ggplot, Seaborn, Tableau, d3js, etc.  


## End-to-End Machine Learning Process

Although there is no prescriptive process, here are the main steps you go through \cite{geron2022hands}:

1. Look at the big picture.
2. Get the data.
3. Discover and visualize the data to gain insights.
4. Prepare the data for Machine Learning algorithms.
5. Select a model and train it.
6. Fine-tune your model.
7. Present your solution.
8. Launch, monitor, and maintain your system.


## Textbook

Deitel, P., & Deitel, H. (2019). _Intro To Python for Computer Science and Data Science: Learning To Program with AI, Big Data and The Cloud_: Pearson.


```
@book{deitel2019intro,
  title={Intro To Python for Computer Science and Data Science: Learning To Program with AI, Big Data and The Cloud},
  author={Deitel, Paul and Deitel, Harvey},
  year={2019},
  publisher={Pearson Education}
}
```

## Other References
```
@book{geron2022hands,
  title={Hands-on machine learning with Scikit-Learn, Keras, and TensorFlow},
  author={G{\'e}ron, Aur{\'e}lien},
  year={2022},
  publisher={"O'Reilly Media, Inc."}
}
```

## Grade Assignments

The following are standard letter grade cutoffs.


| Range (in %)                   | Grade |
|--------------------------------|--------|
| 93 - 100                       |   A    |
| 90 - 92.9                      |   A-   |
| 87 - 89.9                      |   B+   |
| 83 - 86.9                      |   B    |
| 80 - 82.9                      |   B-   |
| 77 - 79.9                      |   C+   |
| 73 - 76.9                      |   C    |
| 70 - 72.9                      |   C-   |
| 67 - 69.9                      |   D+   |
| 63 - 66.9                      |   D    |
| 60 - 62.9                      |   D-   |
| < 60                           |   F    |

