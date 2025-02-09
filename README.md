[Colab File](WhatDrivesThePriceOfACar.ipynb)

# Business Objective

The goal of this project is to develop a model that predicts the price of a used car based on various features, such as manufacturer, model, condition, cylinder count, fuel type, odometer reading, title status, transmission type, drive configuration, size, region, and state. This problem can be addressed by building a regression model that identifies the most significant features affecting price and uses them to generate an accurate price estimate as the output

# Results
The best model we found explains 44% of the variation in used car prices based on the variables included. With a coefficient of determination (R²) of only 0.44, the model is not perfect, but it provides some useful insights into the factors influencing used car prices. However, to make more reliable decisions, it's important to enhance the model using techniques such as:

Adding interactions or new features: Gaining a deeper understanding of the business can help identify additional data points that might significantly impact the model. For example, the high number of odometer readings equal to zero raises questions. While we chose to remove these records, there could be a specific reason behind this anomaly that warrants further investigation.

Refining business knowledge for decision-making: It's essential to collaborate with stakeholders to determine which elements of the data may be irrelevant or redundant for our model. For instance, by working with sellers, we could define a specific price range of used cars that should be considered in our analysis to ensure that the model focuses on the most relevant information.

Exploring more complex models: We could consider implementing more advanced models that require higher computational power, which might offer better performance and insights.

Despite its limitations, this model still provides valuable information on the factors that affect used car prices. For example, cars from manufacturers like Ferrari significantly increase the price of used cars. We also see that used cars in states like Kentucky, and regions such as Klamath Falls and West Virginia (Old), are sold at notably lower prices compared to other areas. Similarly, manufacturers like Harley Davidson, Fiat, Saturn, and Mitsubishi tend to offer used cars at much lower prices.
