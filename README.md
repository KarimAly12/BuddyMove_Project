The dataset employed in this project is the BuddyMove dataset, which contains information on 249 users. The first column lists user IDs, while the remaining six columns detail the number of reviews users have submitted across six different destination categories in South India: "Sports," "Religious," "Picnic," "Theatre," "Nature," and "Shopping." As the dataset is unlabelled, I will generate labels based on the research question at hand.

The objective of my research is to determine if it's possible to predict users' interest in "Sports" destinations based on their interest in the other categories. Users will be categorized into two groups: those with a number of reviews in the "Sports" category below the average will be labeled "0," and those with counts above the average will be labeled "1."

Initially, I cleaned the dataset to ensure it was free of errors, following a systematic cleaning process rather than an ad-hoc approach. This step is crucial for effective data exploration and modeling.

With the cleaned dataset, I explored the review counts in the six destination categories using visualizations to gain a deeper understanding of the data. I also analyzed ten pairs of attributes, defined by a hypothesis, using graphs and descriptive statistics to test the validity of the hypothesis.

Subsequently, I trained two models: a k-Nearest Neighbors (k-NN) classifier and a Decision Tree classifier. Both models were validated and their accuracies compared. The report concludes with a recommendation of the more accurate model for this dataset.
