# Fitness-App-Sentiment-and-Feature-Insights-Dashboard
Fitness app product analytics case study using Python and Power BI. Analyzes app reviews for sentiment, feature level pain points, and feature requests, then applies RICE and experiment design to propose a data driven product roadmap.

Fitness App Review Analytics and Product Roadmap Dashboard

# Overview  
This project is an end to end product analytics case study built around user reviews of health and fitness apps.  
The goal is to turn unstructured review text into clear insights on sentiment, feature level pain points, and a data driven feature roadmap for a fitness app product.

# Key Objectives  
-  Quantify overall user satisfaction and sentiment.  
-  Identify which features users love and which cause friction.  
-  Prioritize feature requests using a structured framework.  
-  Design an experiment to validate the impact of a high priority feature.

# Dataset and Processing  
-  Source: Public app reviews and ratings for multiple Health and Fitness apps from the Google Play Store.  
-  Fields: App name, review text, rating, and related metadata.  
-  Processing:  
  - Text cleaning and tokenization.  
  - Sentiment scoring at review level.  
  - Emotion tagging, for example joy, sadness, anger.  
  - Keyword extraction with TF IDF.  
  - Feature tagging, mapping reviews to feature categories such as Offline Mode or Progress Tracking.  
-  Output: Cleaned, enriched dataset loaded into Power BI for analysis and visualization.

# Dashboard Pages and Insights

# 1. Sentiment Overview  
Focus: Overall health of user feedback.  
Highlights:  
-  Distribution of positive, negative, and neutral reviews.  
-  Average rating and sentiment status over time.  
-  Overall sentiment trend versus previous period.  
-  Health and Fitness apps download trend to provide market context.  
Questions answered:  
-  How satisfied are users overall.  
-  Is sentiment improving or declining.  
-  Does user satisfaction track with app market growth.

# 2. App and Rating Insights  
Focus: App level performance and rating behavior.  
Highlights:  
-  Sentiment breakdown by rating bucket, for example how many negative reviews sit inside 5 star ratings.  
-  Rating distribution across 5 star and 4 star reviews.  
-  Top apps by review volume.  
-  Relationship between review length and sentiment polarity.  
Questions answered:  
-  Which apps get the most feedback.  
-  Where ratings hide underlying dissatisfaction.  
-  How detailed reviews relate to sentiment.

# 3. Feature Level Sentiment and Volume  
Focus: Features that drive love or frustration.  
Highlights:  
-  Average sentiment score by feature category, for example Offline Mode, Calorie and Nutrition, User Interface, Workout Tracking, Bugs and Technical.  
-  Mention volume by feature category.  
-  Feature sentiment distribution, share of positive versus negative mentions per feature.  
-  Loved features versus pain points view.  
Questions answered:  
-  Which features users value most.  
-  Which areas cause the most friction.  
-  Where product and engineering teams should focus effort.

# 4. Keyword and Topic Exploration  
Focus: User language and themes.  
Highlights:  
-  Word cloud of most frequent keywords, such as app, great, love, exercise, calories, fitness, ads, gym.  
-  Top keywords by TF IDF to surface distinctive terms.  
Questions answered:  
-  What users talk about most often in their own words.  
-  Which concepts are most associated with strong sentiment.

# 5. Feature Requests and Emotions  
Focus: Demand for new features and emotional drivers.  
Highlights:  
-  Feature request frequency for key features such as:  
  - Advanced Nutrition and Meal Planning.  
  - Rest Timer Between Sets.  
  - Video Exercise Demonstrations.  
  - Wearable Integration, for example Apple Watch or Fitbit.  
  - Offline Mode.  
-  Emotion distribution across reviews, for example share of joy, sadness, anger.  
Questions answered:  
-  Which feature requests show the highest demand.  
-  What emotions dominate the current user base.

# 6. RICE Prioritization and Roadmap  
Focus: Turning insights into a roadmap.  
Highlights:  
-  RICE scoring table with Reach, Impact, Confidence, Effort, and final RICE score for each candidate feature.  
-  Effort versus impact matrix to categorize quick wins and strategic bets.  
-  Priority matrix and ranked feature development roadmap, for example:  
  - Advanced Nutrition and Meal Planning.  
  - Offline Mode.  
  - Rest Timer Between Sets.  
  - Other supporting features.  
Questions answered:  
-  Which features to build first under a fixed capacity.  
-  How to balance high impact features with low effort wins.

# 7. Experiment Design for a Key Feature  
Focus: Validating roadmap decisions with experimentation.  
Highlights:  
-  A or B test design for Advanced Nutrition and Meal Planning.  
-  Primary metric, for example day 7 retention rate.  
-  Minimum detectable effect and required sample size per group.  
-  Minimum test duration and a power curve showing sample size versus detectable effect.  
Questions answered:  
-  How large the experiment needs to be.  
-  How long it should run.  
-  What uplift counts as a successful outcome.

# Tech Stack  
-  Data processing and NLP: Python.  
-  Data storage: Processed tables exported for analysis.  
-  Visualization: Power BI for interactive dashboards and drill through views.  
-  Product frameworks: RICE scoring, impact and effort matrices, and experiment design templates.

# How to Read the Dashboard  
-  Start with the Sentiment Overview to understand overall product health.  
-  Move to Feature Level Sentiment to pinpoint specific strengths and weaknesses.  
-  Check Feature Requests and RICE pages to see the proposed roadmap.  
-  Review the Experiment Design section to understand how to validate the roadmap with data.

# Use Cases  
-  Product managers, prioritize features and communicate a roadmap anchored in user voice.  
-  Data analysts, demonstrate end to end skills from NLP to BI and product decision support.  
-  Stakeholders, quickly understand where to invest engineering capacity for maximum user impact.
