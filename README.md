# CaliforniaHousingPrices

- What is the business objective?
  - The model will be a prediction of a district's median housing price
  
- How does the company expect to use and benefit from this model?
  - my models output will be fed into another machine learning model downstream that will determine whether it is worth investing in a given area. Getting this model correct directly affects revenue of the company
- What does the current solution look like? I'm asking this to get a reference for performance and some insights to solving the problem?
  - The district housing prices are currently estimated manually by experts 
  - when they cannot get the median housing price they estimate it using complex rules
  - costly, time-consuming, inaccurate (estimates were off by about 30%) which is why the company thinks it would be useful to train a model that can predict a district's median housing price.

-The Census Data seems to be a good source for data because it includes the median housing prices for thousands of districts along with other potentially useful features

- Training Supervision for model:
  - Supervised Learning: the can clearly be trained with labeled examples
- Classification or Regression Task or something else?
  - Regression: because the model with be expected tp predict a value
  - Multiple Regression specifically because were using multiple features to predict a value
  - Uni-variate Regression specifically because we are only predicting a single value for each district.
- Batch Learning or Online Learning?
  - Batch Learning: online learning wouldn't make sense because there is no new data coming into the system and the environment is not rapidly changing