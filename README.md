# Social-Media-Content-Performance-Analysis
This project is aimed at analyzing the performance of content on a social media platform. By examining this data, we can gain insights into content performance, user engagement, and sentiment analysis.

 ## Data Tables ###
 1 Content Table Contains information about each piece of content uploaded on the platform, including content id, Userid, content type, url and content category.
 
 2 Reaction Table Details user reactions to the content, including cotent id, user Id, reaction types and timestamps.
 
 3 ReactionType Table Defines the types of reactions available on the platform including content type, sentiment and content type score. 

 ## BUSINESS QUESTION ###
 What are the total number of content categories?
 What are the total number of content uploaded? 
 What are total number of users?
 What are the top 5 categories?
 What is the month with the most uploads?
 What sentiment has highest category score? 
 



## Data Insights ###
1. Total Number of Content Categories: 16
2. Total Number of Content Uploaded: 842
3. Total Number of Users: 414
4. Top 5 Content Categories: - Animals - Culture - Healthy Eating - Science - Technology
5. Month with the Most Uploads: January 6.
6. Sentiment Analysis: - Positive sentiment had the highest category score, indicating that content viewed as having a positive sentiment had a greater category score
7. Most Used Content Types: Photos and Videos
  
**Data Preparation Process** 

**Data Cleaning and Transformation**
 		  	a) Utilized Power Query to clean and preprocess the data. 
      			b) Removed redundant columnns.
			c) Merged tables to create a comprehensive dataset.
			d) Created unique identifiers for each record. 
 
 **Measure Creation**  : Used Data Analysis Expressions (DAX) to create necessary measures for analysis such as sum of category score and count of content uploaded

![image](https://github.com/user-attachments/assets/c6711d7f-253b-4d90-8bcc-b54b36c852f2)
![image](https://github.com/user-attachments/assets/ad29b5e6-e7c2-4417-a039-17d3755fcc8a)



 
  **Data Visualization** : Visualized the data using various slicers, including Year and Hours, to enable dynamic analysis and insights. 
	
Creation of  various visualizations, focusing on metrics such as:
Number of uploads per month.
Category-wise content distribution.
Sentiment analysis scores.
User engagement metrics for different content types.
       
## Slicers 
	Year: To filter and analyze data by specific years. -
	Hours: To examine content performance based on the time of day.

In conclusion,  we can better understand what types of content are performing well, the engagement patterns of users, and the overall sentiment towards the content. This analysis helps in strategizing future content creation and improving user engagement on the platform.

SEE DASHBOARD BELOW
![image](https://github.com/user-attachments/assets/0700efa7-50b7-4f47-847e-1a973866c107)



