# Dev10 Capstone

## Authors

Shervorn Mathews, Aditya Palapati, Jin Hee Lee, Janeel Abrahams

## Requirements

A requirements.txt containing the latest version of each library as of 5/19/2023 has been included with this repository.

Run the following command in your terminal to automatically install the libraries:

`pip install -r requirements.txt`

## Project Overview

The relationship between food consumption and health is a topic of significant importance in today's society. The nutritional composition of foods plays a crucial role in determining their impact on our overall well-being. In this report, we will analyze the nutrient composition of various food groups using food datasets sourced online. By examining key factors such as energy content, protein, fat, carbohydrates, and other essential nutrients, we aim to gain insights into the relationship between food and health outcomes.

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\janeel1.png" align="center">
</p>

<p align="center" >Figure 1 - Energy vs Carbs</p>

In addition, an examination of the rate at which crops are harvested over time provides an opportunity to identify potential points of interest. Analyzing the trends and changes in crop harvesting rates can offer insights into agricultural practices, food production, and potential correlations with obesity rates. By studying patterns in crop yields and harvest rates, we can explore any potential relationships between food production, availability, and obesity prevalence. 

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\adi1.png" align="center">
</p>

<p align="center" >Figure 2 - Area Harvested Over Time</p>

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\adi2.png" align="center">
</p>

<p align="center" >Figure 3 - Crop Production Per Year in US</p>

Crop production has been steadily increasing in an upwards trend and continues to do so. Crop production is very important but the yields give us a better understanding of just how much of these crops become available to consumers. Through Figures 2 and 3 we can see while some crop yields have stayed stagnant over the years of analysis, others have followed upward trends as well with sugarcane and tomatoes providing the greatest yield.

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\adi3.png" align="center">
</p>

<p align="center" >Figure 4 - Confusion Matrix for Random Forest Model</p>

Through soil data analysis within the US we can ascertain whether certain fruits, vegetables, or grains would thrive in certain conditions. By taking the data we are able to create a model considering different growing aspects, such as soil pH levels, nitrogen, phosphorous, and potassium concentrations as well as temperature, rainfall, and humidity. A logistic regression, decision tree, and random forest model has been created followed by cross validation techniques to ensure the models are low in bias and variance. To visually show this, a confusion matrix was created on our random forest model to show just how accurate it is. Through the use of this modeling we can assist farmers to determine the best crops to be grown while considering their nutritional content as well.

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\adi4.png" align="center">
</p>

<p align="center" >Figure 5 - Crop Yields in the US Over Time</p>

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\shervorn1.png" align="center">
</p>

<p align="center" >Figure 6 - Obesity Percentage By State (2020)</p>

The presented figure portrays the prevalence of obesity across US states, delineating a discernible pattern wherein the southeastern region exhibits a notably higher incidence of obesity. Conversely, the western states demonstrate comparatively lower rates of obesity. Intriguingly, the data highlights outliers in the form of Colorado and Massachusetts, where the prevalence of obesity is strikingly minimal, while Alabama and Mississippi emerge as states grappling with the highest obesity rates. This stark contrast invites a compelling investigation into the comparative statistics of these regions, promising insightful findings.

<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\shervorn2.png" align="center">
</p>

<p align="center" >Figure 7 - Obesity Rate Over Time (2011 - 2020)</p>

The provided figure presents a comparative analysis of obesity percentages in Alabama, Colorado, Massachusetts, Mississippi, and the national average, spanning the years 2011 to 2021. Notably, a consistent 15% disparity persists between states with higher obesity rates (Alabama and Mississippi) and those with lower rates (Colorado and Massachusetts) throughout the examined period. Furthermore, both the higher and lower states exhibit a proximity of approximately 7% deviation from the national average. Remarkably, an average incremental rise of 5% is discernible in the obesity rates over the course of the ten-year duration.


<p align="center" style="margin-bottom: 0px !important;">
  <img width="700" src="images\shervorn3.png" align="center">
</p>

<p align="center" >Figure 8 - Food Consumption Over Time in the USA (1970 - 2021)</p>

A notable trend observed over time is the increase in the amount of food consumed per person per year, accounting for population growth. This significant rise in food consumption serves as a potential contributing factor to the increase in obesity rates. The concurrent changes in dietary habits and portion sizes may play a role in the escalating prevalence of obesity over time.

## Data Bricks

[Kafka (create topic, producer, consumer)](https://adb-3129302285465110.10.azuredatabricks.net/?o=3129302285465110#notebook/2870419301879715/command/2870419301879857)

[Azure Data Factory for Kafka](https://adf.azure.com/en/monitoring/pipelineruns?factory=%2Fsubscriptions%2Fd71849c0-0faa-4a3f-95c3-e2b84232c9f7%2FresourceGroups%2Fcohort50rg%2Fproviders%2FMicrosoft.DataFactory%2Ffactories%2Fjlee-datafactory)

[Health Outcome Databrick](https://adb-3129302285465110.10.azuredatabricks.net/?o=3129302285465110#notebook/796925177194531/command/4465790401556867)

## Data Sources

[USDA National Nutrient DB](https://data.world/craigkelly/usda-national-nutrient-db)

[Hunger and Undernourishment](https://ourworldindata.org/hunger-and-undernourishment)

[Malnutrition Data](https://data.unicef.org/resources/dataset/malnutrition-data/)

[Health, Nutrition and Population](https://datatopics.worldbank.org/health/health)

[Global Food & Agriculture Statistics](https://www.kaggle.com/datasets/unitednations/global-food-agriculture-statistics?select=fao_data_crops_data.csv)

[Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

[Local Data for Better Health, County Data](https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-County-Data-20/swc5-untb)
             
[Local Data for Better Health, County Data 2022](https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-County-Data-20/swc5-untb)

[Health searches by US Metropolitan Area, 2005-2017](https://www.kaggle.com/datasets/GoogleNewsLab/health-searches-us-county)

[Obesity Survey Data](https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/data)

[Food Consumption Data](https://www.ers.usda.gov/data-products/food-availability-per-capita-data-system/)