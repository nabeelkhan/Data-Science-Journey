Copyright (c) 2020, [Nabeel Khan](https://www.nabeelkhan.com)
All rights reserved.

# What is Data Science?

The human brain has a highly complex and non-linear parallel computer that can organize the structural constituents i.e. the neurons interconnected in a complex manner between each other. Let us take a simple example of face recognition-whenever we meet a person, a person who is known to us can be easily recognized with his name or he works at XYZ place or based on his relationship with you. We may be knowing thousands of people, the task requires the human brain to immediately recognize the person (face recognition). Now, suppose instead of the human brain doing it, if a computer is asked to perform this task. It is not going to be an easy computation for the machine as it does not know the person. You have to teach the computer that there are images of different people. If you know 10,000 people then you have to feed all the 10,000 photographs into the computer. Now, whenever you meet a person you capture an image of the person and feed it to the computer. The computer matches this photograph with all the 10,000 photographs that you have already fed into the database. At the end of all the computations-it gives the result with the photograph that best resembles the person. This could take several hours or more depending on the number of images present in the database. The complexity of the task will increase with increase in the name of images in the database. However, a human brain can recognize it instantly.

# What is Machine Learning?

Artificial Intelligence is used in business through machine learning algorithms. Machine learning is a part of computer science focused on computer systems learning to perform a specific task without using explicit instructions, relying on patterns and inference instead.

Machine learning algorithms detect patterns and learn how to make predictions and recommendations by processing data, rather than by receiving explicit programming instructions (‘if-then’ loops). The algorithms improve over time with new data coming in, ‘learning’ through examples.

Machine learning is primarily used in:

- **Descriptive**: _What happened_?
- **Prescriptive**: _What should be done to achieve goals_?
- **Predictive**: _What will happen_?

### How we are using Machine Learning

We are using machine learning to identify spending patterns of customers, what time of the day, what day of the week, weather conditions, type of coupons, etc. there are multi-dimension of data that we label and later analyze to predictive the behavioral model.

Most recently we developed a proto-type for Australian Suicide Prevention Society, a mobile app, which analysis the in-app chat and provides the scoring on suicidal and depression level based on certain ranking used on semantics and pragmatics. the model provides three basic and distinctive information. The ranking and scorings are defined by CBT authorities.

### Customer Service Agent Case Study

1. Leverage Natural Language Processing and machine vision to identify customers to contact and respond to them automatically or assign them to relevant agents increasing customer satisfaction.
2. Seamlessly but securely authenticate your customers. Voice authentication allows you to authenticate customers without passwords leveraging biometry to improve customer satisfaction and reduce issues related to forgotten passwords.
3. Ensure that the agent you assign to a customer has the expertise and style which matches the needs of that customer behavior.
4. Call classification systems to leverage Natural Language Processing to understand what customer is trying to achieve enabling your agents to focus on higher value-added activities and enable you to better match agents and customers
5. Intelligent call routing systems route calls to the most capable agent available. Intelligent routing systems incorporate data from all customer interactions optimizing customer satisfaction.
6. Leverage Natural Language Processing and machine learning to estimate and manage customer's intent (e.g., churn) to improve customer satisfaction and business metrics

## Which Data Science / Machine Learning methods and algorithms used in for a real-world application?

1. Regression
2. Decision Trees / Rules
3. Clustering
4. Visualization
5. Random Forests
6. Statistics - Descriptive
7. K-Nearest Neighbors
8. Time Series
9. Ensemble Methods
10. Text Mining
11. PCA
12. Boosting
13. Neural Networks - Deep Learning
14. Gradient Boosted Machines
15. Anomaly / Deviation Detection
16. Neural Networks - Convolutional Neural Networks (CNNs)
17. Support Vector Machine (SVM)

Machine Learning Algorithms Every Engineer Should Know

1. Naïve Bayes Classifier Algorithm
2. K Means Clustering Algorithm
3. Support Vector Machine Algorithm
4. Apriori Algorithm
5. Linear Regression
6. Logistic Regression
7. Artificial Neural Networks
8. Random Forests
9. Decision Trees
10. Nearest Neighbours

### Naïve Bayes Classifier Algorithm

It would be difficult and practically impossible to classify a web page, a document, an email, or any other lengthy text notes manually. This is where the Naïve Bayes Classifier machine learning algorithm comes to the rescue. A classifier is a function that allocates a population's element value from one of the available categories. For instance, Spam Filtering is a popular application of the Naïve Bayes algorithm. Spam filter here is a classifier that assigns a label "Spam" or "Not Spam" to all the emails.
Naïve Bayes Classifier is amongst the most popular learning method grouped by similarities that works on the famous Bayes Theorem of Probability- to build machine learning models particularly for disease prediction and document classification. It is a simple classification of words based on the Bayes Probability Theorem for subjective analysis of content.
When to use the Machine Learning algorithm - Naïve Bayes Classifier?

- If you have a moderate or large training data set.
- If the instances have several attributes.
- Given the classification parameter, attributes that describe the instances should be conditionally independent.
  Applications of Naïve Bayes Classifier
- Sentiment Analysis- It is used at Facebook to analyze status updates expressing positive or negative emotions.
- Document Categorization- Google uses document classification to index documents and finds relevancy scores i.e., the PageRank. PageRank mechanism considers the pages marked as necessary in the databases that were parsed and classified using a document classification technique.
- Naïve Bayes Algorithm is also used for classifying news articles about Technology, Entertainment, Sports, Politics, etc.
- Email Spam Filtering-Google Mail uses the Naïve Bayes algorithm to classify your emails as Spam or Not Spam
  Advantages of the Naïve Bayes Classifier Machine Learning Algorithm
- Naïve Bayes Classifier algorithm performs well when the input variables are categorical.
- A Naïve Bayes classifier converges faster, requiring relatively little training data than other discriminative models like logistic Regression when the Naïve Bayes conditional independence assumption holds.
- With the Naïve Bayes Classifier algorithm, it is easier to predict the class of the test data set. A good bet for multi-class predictions as well.
- Though it requires the conditional independence assumption, Naïve Bayes Classifier has presented an excellent performance in various application domains.

### K Means Clustering Algorithm

K-means is a popularly used unsupervised machine learning algorithm for cluster analysis. K-Means is a non-deterministic and iterative method. The algorithm operates on a given data set through a pre-defined number of clusters, k. The output of the K Means algorithm is k clusters with input data partitioned among the clusters.

For instance, let's consider K-Means Clustering for Wikipedia Search results. The search term "Jaguar" on Wikipedia will return all pages containing the word Jaguar which can refer to Jaguar as a Car, Jaguar as Mac OS version and Jaguar as an Animal. K Means clustering algorithm can be applied to group the webpages that talk about similar concepts. So, the algorithm will group all web pages that talk about Jaguar as an Animal into one cluster, Jaguar as a Car into another cluster and so on.
Advantages of using K-Means Clustering Machine Learning Algorithm

- In the case of globular clusters, K-Means produces tighter clusters than hierarchical clustering.
- Given a smaller value of K, K-Means clustering computes faster than hierarchical clustering for a large number of variables.
  **Applications of K-Means Clustering**
  K Means Clustering algorithm is used by most of the search engines like Yahoo, Google to cluster web pages by similarity and identify the 'relevance rate' of search results. This helps search engines reduce the computational time for the users.

### Support Vector Machine Learning Algorithm

Support Vector Machine is a supervised machine learning algorithm for classification or regression problems where the dataset teaches SVM about the classes so that SVM can classify any new data. It works by classifying the data into different classes by finding a line (hyperplane) which separates the training data set into classes. As there are many such linear hyperplanes, SVM algorithm tries to maximize the distance between the various classes that are involved and this is referred as margin maximization. If the line that maximizes the distance between the classes is identified, the probability to generalize well to unseen data is increased.

SVM's are classified into two categories:
-Linear SVM's – In linear SVM's the training data i.e. classifiers are separated by a hyperplane.
-Non-Linear SVM's- In non-linear SVM's it is not possible to separate the training data using a hyperplane. For example, the training data for Face detection consists of group of images that are faces and another group of images that are not faces (in other words all other images in the world except faces). Under such conditions, the training data is too complex that it is impossible to find a representation for every feature vector. Separating the set of faces linearly from the set of non-face is a complex task.
Advantages of Using SVM

- SVM offers best classification performance (accuracy) on the training data.
- SVM renders more efficiency for correct classification of the future data.
- The best thing about SVM is that it does not make any strong assumptions on data.
- It does not over-fit the data.
  **Applications of Support Vector Machine**
  SVM is commonly used for stock market forecasting by various financial institutions. For instance, it can be used to compare the relative performance of the stocks when compared to performance of other stocks in the same sector. The relative comparison of stocks helps manage investment making decisions based on the classifications made by the SVM learning algorithm.

### Apriori Machine Learning Algorithm

Apriori algorithm is an unsupervised machine learning algorithm that generates association rules from a given data set. Association rule implies that if an item A occurs, then item B also occurs with a certain probability. Most of the association rules generated are in the IF_THEN format. For example, IF people buy an iPad THEN they also buy an iPad Case to protect it. For the algorithm to derive such conclusions, it first observes the number of people who bought an iPad case while purchasing an iPad. This way a ratio is derived like out of the 100 people who purchased an iPad, 85 people also purchased an iPad case.
Basic principle on which Apriori Machine Learning Algorithm works:

- If an item set occurs frequently then all the subsets of the item set, also occur frequently.
- If an item set occurs infrequently then all the supersets of the item set have infrequent occurrence.
  Advantages of Apriori Algorithm
- It is easy to implement and can be parallelized easily.
- Apriori implementation makes use of large item set properties.
  Applications of Apriori Algorithm
- Detecting Adverse Drug Reactions
  Apriori algorithm is used for association analysis on healthcare data like-the drugs taken by patients, characteristics of each patient, adverse ill-effects patients experience, initial diagnosis, etc. This analysis produces association rules that help identify the combination of patient characteristics and medications that lead to adverse side effects of the drugs.
- Market Basket Analysis
  Many e-commerce giants like Amazon use Apriori to draw data insights on which products are likely to be purchased together and which are most responsive to promotion. For example, a retailer might use Apriori to predict that people who buy sugar and flour are likely to buy eggs to bake a cake.
  **Auto-Complete Applications**
  Google auto-complete is another popular application of Apriori wherein - when the user types a word, the search engine looks for other associated words that people usually type after a specific word.

### Linear Regression Machine Learning Algorithm

Linear Regression algorithm shows the relationship between 2 variables and how the change in one variable impacts the other. The algorithm shows the impact on the dependent variable on changing the independent variable. The independent variables are referred as explanatory variables, as they explain the factors the impact the dependent variable. Dependent variable is often referred to as the factor of interest or predictor.
Advantages of Linear Regression Machine Learning Algorithm

- It is one of the most interpretable machine learning algorithms, making it easy to explain to others.
- It is easy of use as it requires minimal tuning.
- It is the mostly widely used machine learning technique that runs fast.
  Applications of Linear Regression
- Estimating Sales
  Linear Regression finds great use in business, for sales forecasting based on the trends. If a company observes steady increase in sales every month - a linear regression analysis of the monthly sales data helps the company forecast sales in upcoming months.
- Risk Assessment
  Linear Regression helps assess risk involved in insurance or financial domain. A health insurance company can do a linear regression analysis on the number of claims per customer against age. This analysis helps insurance companies find, that older customers tend to make more insurance claims. Such analysis results play a vital role in important business decisions and are made to account for risk.

### Decision Tree Machine Learning Algorithm

You are making a weekend plan to visit the best restaurant in town as your parents are visiting but you are hesitant in making a decision on which restaurant to choose from. Whenever you want to visit a restaurant you ask your friend Tyrion if he thinks you will like a particular place. To answer your question, Tyrion first has to find out, the kind of restaurants you like. You give him a list of restaurants that you have visited and told him whether you liked each restaurant or not (giving a labeled training dataset). When you ask Tyrion that whether you will like a particular restaurant R or not, he asks you various questions like "Is "R" a rooftop restaurant?", "Does restaurant "R" serve Italian cuisine?", "Does R have live music?", "Is restaurant R open till midnight?" and so on. Tyrion asks you several informative questions to maximize the information gain and gives you YES or NO answer based on your answers to the questionnaire. Here Tyrion is a decision tree for your favorite restaurant preferences.
A decision tree is a graphical representation that makes use of branching methodology to exemplify all possible outcomes of a decision, based on certain conditions. In a decision tree, the internal node represents a test on the attribute, each branch of the tree represents the outcome of the test and the leaf node represents a particular class label i.e. the decision made after computing all of the attributes. The classification rules are represented through the path from the root to the leaf node.
Types of Decision Trees
Classification Trees- These are considered as the default kind of decision trees used to separate a dataset into different classes, based on the response variable. These are generally used when the response variable is categorical in nature.

Regression Trees-When the response or target variable is continuous or numerical, regression trees are used. These are generally used in predictive type of problems when compared to classification.
Decision trees can also be classified into two types, based on the type of target variable- Continuous Variable Decision Trees and Binary Variable Decision Trees. It is the target variable that helps decide what kind of decision tree would be required for a particular problem.
Why should you use the Decision Tree Machine Learning algorithm?

- These machine learning algorithms help make decisions under uncertainty and help you improve communication, as they present a visual representation of a decision situation.
- Decision tree machine learning algorithms help a data scientist capture the idea that if a different decision was taken, then how the operational nature of a situation or model would have changed intensely.
- Decision tree algorithms help make optimal decisions by allowing a data scientist to traverse through forward and backward calculation paths.
  When to use Decision Tree Machine Learning Algorithm
- Decision trees are robust to errors and if the training data contains errors- decision tree algorithms will be best suited to address such problems.
- Decision trees are best suited for problems where instances are represented by attribute-value pairs.
- If the training data has missing value then decision trees can be used, as they can handle missing values nicely by looking at the data in other columns.
- Decision trees are best suited when the target function has discrete output values.
  Advantages of Using Decision Tree Machine Learning Algorithms
- Decision trees are very instinctual and can be explained to anyone with ease. People from a non-technical background can also decipher the hypothesis drawn from a decision tree, as they are self-explanatory.
- When using decision tree machine learning algorithms, the data type is not a constraint as they can handle both categorical and numerical variables.
- Decision tree machine learning algorithms do not require making any assumption on the linearity in the data and hence can be used in circumstances where the parameters are non-linearly related. These machine learning algorithms do not make any assumptions on the classifier structure and spatial distribution.
- These algorithms are useful in data exploration. Decision trees implicitly perform feature selection which is very important in predictive analytics. When a decision tree is fit to a training dataset, the nodes at the top on which the decision tree is split, are considered as important variables within a given dataset and feature selection is completed by default.
- Decision trees help save data preparation time, as they are not sensitive to missing values and outliers. Missing values will not stop you from splitting the data for building a decision tree. Outliers will also not affect the decision trees as data splitting happens based on some samples within the split range and not on exact absolute values.
  Drawbacks of Using Decision Tree Machine Learning Algorithms
- The more the number of decisions in a tree, the less is the accuracy of any expected outcome.
- A major drawback of decision tree machine learning algorithms is that the outcomes may be based on expectations. When decisions are made in real-time, the payoffs and resulting outcomes might not be the same as expected or planned. There are chances that this could lead to unrealistic decision trees leading to bad decision making. Any irrational expectations could lead to major errors and flaws in decision tree analysis, as it is not always possible to plan for all eventualities that can arise from a decision.
- Decision Trees do not fit well for continuous variables and result in instability and classification plateaus.
- Decision trees are easy to use when compared to other decision-making models but creating large decision trees that contain several branches is a complex and time-consuming task.
- Decision tree machine learning algorithms consider only one attribute at a time and might not be best suited for actual data in the decision space.
- Large-sized decision trees with multiple branches are not comprehensible and pose several presentation difficulties.
  Applications of Decision Tree Machine Learning Algorithm
- Decision trees are among the popular machine learning algorithms that find great use in finance for option pricing.
- Remote sensing is an application area for pattern recognition based on decision trees.
- Decision tree algorithms are used by banks to classify loan applicants by their probability of defaulting payments.
- Gerber Products, a popular baby product company, used decision tree machine learning algorithms to decide whether they should continue using the plastic PVC (Poly Vinyl Chloride) in their products.
- Rush University Medical Centre has developed a tool named Guardian that uses a decision tree machine learning algorithm to identify at-risk patients and disease trends.
  Random Forest Machine Learning Algorithm
  Let's continue with the same example that we used in decision trees, to explain how the Random Forest Machine Learning Algorithm works. Tyrion is a decision tree for your restaurant preferences. However, Tyrion being a human being, does not always generalize your restaurant preferences with accuracy. To get a more accurate restaurant recommendation, you ask a couple of your friends and decide to visit the restaurant R, if most of them say that you will like it. Instead of just asking Tyrion, you would like to ask Jon Snow, Sandor, Bronn, and Bran, who vote on whether you will love the restaurant R or not. This implies that you have built an ensemble classifier of decision trees - also known as a forest.
  You don't want all your friends to give you the same answer - so you provide each of your friends with slightly varying data. You are also not sure of your restaurant preferences and are in a dilemma. You told Tyrion that you like Open Roof Top restaurants but maybe, just because it was summer when you visited the restaurant, you could have liked it then. You may not be a fan of the restaurant during the chilly winters. Thus, all your friends should not make use of the data point that you like open rooftop restaurants, to make their recommendations for your restaurant preferences.
  By providing your friends with slightly different data on your restaurant preferences, you make your friends ask you various questions at different times. In this case, just by slightly altering your restaurant preferences, you are injecting randomness at the model level (unlike randomness at data level in case of decision trees). Your group of friends now forms a random forest of your restaurant preferences.
  Random Forest is the go-to machine learning algorithm that uses a bagging approach to create a bunch of decision trees with a random subset of the data. A model is trained several times on a random sample of the dataset to achieve excellent prediction performance from the random forest algorithm. In this ensemble learning method, the output of all the decision trees in the random forest is combined to make the final prediction. The final prediction of the random forest algorithm is derived by polling the results of each decision tree or just by going with a prediction that appears the most times in the decision trees.
  For instance, in the above example - if five friends decide that you will like restaurant R, but only two friends decide that you will not like the restaurant, then the final prediction is that you will like restaurant R as the majority always wins.
  Why use Random Forest Machine Learning Algorithm?
- There are many good open-source, free implementations of the algorithm available in Python and R.
- It maintains accuracy when there is missing data and is also resistant to outliers.
- Simple to use as the basic random forest algorithm can be implemented with just a few lines of code.
- Random Forest machine learning algorithms help data scientists save data preparation time, as they do not require any input preparation and are capable of handling numerical, binary and categorical features, without scaling, transformation or modification.
- Implicit feature selection as it gives estimates on what variables are important in the classification.
  Advantages of Using Random Forest Machine Learning Algorithms
- Overfitting is less of an issue with Random Forests, unlike decision tree machine learning algorithms. There is no need of pruning the random forest.
- These algorithms are fast but not in all cases. A random forest algorithm, when running on an 800 MHz machine with a dataset of 100 variables and 50,000 cases produced 100 decision trees in 11 minutes.
- Random Forest is one of the most effective and versatile machine learning algorithms for a wide variety of classification and regression tasks, as they are more robust to noise.
- It is difficult to build a bad random forest. In the implementation of Random Forest Machine Learning algorithms, it is easy to determine which parameters to use because they are not sensitive to the parameters that are used to run the algorithm. One can easily build a decent model without much tuning.
- Random Forest machine learning algorithms can be grown in parallel.
- This algorithm runs efficiently on large databases.
- Has higher classification accuracy.
  Drawbacks of Using Random Forest Machine Learning Algorithms
- They might be easy to use, but analyzing them theoretically is difficult.
- A large number of decision trees in the random forest can slow down the algorithm in making real-time predictions.
- If the data consists of categorical variables with a different number of levels, then the algorithm gets biased in favor of those attributes that have more levels. In such situations, variable importance scores do not seem to be reliable.
- When using the RandomForest algorithm for regression tasks, it does not predict beyond the range of the response values in the training data.
  Applications of Random Forest Machine Learning Algorithms
- Random Forest algorithms are used by banks to predict if a loan applicant is a likely high risk.
- They are used in the automobile industry to predict the failure or breakdown of a mechanical part.
- These algorithms are used in the healthcare industry to predict if a patient is likely to develop a chronic disease or not.
- They can also be used for regression tasks, like predicting the average number of social media shares and performance scores.
- Recently, the algorithm has also made way into predicting patterns in speech recognition software and classifying images and texts.
  Logistic Regression
  The name of this algorithm could be a little confusing in the sense that the Logistic Regression machine learning algorithm is for classification tasks and not regression problems. The name 'Regression' here implies that a linear model is fit into the feature space. This algorithm applies a logistic function to a linear combination of features to predict the outcome of a categorical dependent variable based on predictor variables.
  The odds or probabilities that describe the outcome of a single trial are modeled as a function of explanatory variables. Logistic regression algorithms help estimate the probability of falling into a specific level of the categorical dependent variable based on the given predictor variables.
  Just suppose that you want to predict if there will be a snowfall tomorrow in New York. Here the outcome of the prediction is not a continuous number because there will either be snowfall or no snowfall and hence linear Regression cannot be applied. Here the outcome variable is one of the several categories and using logistic Regression helps.

Based on the nature of the categorical response, Logistic Regression is classified into 3 types –
· Binary Logistic Regression – The most commonly used logistic Regression when the categorical response has 2 possible outcomes i.e. either yes or not. Example –Predicting whether a student will pass or fail an exam, predicting whether a student will have low or high blood pressure, predicting whether a tumor is cancerous or not.
· Multi-nominal Logistic Regression - Categorical response has three or more possible outcomes with no ordering. Example- Predicting what kind of search engine (Yahoo, Bing, Google, and MSN) is used by majority of US citizens.
· Ordinal Logistic Regression - Categorical response has 3 or more possible outcomes with natural ordering. Example- How a customer rates the service and quality of food at a restaurant based on a scale of 1 to 10.
Let us consider a simple example where a cake manufacturer wants to find out if baking a cake at 160°C, 180°C and 200°C will produce a 'hard' or 'soft' variety of cake ( assuming the fact that the bakery sells both the varieties of cake with different names and prices). Logistic Regression is a perfect fit in this scenario instead of other statistical techniques. For example, if the manufactures produces 2 cake batches wherein the first batch contains 20 cakes (of which 7 were hard and 13 were soft ) and the second batch of cake produced consisted of 80 cakes (of which 41 were hard and 39 were soft cakes). Here in this case if linear regression algorithm is used it will give equal importance both the batches of cakes regardless of the number of cakes in each batch. Applying a logistic regression algorithm will consider this factor and give the second batch of cakes more weightage than the first batch.
When to Use the Logistic Regression Machine Learning Algorithm

- Use logistic regression algorithms when there is a requirement to model the probabilities of the response variable as a function of some other explanatory variable. For example, the probability of buying a product X as a function of gender
- Use logistic regression algorithms when there is a need to predict probabilities that the categorical dependent variable will fall into two categories of the binary response as a function of some explanatory variables. For example, what is the probability that a customer will buy a perfume given that the customer is a female?
- Logistic regression algorithms is also best suited when the need is to classify elements two categories based on the explanatory variable. For example-classify females into 'young' or 'old' group based on their age.
  Advantages of Using Logistic Regression
- Easier to inspect and less complex.
- Robust algorithm as the independent variables need not have equal variance or normal distribution.
- These algorithms do not assume a linear relationship between the dependent and independent variables and hence can also handle non-linear effects.
- Controls confounding and tests interaction.
  Drawbacks of Using Logistic Regression
- When the training data is sparse and high dimensional, in such situations, a logistic model may overfit the training data.
- Logistic regression algorithms cannot predict continuous outcomes. For instance, logistic Regression cannot be applied when the goal is to determine how heavily it will rain because the scale of measuring rainfall is continuous. Data scientists can predict heavy or low rainfall but this would make some compromises with the precision of the dataset.
- Logistic regression algorithms require more data to achieve stability and meaningful results. These algorithms require a minimum of 50 data points per predictor to achieve stable outcomes.
- It predicts outcomes depending on a group of independent variables and if a data scientist or a machine learning expert goes wrong in identifying the independent variables then the developed model will have minimal or no predictive value.
- It is not robust to outliers and missing values.
  Applications of Logistic Regression
- Logistic regression algorithm is applied in the field of epidemiology to identify risk factors for diseases and plan accordingly for preventive measures.
- Used to predict whether a candidate will win or lose a political election or to predict whether a voter will vote for a particular candidate.
- Used to classify a set of words as nouns, pronouns, verbs, adjectives.
- Used in weather forecasting to predict the probability of rain.
- Used in credit scoring systems for risk management to predict the defaulting of an account.

### Basic Syntax Help

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1

## H2

### H3

### Bold

**bold text**

### Italic

_italicized text_

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[title](https://www.example.com)

### Image

![alt text](image.jpg)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
