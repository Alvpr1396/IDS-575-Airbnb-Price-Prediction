# IDS-575-Airbnb-Price-Prediction

# 1. Abstract

Nowadays, the number of people involved in staycation as a guest or host are rising. This situation produces availability in an alternative way that allows tourists to customize their rent plan and gain their experience. However, the accommodation price would become more competitive day by day due to high demand, especially in a big city like New York. This research performed with the purpose of acquiring the fittest model and competitive price for airbnb’s. The results emphasize the score of each room type (apt room/hotel room/shared room/private room). This research focuses on the linear model and other related models to determine how the price relates to any other factor. The correlation between Airbnb price and the room’s type showed how diverse the price for areas combined. The location of Airbnb is also a major factor of the price competitiveness compared to others. To make an analysis out of our datasets, we did exploratory Data Analysis (EDA) which was performed using matplotlib, pandas, and seaborn packages. After undergoing the data analysis on the datasets, we executed a linear regression model, SVR, gradient boost, etc to determine which model suits our objectives. Finally,  we evaluate the model using evaluation metric Root Mean Square(RMSE) and Median absolute Error (MAE) since it is less sensitive to outliers compared to other metrics.  The graph shows that most of the models are able to predict the price with a median error around 20 to 30 dollars.

# 2. Research Background

Airbnb is a short-term rental platform that allows you to rent out a portion or all of your living space to others. Airbnb has become a shining star in the sharing economy. Airbnb was valued at 113 billion dollars in 2021, up from 75 billion the year before. According to reports, Airbnb accounts for 5% of all tourism lodging revenue. Despite its commercial success, Airbnb has struggled to improve host pricing, potentially missing out on significant financial benefits. Airbnb hosts are predicted to lose up to 46% of additional revenue due to inefficient pricing, which has been cited as one of the company's top difficulties.
Although Airbnb has been developing pricing tools for hosts since 2012, these tools have been relatively basic and have solely focused on simple parameters such as the number of rooms, surrounding properties, and amenities such as parking. Airbnb has selectively launched a new pricing tool that takes both property qualities and demand into account, after years of work on a price algorithm. The pricing of Airbnb properties is complicated because, in addition to standard demand considerations such as seasonal changes, local events, and location, each Airbnb listing has its own unique qualities, and hosts frequently take on additional duties such as concierge, cook, and tour guide.
Airbnb listings face competition from other Airbnbs rather than hotels. It is assumed that potential clients have already decided to use Airbnb and are just looking at Airbnbs in the region, rather than comparing costs to adjacent hotels. Renters will choose other cheaper options if the host charges more than the market price. The hosts will lose out on potential earnings if the nightly rent price is set too low. As a result, we employ machine learning models to anticipate the best prices for the hosts' properties. Dynamic Pricing Optimization for Airbnb listing to optimize yearly profit for hosts. We've decided on three overall business goals to focus on for our project, which we'll expand on in the analytics goals and general model.

To strengthen our work background, we use another source of research related to this topic, which is predicting list prices on airbnb dataset. The purpose of this research is solely to generate competitive prices for a list of airbnb’s. Referring to this research, we would like to do some predictive analysis regarding the airbnb pricing with other approaches such as regression algorithms.

# 3. Methodology

# 3.1. Exploratory Data Analysis
Getting to know the patterns of the data using specific packages. The dataset was collected from kaggle which consist of Airbnb reservation details around the world.

# 3.2 Preprocessing
The preprocessing will be done by performing data cleansing on junk values and missing data. The next step to do is to separate the numerical and categorical columns. It also included with changing the categorical columns with numeric value.

# 3.3 Data Modelling
For these specific datasets I used several models and evaluation metric such as MSE and MAE to evaluate the model generated. Before validating each sets made by our models, I used Principal Component Analysis to reduce the features inside of Airbnb data.

