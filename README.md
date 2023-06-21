# Regression Analysis on Combined Cycle Power Plant Dataset

![Combined Cycle Power Plant](https://upload.wikimedia.org/wikipedia/commons/8/8d/Combined_Cycle_Gas_Fired_Power_Plant.jpg)

This project focuses on performing regression analysis on the "Combined Cycle Power Plant" dataset to estimate five types of regression models: multiple linear regression, polynomial regression, support vector regression, decision tree regression, and random forest regression. The goal is to determine the best model for predicting the electrical energy output of a combined cycle power plant using the determination coefficient.

## Data

The "Combined Cycle Power Plant" dataset contains the following features (variables):

- **Temperature (T):** The temperature measured in °C.
- **Ambient Pressure (AP):** The ambient pressure measured in millibars.
- **Relative Humidity (RH):** The relative humidity measured in percent.
- **Exhaust Vacuum (V):** The exhaust vacuum measured in cm Hg.
- **Electrical Energy Output (PE):** The electrical energy output of the power plant measured in MW.

You can find more information about the "Combined Cycle Power Plant" dataset at [UCI Machine Learning Repository](https://archive.ics.uci.edu/ "UCI Machine Learning Repository").

## Methodology

The regression analysis utilizes five regression models: multiple linear regression, polynomial regression, support vector regression, decision tree regression, and random forest regression. The determination coefficient (R-squared) is used as the evaluation metric to determine the performance of each model.

## Results

Based on the determination coefficients obtained for each model, the best-performing model for predicting the electrical energy output is [the random forest ](https://github.com/SantiagoMorenoV/Combined-Cycle-Power-Plant_Regs/blob/main/Models/Combined_Cycle_Power_Plant_Random_Forest_Reg.ipynb "the random forest ")regression. This model achieved the highest determination coefficient among all the models evaluated.

## Limitations and Future Work

One limitation of this analysis is that the determination coefficient was used as the sole metric for model selection. A further examination could consider other evaluation metrics or perform cross-validation to assess the models' generalization performance. Additionally, future work could explore feature engineering techniques or incorporate additional relevant variables to improve predictive accuracy.

## Usage

Feel free to use this code for your educational purposes.

## Contributions

Contributions to this repository are welcome. If you find a bug or have suggestions for improvement, please open an issue or submit a pull request.

## Credits

This project was created by **Santiago Moreno Velasquez** as part of an **Udemy Guided Project**.

## Acknowledgements 

**[UCI Machine Learning Repository](https://archive.ics.uci.edu/ "UCI Machine Learning Repository")** for providing the "Combined Cycle Power Plant" dataset.
