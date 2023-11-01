## Diamond Price Prediction
This repository contains a machine learning model for predicting diamond prices based on various features. The model is trained on a dataset containing information about diamonds, such as id, carat weight, cut, color, clarity, table and depth.

### Table of Contents
- Introduction
- Features
- Dataset
- Contributing
- License

### Introduction
Diamond Price Prediction is a machine learning project aimed at predicting the price of diamonds based on their characteristics. The project uses a regression model to estimate diamond prices, making it valuable for jewelers, buyers, and enthusiasts interested in understanding the factors influencing diamond pricing.

### Features
The model takes the following features into account for predicting diamond prices:

There are 10 independent variables (including id):
- id : unique identifier of each diamond
- carat : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
- cut : Quality of Diamond Cut
- color : Color of Diamond
- clarity : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
- depth : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
- table : A diamond's table is the facet which can be seen when the stone is viewed face up.
- x : Diamond X dimension
- y : Diamond Y dimension
- z : Diamond Z dimension

#### Target variable:
- price: Price of the given Diamond.

### Dataset
The dataset used for training the model is sourced from [ https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv ], containing a comprehensive collection of diamond data.

### Contributing
If you want to contribute to this project, please fork the repository and create a new branch for your changes. After making your changes, submit a pull request, describing the purpose of your changes.

### License
This project is licensed under the "MIT License" License - see the LICENSE file for details.
