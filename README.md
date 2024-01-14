# Meal_Behaviour_Analysis

**Problem Statement:**

A healthy lifestyle necessitates proper nutrition. Individuals maintain online meal logs to gain insights into their eating behaviors. The objective is to derive meaningful insights that empower users to comprehend and enhance their dietary patterns.


**Dataset:**

The analysis utilizes two datasets:

1. *Meal Log Data* (data.json): This dataset comprises human-generated meal entries recorded throughout the day. Each entry encompasses three attributes:
user_id: Unique identifier of the user submitting the meal log.
log_time: Timestamp indicating when the meal was logged.
description: Narrative description of the meal content.

2. *Food Corpus* (food_corpus.csv): This dataset catalogs various food items, encompassing vegetables, spices, and other edible substances.



**Data Processing:**

Following data loading and food corpus integration, the meal descriptions undergo tokenization, lemmatization, and keyword extraction. Tokenization divides sentences into individual words, while lemmatization reduces words to their root form, such as transforming "Cats" into "Cat." This process yields a list of keywords from the meal descriptions.

Data labeling categorizes the processed data into breakfast, lunch, or dinner based on the meal log time. It's important to note that meal logging time doesn't confirm the actual consumption time but rather indicates the time the meal description was entered.


**Insights from Meal Patterns:**

Analyzing meal patterns offers valuable insights into individual eating habits and potential health implications. The code incorporates various visualizations to elucidate the consumption patterns and their impact on the types and timings of food intake. Across all users and meal times, tea and coffee consistently emerge as the most frequently consumed beverages. Additionally, soup, salad, fruits, and vegetables demonstrate consistent presence in users' meal logs.

A notable distinction emerges in meal logging patterns between weekdays and weekends. Breakfast entries are disproportionately higher during weekends, indicating a potential shift in meal habits on non-work days. Lunch and dinner logs, on the other hand, exhibit comparable frequency across weekdays and weekends.
