(Colab File)[WhatDrivesThePriceOfACar.ipnyb]

#Business Objective

The objective of this project is to create a model that can predict the price of a used car, given features as manufacturer, model, condition, cylinders, fuel, odometer, title status, transmition, drive, size, region, state.
This problem can be solved by building a regression model that takes as input the features that impact more significatly price, and predicts the estimate price as output.

#Results

Given that the RMSE is a high and the R² is only 0.44, the model is not perfect, but it already offers some insights into which factors are impacting on the price of used cars. However, to make more robust decisions, it is important to improve the model by using techniques such as:
Adding interactions or new features. A better knowing of the business that allow to determined what data could be affecting significativly the model. For example, why odometer has so many values = 0? We decided to delete those records of the Data but maybe there is an explanation for that.
A better understanding of the business that supported decision-making of which elements can be removed because they are not significant from the data used to generate the models. For example, we could determine together with the sellers what price range of used cars they want to evaluate from the data and is most relevant to our results.
We can also evaluate more complex models that require more processing power.
Even though the model has its limitations, you can get an idea of elements that affect the sale price of used cars. For example, the prices of used cars manufactured by Ferrari are much higher than the rest and increase the price of the cars.
We can also determine that in the State of Kentucky and in region Klamath Fallas and West Virginia (Old), used cars are sold at a significantly lower prices than the rest.
In the same way manufacturers such as Harley Davidson, Fiat, Saturn and Mitsubishui sell used cars much cheaper.
