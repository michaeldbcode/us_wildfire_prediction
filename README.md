# Machine Learning for County-Level Wildfire Risk Prediction in California Through Optimised Classification Models

This repository contains mine and my group's work for our Data Analytics course where we analysed US wildfires, using the FPA dataset (1.88M records of wildfires between 1992-2015) and NASA's Daymet V4 Climate dataset.

Please see attached PDF paper for full write-up.

## Highlighted results:

<img width="350" alt="image" src="https://github.com/user-attachments/assets/2bba90c3-4f55-4f01-9a9f-ade0e2cc0fa2" />

<img width="350" alt="image" src="https://github.com/user-attachments/assets/64201219-a905-4044-8eb6-c2a1d69cd621" />

<img width="450" alt="image" src="https://github.com/user-attachments/assets/3344fb25-b365-47d3-b144-787eb03875b4" />



### Report conclusion:

From our analysis we have shown that our classification models perform strongly for wildfire prediction and can be leveraged by local fire management to properly allocate resources. Most notably, weather patterns are shown to be strong predictors for the total acres burned in counties, whereas historical data is treated as less important. This corresponds with the data referenced in our introduction regarding the abnormality of the 9 largest Californian wildfires occurring in the last 7 years, as well as the devastating effects of the LA wildfires in 2025. The practical problem of this field is how fire mitigation and protection plans should be addressed when wildfire causes consist of both man-made reasons and climate patterns, of which the latter is becoming increasingly unusual. The approach we took in this analysis was to focus on binary classification above a set threshold. This proved fruitful with respectably high-performance metrics across models and most importantly, very high recall scores when the cost matrix was optimised. Although our models fall short on exact accurate prediction of total acreage burned in respective counties, this was to be expected given the skewed, tailed distribution of wildfire data. Having said this, our EDA section provided useful insights into the causes and patterns of wildfires across the US, California and its Counties, and even Yosemite National Park. Notably, outside research on the vegetation and elevation of Yosemite Park helped the understanding of why certain areas were more prone to fire risk. We believe that further success could be found by analysing areas on a more granular level and using this to enhance the features of predictive ML models. A highlight from our research was the consistency in the various performance metrics of our models, indicating robustness and that our feature engineering was effective. The close performance of our simple and more complex models suggests less concern of overfitting.

We believe that data analysis and predictive ML models will continue to be integral in improving wildfire management in the U.S. by better informing budgets, policymakers, and fire management departments on the causes and patterns of wildfires. The strong AUC values of our model are valuable for practical use cases where the threshold for high/low fire risk may need to be adjusted subject to resource availability and risk tolerance. Further improvements to our EDA and ML models could be made through predominantly two channels: 1. Improving feature engineering further through the inclusion of more complex data and vegetation information. 2. Dealing with class imbalances on a county-level through stratified sampling or applying SMOTE (Synthetic Minority Oversampling Techniques).

