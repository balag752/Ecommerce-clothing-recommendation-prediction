# Ecommerce-clothing-recommendation-prediction

**Goal : Predicting Ecommerce cloth Recommendation & Analyzing the reviews**

**Dataset** : [Kaggle women ecommerce clothing review](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)
## Motivation

1. Suggesting the buessiness to significant words for recommended products
2. Suggesting the buessiness to important categories and influencing factors in recommendedation
3. What kind of categories people have more negative reviews and what are they try to say
4. Correlation between Negative review and Recommendation

## Methodology 

1. `Suggesting the buessiness to significant words for recommended products` - using TF-IDF in review extraction, building categorical model with reviews to predict recommendation then finding more weighted words. 
2. `Suggesting the buessiness to important categories and influencing factors in recommendedation` - using bag of words in product categories, building categorical model with reviews to predict recommendation then finding more weighted categories.
3. `What kind of categories people have more negative reviews and what are they try to say` - Apply sentimental analysis and find top TF-IDF in negative sentence and do topic modeling
4. `Correlation between Positive review and Recommendation` - using TF-IDF in positive review extraction, building categorical model with reviews to predict recommendation then finding more weighted words. 

*Optional : using Words embedding to combine the features [keras]*

## Aim for each phase 

- **Data Analysis :** Experiment our Business hypothesis with dataset. Find the pattens in dataset. Plan for Feature Engineering.
- **Data Preprocess :** Based on insights, start with preprocessing. Apply all regular NLP feature engineering (Tokens, stemming, lower letter and trimming). Apply TF-IDF & Bag of words for each words
- **Model Building & Validation :** Apply all possible models and validate with that. Validate with Cross matrix initially. It is efficient and easy to interpret more metrics.
- **Business Inference :** Try to interpret the results from modelt result. for `objective 3` , use topic modelling and extract the topics.

## Plan

|SI No|Planned Date|Topic|Started date|End date|Status|User|
|---|---|---|---|---|---|---|
|1||Get insights of data & Better Business understanding|||YTS|Balaji|
|2||Get insights of data & Better Business understanding|||YTS|Karuna|
|3||Discuss about insights|||YTS|Balaji & Karuna
|3||Plan for preprocessing & Model selection|||YTS|Balaji & Karuna|
|4||Feature Engineering 1|||YTS|Balaji|
|8||Feature Engineering 1|||YTS|Karuna|
|5||Discussion and planning |||YTS|Balaji & Karuna|
|6||Feature Engineering 2|||YTS|Karuna|
|7||Feature Engineering 2|||YTS|Balaji|
|8||Discussion and planning |||YTS|Balaji & Karuna|
|9||Apply all models|||YTS|Balaji|
|10||Apply all models|||YTS|Karuna|
|11||Discussion and planning |||YTS|Balaji & Karuna|
|12||Validating the models|||YTS|Balaji|
|13||Validating the models|||YTS|Karuna|
|14||Discussion and planning |||YTS|Balaji & Karuna|
|15||Buissness  inference|||YTS|Balaji|
|16||Buissness  inference|||YTS|Karuna|
|17||Discussion and planning |||YTS|Balaji & Karuna|
