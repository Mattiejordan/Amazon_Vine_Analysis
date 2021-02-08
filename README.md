# Amazon_Vine_Analysis

Deliverable 3 Requirements
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt)
Each section has a heading and subheading (2 pt)
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (14 points)
The written analysis has the following:

Overview of the analysis of the Vine program:

The purpose of this analysis is well defined (3 pt)
Results:

There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)
Summary:

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)

## Vine Program Overview for SellBy

![AnalysisImages/stars](AnalysisImages/stars.png)

#### SellBy pays a fee to Amazon and provides products to Amazon Vine members for the encouragement 
of Vine members writing reviews. Is SellBy providing incentive for many well written reviews or 
does SellBy provide a bias of skewed review data? ####

Jennifer and I have crunched the numbers from the SellBy project and now I am feasting upon the data
accumulated by the Amazon Vine program. I used PySpark, AWS, Google Colab Notebooks, Visual Studio Code, pgAdmin, and python 
for this project. 

My dataset is from the Amazon groceries reviews. Inside this set are reviews from the paid Vine program pool
as well as all the unpaid regular reviews. Ratings range from 1 star dissatisfied to 5 stars very
satisfied. I am curious to see how many of our paid Vine reviews are in the 5 star category versus
the other rating categories. 

![AnalysisImages/total_reviews](AnalysisImages/total_reviews.PNG)
## The Total Number of Reviews by total votes

![AnalysisImages/totalfivestarreviews](AnalysisImages/totalfivestarreviews.PNG)
## The Total Number of Five Star Rating Reviews by total votes

