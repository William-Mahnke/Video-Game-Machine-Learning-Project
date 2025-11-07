This repository contains the final product of my project for PSTAT131: Statistical Machine Learning. The goal of the project was to find a dataset of interest online and apply the machine larning techniques learned from the class. I sourced my dataset from Kaggle, a dataset about the sale of video games. Given the dataset contains observed variables (sales globally and across specific regions) the aim of the project was to create a variety of models to predict sales across different regions and compare their predictive accuracy. 

[Link to Data](https://www.kaggle.com/datasets/gregorut/videogamesales)

File Contents:
* data: contains data and codebook for the project
   * video_games.csv: data used for the entire project sourced from Kaggle
   * video_games_codebook: text file explaining the columns within video_games.csv
* models: contains saved models created during the project to save computational power and time
   * game_bf_tune.rda: set of boosted forest models with different parameter values
   * game_enet_tune.rda: set of elastic net models with different parameter values
   * game_knn_tune.rda: set of k nearest neighbors models with different parameter values
   * game_rf_tune.rda: set of random forest models with different parameter values
   * game_lm_fit.rda: linear regression model
   * game_final_bf.rda: final boosted forest model used by taking the highest performing model from game_bf_tune.rda
   * game_final_rf.rda: final random forest model used by taking the highest performing model from game_rf_tune.rda
* DataMemo.Rmd: first assignment in the project. the goal was to find a dataset we wanted to use and provide a breif explanation about the data set and overall goals for analysis and machine learning implementation
* Extra.Rmd: contains extra code created and used during the development of the final project but not included in the file report
* Project.Rmd: final project containing all work from EDA to testing the best two models 
