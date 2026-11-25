# Project2
## Project description

This project uses decision tree regressor and one random forest regressor to predict the total expenses of an institution’s women’s athletic teams.

The data set is from Equity in Athletics Data Analysis database, maintained by the Office of Postsecondary Education of the U.S. Department of Education

## Data

- 2040 Athletics institutions and 4275 predictors
- 65 missing values
- Predictors used: the institution’s athletic classification and sector (public four-year or private nonprofit), the number of male and female undergraduates, the number of women and men participating in athletics, the number of head and assistant coaches, and participation in selected sports such as women’s basketball, soccer, volleyball.

## Methods

Two regression models
- Decision Tree
- Random Forest

## Main Finding

The predicton uses data from 2024 Equity in Athletics (EADA) survey and the target is to predict the total expenses of women's athletic teams at U.S institutions. The random forest had the best output, with test RMSE of 1.484 million compared with 2.023 million for the decision tree. Cross-validation showed that adding number of estimators reduced the train error and the best depth = 8. The final forest (100 trees and 8 depths) had the best Test RMSE of 1.477 millions. One limitation is that the for this prediction I choose only few sports and no others variables, such as revenue, so different groups might explain better the expending.
