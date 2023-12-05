You do not need to download the dataset to run the code. The program will do it for you.
You just need to run the code in .ipynb file.

Coding: Car PricePrediction.ipynb
Dataset: cars.cvs.zip 
Final Report: https://docs.google.com/document/d/1zhQrkWmJjjMU6wIfBC78MygGzp-XUrkaUOWALfyAL9Q/edit


Here is the list of libraries we used in our code:

    statsmodels.api - for statistical models and tests.
    numpy - for numerical operations and arrays.
    pandas - for data manipulation and analysis.
    matplotlib.pyplot - for creating visualizations and plots.

    SequentialFeatureSelector - from sklearn.feature_selection for feature selection.
    LassoCV and Lasso - from sklearn.linear_model for Lasso regression.
    Various metrics from sklearn.metrics - including mean absolute error, mean squared error, R-squared, and ROC curve display.

    LinearRegression - from sklearn.linear_model for linear regression.
    DecisionTreeRegressor, plot_tree, export_text - from sklearn.tree for decision tree regression.
    RandomForestRegressor and GradientBoostingRegressor - from sklearn.ensemble for ensemble methods.
    BART - from ISLP.bart for Bayesian Additive Regression Trees.
    SVR - from sklearn.svm for Support Vector Regression.

    Libraries for loading data using requests, zipfile, io, and os.
    StandardScaler and LabelEncoder - from sklearn.preprocessing for data preprocessing.
    seaborn - for additional data visualization, including heatmap.
    train_test_split and cross_val_predict - from sklearn.model_selection for splitting datasets and cross-validation.

Please install these libraries (statsmodels, numpy, pandas, matplotlib, sklearn, ISLP,seaborn, requests, zipfile, io, and os) 
before you run the program if needed.