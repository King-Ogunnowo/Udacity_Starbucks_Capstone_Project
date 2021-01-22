## Project Overview

This project aims to identify consumers who will respond positively or favourably to a sales promotion offer made by starbucks. Starbucks dispenses messages to customers containing a type of offer. Offers made by Starbucks in these messages include the following: buy-one-get-one (BOGO), discount offers and informational offers. Each customer receives one of these offers.

BOGO offers require that a customer spends a particular amount or purchases the required amount of items to qualify. Discount offers give customers the chance to purchase certain items at lesser value. The last category which is informational, is not necessarily an offer but merely gives information about certain products. Customers and consumers alike receive these offers through a variety of channels. These channels include: web, email, mobile and social media.

Generally, companies make offers or deploy ads to their customers for a number of reasons, this action is referred to as sales promotion. Some of the reasons for sales promotion include: increase sales, gain market share from competition, gain new distribution opportunities and so on. Sale promos demand a significant amount of resources and are only successful when the objectives are achieved

## Problem Statement

Starbucks like any other organisation sends out promos to reward loyal customers, maximize profit and also gain new customers. The typical flow of an appropriate offer begins with "Offer Recieved". The next stage is "Offer Viewed". at this stage it is expected that the customer has viewed the offer. The third stage is "Transaction", whereby the customer makes a transaction in accordance with the offer viewed. The last stage is "Offer Completed" in which the customer has completed the demands of the offer and made the appropriate transactions.

Considering the preceding, it is discovered that some consumers do not complete the offer. In certain cases, offers are only received and not viewed while others are viewed and no transaction is conducted. There are also cases where transactions not impacted by offers are conducted. The preceding scenarios which depict incomplete offers, points to the inability to match customers with offers they are prone to completing. As such, this project sets determine if a particular customer will respond to an offer or not.

For the purpose of solving the above stated problem, a classifier will be trained to determine if a customer will respond to a particular offer or not. The project will also identify the features that customers consider before responding to an offer. There (3) distinct classifiers (Logistic Regression, Random Forest Classifier, Gradient Boosting) will be trained with the data and their results compared with each other. The classifier or model with the highest accuracy will be chosen.

## Metrics

For this project, a confusion matrix will be generated detailing the True Positives (TP), False Positives (FP), False Negatives (FN), True Negatives (TN). The purpose of this is to depict the number of correct and wrong predictions made by the model. After this, the model’s accuracy score will be generated. Accuracy measures the ratio of correct predictions over the total number of instances evaluated. Formula for accuracy: (TP+TN)/(TP+TN+FP+FN)

## Benchmarking

For this project, three (3) models were trained with their accuracy scores compared with each other. The model with the highest accuracy score was chosen for the project. The models and their scores include:

<ul>
    <li> LogisticRegression: 0.863 </li>
    <li> RandomForestClassifier: 0.999 </li>
    <li> GradientBoostingClassifier: 0.911 </li>
</ul>    

All models mentioned above are classifier models, designed to solve classification problems. Considering the dataset, any one of them could have worked well. However, <b>LogisticRegression</b> is limited in that it constructs a linear decision boundry. However the data suggests that the decision made will follow a non-linear decision pattern. As a result, an ensemble model like a <b>RandomForestClassifier</b> will perform better. 

## Packages Used

The following packages were imported and used accordingly
<ul>
    <li><b>%matplotlib inline:</b> Inline because no interactive plots or charts will be created</li>
    <li><b>pandas:</b> To read in the dataset(s)</li>
    <li><b>numpy:</b> To work with arrays</li> 
    <li><b>matplotlib.pyplot:</b> To visualize and plot data</li>
    <li><b>seaborn:</b> To visualize and plot data</li>
    <li><b>sklearn (scikit-learn):</b> Machine Learning </li>
</ul>

## Files

<ul>
    <li><b>Datasets:</b>portfolio.csv, profile.csv, transcript.csv and combined_df.csv (Combination of all datasets)</li>
    <li><b>Starbucks_Project Notebook:</b> used in conducting exploratory analysis, cleaning, visualizations and modelling</li>
    <li><b>Report:</b> Report on the findings of the project </li>
</ul>
