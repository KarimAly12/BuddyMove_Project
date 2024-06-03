In this project, we utilized the BuddyMove dataset, which contains data on 249 users. The dataset's first column contains user IDs, and the subsequent six columns represent the number of reviews each user has provided across six different types of destinations in South India: "Sports," "Religious," "Picnic," "Theatre," "Nature," and "Shopping." Since the dataset is initially unlabelled, I will assign labels to it based on the research question I aim to explore.

The primary research question is to investigate whether a user's interest in "Sports" destinations can be inferred from their interest in the other categories. For this purpose, users will be classified into two groups: those whose review counts for "Sports" are below the average will be labeled as "0," and those above the average will be labeled as "1."

The first step in this process was data cleaning to remove any errors, following a systematic approach to ensure consistency and accuracy, which is critical for the subsequent analysis and modeling.

Once the dataset was cleaned, I conducted an exploratory data analysis (EDA) to understand the distribution and relationships within the data. This involved generating visualizations to inspect the review counts across the six categories and examining pairs of attributes to test predefined hypotheses using both graphical methods and descriptive statistics.

After gaining insights from the EDA, I proceeded to the modeling phase, where I developed two classification models: a k-Nearest Neighbors (k-NN) classifier and a Decision Tree classifier. Both models were trained and validated to assess their performance.

The final step involved comparing the accuracy of the two models to determine which one better predicts user interest in "Sports" destinations based on their review patterns in the other categories. The results of this comparison will inform the recommendation of the most suitable model for this dataset, which will be presented at the conclusion of the report.
