## Crop-Recommendation-Project
Smart Crop Recommendation System that leverages machine learning to optimize crop selection based on integrated soil and weather parameters. With growing challenges in agriculture due to climate change, poor soil health, and inefficient resource use, intelligent decision-support tools are essential for enhancing productivity and sustainability. The system utilizes key features such as nitrogen, phosphorus, potassium, pH, temperature, humidity, and rainfall to predict the most suitable crops for a given region. Multiple models were trained and evaluated, including Random Forest, Gradient Boosting, Support Vector Machine (SVM), and Logistic Regression. To further improve performance, a stacking ensemble of Random Forest and Gradient Boosting was implemented, achieving superior results. The ensemble model reached an impressive accuracy of 99.09%, demonstrating robustness and effectiveness across diverse agricultural conditions. The solution is deployed via a web-based interface using Flask, enabling easy access and real-time recommendations for farmers. This AI-powered system supports data-driven agricultural planning, increases yield potential, reduces risks related to climate variability, and promotes sustainable farming practices. By providing precise, region-specific crop recommendations, this system empowers farmers to make informed decisions, contributing to both economic growth and food security.

## Data Used
https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

## Process
1. Here The farmers can directly enter the n, p, k, Ph and climatic values and get the prediction of the recommended crop
2. n, p, k, ph values can be found using the sensors and if sensors are not available the farmers can reach out to nearest govt support centers to get their soil tested.
3. and the climatic values are the expected temparature for the entire season can be found from the weather department.

## Future Improvements
1. Can collaborate with any weather department and if farmer enter the location of the farm land the climatic values should be automatically filled.
2. Provide a kit to the farmer with the required sensors that monitor the soli features 24/7.
3. Thesse two improvements can drastically improve the real time accuracy of the model. 
