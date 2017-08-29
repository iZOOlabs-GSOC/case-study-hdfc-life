# Industry Case Study with Datasets

## Introduction

#### About HDFC Life - 

HDFC Life (HDFC Standard Life Insurance Company) is a long-term life insurance provider with its headquarters in Mumbai, offering individual and group insurance.

It is a joint venture between Housing Development Finance Corporation Ltd (HDFC), one of India's leading housing finance institution and Standard Life plc, leading well known provider of financial savings & investments services in the United Kingdom. 

HDFC Life's products include Protection, Pension, Savings, Investment, Health along with Children and Women plans. The company also provides an option of customizing the plans, by adding optional benefits called riders, at an additional price. The company currently has 29 retail and 8 group products, along with 7 optional rider benefits (as on 31 May 2016).

* Mohit Karnwal Protection Plans - insurance plans that provide protection and financial stability to the family in case of any unforeseen events.
* Click2Protect Plus is their online term plan.
* Launched CSC Suraksha to be sold exclusive through the Common Services Centre network.
* Click2Invest is their online ULIP investment plan.
* Health Plan – offers financial security to meet health related contingencies.
* Savings & Investment plans - These plans help in investment to achieve financial goals.
* Retirement plans - financial security for life post retirement.
* Women’s plans - plans catering to different financial needs of women.
* Children’s plans – plans meant to secure children’s future.
* Rural & social Plans – meant specifically for rural customers.
* Click2Retire completed their Click2 portfolio.

#### About GreyAtom - 

GreyAtom is an onsite school focused on providing industry relevant programs on emerging technologies. Our Program is developed by world-class academicians in collaboration with industry practitioners. Our Instructors and curriculum developers rank from the best institutes globally and in India. GreyAtom also provides LIVE streaming of all our programs.

## Problem Statement

Reddit is a social news aggregation and discussion website. Reddit's registered community members can submit content such as text posts or direct links.

Content entries are organized by areas of interest called "Subreddits". Subreddit topics include news, science, gaming, movies, music, books, fitness, food, image-sharing and many others.

Provided [here](https://s3.ap-south-1.amazonaws.com/greyatom-files/25000-users.zip) is a dataset of 25,000 reddit users, their interactions with subreddits and the timestamp at which they interacted.

## Output

The goal of this assignment is to recommend users the subreddit they should subscribe to. You should submit the output in .CSV format and it should have all the usernames as rows and the columns with subreddits. You should document your approaches and how you have arrived to the final solution.

## Example

The user with username "kabanossi", some of the subreddits recommended for him are: "AnimalGIFs", "AnimalBehavior", "tinyanimalsonfingers", "whatisthisanimal", etc.

## Note

Don't use RNN (Recurrent Neural Network) language model.

## Evaluation

You will be evaluated based on the accuracy of the output, documentation, code quality, code documentation and explanation about how you have reached to the solution.

## Evaluation Criteria
#### Data Exploration

Student response addresses the most important characteristics of the dataset and uses these characteristics to inform their analysis. Important characteristics include:
* Total number of data points
* Allocation across classes (POI/non-POI)
* Number of features used
* Are there features with many missing values? etc.

#### Outlier Investigation
* Student response identifies outlier(s) in the data, and explains how they are removed or otherwise handled.

#### Create new features
* At least one new feature is implemented. Justification for that feature is provided in the written response. The effect of that feature on final algorithm performance is tested or its strength is compared to other features in feature selection. The student is not required to include their new feature in their final feature set.

#### Feature Selection
* Univariate or recursive feature selection is deployed, or features are selected by hand (different combinations of features are attempted, and the performance is documented for each one). Features that are selected are reported and the number of features selected is justified. For an algorithm that supports getting the feature importances (e.g. decision tree) or feature scores (e.g. SelectKBest), those are documented as well.

#### Feature Scaling
* If algorithm calls for scaled features, feature scaling is deployed.

#### Pick an algorithm
* At least two different algorithms are attempted and their performance is compared, with the best performing one used in the final analysis.

#### Discuss parameter tuning and its importance.
* Response addresses what it means to perform parameter tuning and why it is important.

#### Tune the algorithm 
At least one important parameter tuned with at least 3 settings investigated systematically, or any of the following are true:
* GridSearchCV used for parameter tuning
* Several parameters tuned
* Parameter tuning incorporated into algorithm selection (i.e. parameters tuned for more than one algorithm, and best algorithm-tune combination selected for final analysis).

#### Usage of Evaluation Metrics
* At least two appropriate metrics are used to evaluate algorithm performance (e.g. precision and recall), and the student articulates what those metrics measure in context of the project task.

#### Discuss validation and its importance.
* Response addresses what validation is and why it is important

#### Validation Strategy
* Performance of the final algorithm selected is assessed by splitting the data into training and testing sets or through the use of cross validation, noting the specific type of validation performed.

## Mentoring Sessions
### Calendar of Visitation of Academic Partner
##### Day -01
##### Day -02
##### Day -04
##### Day -05
### Calendar of Visitation of Industry Partner
##### Day -03

## Mentoring Sequence
* Harishkandan
* Nikhil Borkar
* Pankaj Meher
* Nikita Goel
* Mudassir Khan
* Biraj Parikh
* Nikhil Singh
* Ronak Talreja
* Varun Panicker
* Bhavesh Bhatt
* Gowtham Dongiri
* Pramod Bhalerao
* Saahil Sharma
* Arunabh Singh
* Ramkrishna Sahu
* Sagar Ambalam
* Bijit Deka

### Each Session is for 10 minutes. Make sure your quesitons are ready.
### Mentoring Sessions start at 10 AM - 12 PM every morning.


