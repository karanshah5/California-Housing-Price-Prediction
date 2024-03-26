# California Housing Price Prediction

This project aims to predict the median house value for districts in California using machine learning techniques, particularly linear regression.

## Implementation Details

- **Dataset**: California Housing Dataset
- **Model**: Linear Regressor
- **Input Features**: Median Household Income, House Age, Average Rooms, Average Bedrooms, Population, Average Occupancy, Latitude, Longitude
- **Output**: House Price

## Dataset Details

The dataset used in this project is obtained from the StatLib repository, derived from the 1990 U.S. census. It contains information on various factors influencing house prices, such as median income, house age, population, etc. The dataset comprises 20640 samples with 8 input features and the target variable being the median house value for California districts.

## Evaluation and Results
![alt text](https://github.com/karanshah5/California-Housing-Price-Prediction/blob/main/results/Simple%20linear%20regression%20plot.png)

As you can see from the above image, the model has a significant amount of error in regions corresponding to lower median incomes.


| Metric   | Simple Linear Regression | Multiple Linear Regression |
|----------|--------------------------|----------------------------|
| R2 Score | 0.446                    | 0.594                      |
| MSE      | 0.721                    | 0.528                      |


The above quantitative results show that:

- The simple linear regression model demonstrates moderate explanatory ability and prediction accuracy.

- The multiple linear regression model exhibits improved performance in explaining variance and predicting house prices compared to the simple model.

## Key Takeaways

This project provided practical experience with linear regression and multiple linear regression, offering valuable insights applicable to various predictive modeling tasks.

## How to Run

The code is built on Google Colab on an iPython Notebook. 

```bash
Simply download the repository, upload the notebook and dataset on colab, and hit play!
```

## Roadmap

Future modifications planned for this project include:

- Experimentation with additional machine learning models.
- Implementation of feature selection techniques.

## Libraries 

**Language:** Python

**Packages:** 
- Scikit-learn
- Matplotlib

## FAQ

#### How does the linear regression model work?

Linear regression primarily utilizes the least squares method to find the line that best fits the data. This method minimizes the error represented by the objective function J, aiming to reduce the distance between the observed data points and the fitted line. By minimizing J, linear regression determines the optimal values of the coefficients w and b, ensuring the lowest possible error and the best fit for the data.

#### How do you train the model on a new dataset?

To train the model on a new dataset, utilize the fit method of the model instance, providing the training features and target values, following data loading, preprocessing, and splitting procedures.

#### What is the California Housing Dataset?

The California Housing Dataset contains information on various socio-economic factors influencing housing prices in California, such as income, population, and location.


## Contact

If you have any feedback or are interested in collaborating, please reach out to me at karanshah51101@gmail.com.

## License

[MIT License](LICENSE)

