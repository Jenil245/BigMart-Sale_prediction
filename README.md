# Bigmart Sale Prediction

# About Project

This problem statement is part of a hackathon which was hosted by analytics vidhya.

Dataset contains <b>8523 entries</b> and <b>12 columns</b>. We have 7 categorical columns and 5 numerical columns. We have to predict bigmart sales based on given features.

<h2>Project LifeCycle</h2>
<ul>
  <li>
    <b>Data Cleaning</b>: I replaced null values based on distribution of particular column. While exploring categorical data, I found that one of the column contained <b>error in labeling</b>. Different type of term were used for one specific label. I handle it by map funtion. Then I removed outliers. 
  </li>
<li>
  <b>DATA VISUALIZATION</b>: I visualized data with python seaborn-package which allows to create very good chart for statistical analysis. For inspecting numerical columns, I used box plots and histograms. Then I used barplot to see count distribution of categorical columns. Finally, I researched relationship between feature variable and target variable with pairplot.</li>
  <li>
    <b>FEATURE ENGINEERING</b>: I used various techniques to transform data so that it can be fed into model which are scaling, encoding, etc.
  </li>
  <li>
  <b>MODEL DEVELOPEMENT</b>:
  I used XGBoost algorithm which is a very powerful ensemble boosting approach. I performed hyperparameter tuning to optimize model performance.  </li></ul>
   
