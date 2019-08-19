# Ecommerce-clothing-recommendation-prediction

**Goal : Predicting Ecommerce cloth Recommendation & Analyzing the reviews**

**Dataset** : [Kaggle women ecommerce clothing review](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)
## Motivation

1. Suggesting the business to significant words for recommended products
2. Suggesting the business to important categories and influencing factors in recommendedation
3. What kind of categories people have more negative reviews and what are they try to say
4. Correlation between Negative review and Recommendation

## Methodology 

0. **`Sentiment Analysis`** -  Finding the sentiments for reviews using lexical sentiment analysis approach.
⋅⋅⋅- Determine the approch - [Sentiment-analysis-tools-overview](https://medium.com/@datamonsters/sentiment-analysis-tools-overview-part-1-positive-and-negative-words-databases-ae35431a470c), [TextBlob](https://textblob.readthedocs.io/en/dev/)
- Find a way to validate  
1. **`Suggesting the business to significant words for recommended products`** - using TF-IDF in review extraction, building categorical model with reviews to predict recommendation then finding more weighted words.  
⋅⋅⋅-  Try to experiment with the different models and validate (Make sure model results are interpretable).  
2. `Suggesting the business to important categories and influencing factors in recommendedation` - using bag of words in product categories, building categorical model with reviews to predict recommendation then finding more weighted categories.  
⋅⋅⋅-  **Try to experiment with the different models and validate (Make sure model results are interpretable).**  
3. `What kind of categories people have more negative reviews and what are they try to say` - Apply sentimental analysis and find top TF-IDF in negative sentence and do topic modeling
4. `Correlation between Positive review and Recommendation` - using TF-IDF in positive review extraction, building categorical model with reviews to predict recommendation then finding more weighted words. 

*Optional : using Words embedding to combine the features [keras]*

## Aim for each phase 

- **Data Analysis :** Experiment our Business hypothesis with dataset. Find the pattens in dataset. Plan for Feature Engineering.
- **Data Preprocess :** Based on insights, start with preprocessing. Apply all regular NLP feature engineering (Tokens, stemming, lower letter and trimming). Apply TF-IDF & Bag of words for each words
- **Model Building & Validation :** Apply all possible models and validate with that. Validate with Cross matrix initially. It is efficient and easy to interpret more metrics.
- **Business Inference :** Try to interpret the results from modelt result. for `objective 3` , use topic modelling and extract the topics.

## Plan

|SI No|Plan Date|Topic|Start date|End date|Status|User|
|---|---|---|---|---|---|---|
|1|09.07|Get insights of data & Better Business understanding|||YTS|Balaji|
|2|09.07|Get insights of data & Better Business understanding|||YTS|Karuna|
|3|09.07|Discuss about insights|||YTS|Balaji & Karuna
|3|10.07|Plan for preprocessing & Model selection|||YTS|Balaji & Karuna|
|4|30.07|Feature Engineering 1|||YTS|Balaji|
|8|30.07|Feature Engineering 1|||YTS|Karuna|
|5|30.07|Discussion and planning |||YTS|Balaji & Karuna|
|6|16.08|Feature Engineering 2|||YTS|Karuna|
|7|16.08|Feature Engineering 2|||YTS|Balaji|
|8|16.08|Discussion and planning |||YTS|Balaji & Karuna|
|9|19.08|Apply all models|||YTS|Balaji|
|10|19.08|Apply all models|||YTS|Karuna|
|11|19.08|Discussion and planning |||YTS|Balaji & Karuna|
|12|22.08|Validating the models|||YTS|Balaji|
|13|22.08|Validating the models|||YTS|Karuna|
|14|22.08|Discussion and planning |||YTS|Balaji & Karuna|
|15|24.08|Buissness  inference|||YTS|Balaji|
|16|24.08|Buissness  inference|||YTS|Karuna|
|17|24.08|Discussion and planning |||YTS|Balaji & Karuna|
