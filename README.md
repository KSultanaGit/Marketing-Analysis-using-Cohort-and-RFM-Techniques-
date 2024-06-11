# Marketing Analysis using Cohort and RFM Techniques 
 Marketing Analysis using Cohort and RFM Techniques 
# Customer segmentation

### The customer segmentation based on RFM method and K-Means clustering

## General info
The project contains two methods of customer segmentation by combining the RFM method and K-Means clustering. The dataset includes sample sales data based on retail analytics. 
### Dataset
The dataset includes sample sales data based on retail analytics and contains three years of sales.

## Motivation
The customer segmentation is an effective method that enables to get better know clients and to better correspond their various needs. 
Almost every company that sells products or services stores data of shopping. This type of data can be used to execute customer segmentation thus the results of the analysis can be translated into marketing campaigns to increase sales. One of the most widely used techniques is RFM analysis, which allows to create personalized special offers to improve sales. 

**RFM** stands for Recency, Frequency, Monetary Value and it is the technique of customer segmentation based on their transaction history. The RFM analysis is based on three criterias which measure different customer characteristics:
- Recency: Days since last purchase/order of the client;
- Frequency: Total number of purchases the customer were made;
- Monetary Value: Total money the customer spent per order.

## Technologies

The project is created with:

- Python 3.6
- libraries: pandas, numpy, sklearn, scipy, seaborn, matplotlib.

Analysis of RFM Clusters:

Based on the K-means clustering algorithm applied to the RFM (Recency, Frequency, Monetary) data, here is a detailed description and characteristics of each cluster, along with category recommendations:

<img src="https://github.com/KSultanaGit/Marketing-Analysis-using-Cohort-and-RFM-Techniques-/blob/main/images/scatterplot.png" alt="Screenshot 1" width="959" height="2393" align="center">


<img src="https://github.com/KSultanaGit/Marketing-Analysis-using-Cohort-and-RFM-Techniques-/blob/main/images/boxplot.png" alt="Screenshot 1" width="2693" height="300" align="center">


Cluster 0

Recency: Moderate
Frequency: High
Monetary: Moderate
Characteristics: This cluster includes customers who purchase relatively frequently and have moderate spending. They are moderately recent in their purchase behavior.
Category: Loyal Customers – These customers are valuable due to their frequent purchases. They should be nurtured with loyalty programs and personalized offers.

Cluster 1

Recency: High
Frequency: Low
Monetary: Low
Characteristics: Customers in this cluster haven't made recent purchases and show low purchase frequency and spending.
Category: At-Risk Customers – These customers are at risk of churning. Efforts should be made to re-engage them through targeted marketing campaigns and special discounts.

Cluster 2

Recency: Moderate
Frequency: Moderate
Monetary: Moderate
Characteristics: Customers in this cluster have average values across recency, frequency, and monetary metrics.
Category: Average Customers – These customers are neither exceptionally loyal nor at risk. Regular engagement and good customer service will help maintain their current purchasing behavior.

Cluster 3

Recency: Moderate
Frequency: Low
Monetary: Moderate
Characteristics: This cluster includes customers with moderate spending but lower purchase frequency. Their recency is also moderate.
Category: Potential Loyalists – With the right incentives, these customers could increase their purchase frequency and become more loyal. Focus on personalized marketing to increase engagement.

Cluster 4

Recency: Low
Frequency: Moderate
Monetary: Low
Characteristics: Customers in this cluster are fairly recent in their purchase behavior but have low monetary value and moderate frequency.
Category: New Customers – These customers have recently started engaging but have not spent much yet. Encouraging repeat purchases through welcome offers and onboarding can help increase their lifetime value.

Cluster 5

Recency: Low
Frequency: High
Monetary: High
Characteristics: This cluster consists of customers who have made recent, frequent purchases and have high spending.
Category: Best Customers – These are the most valuable customers. They should be given VIP treatment, exclusive offers, and top-notch customer service to maintain their loyalty.

Summary

Cluster 0: Loyal Customers
Cluster 1: At-Risk Customers
Cluster 2: Average Customers
Cluster 3: Potential Loyalists
Cluster 4: New Customers
Cluster 5: Best Customers

Understanding these clusters helps in creating targeted strategies for different customer segments, enhancing overall customer satisfaction and business performance. ​ ​

Conclusion:

Targeted Marketing Strategies for Each Customer Segment

    Best Customers (Cluster 5)

Characteristics: Recent, frequent purchases with high spending.

Strategies:

VIP Programs: Offer exclusive benefits such as early access to new products, special discounts, and personalized services.
Personalized Communication: Send personalized emails or messages highlighting products that match their purchase history.
Loyalty Rewards: Implement a robust loyalty program where they can earn points for every purchase and redeem them for rewards.
Exclusive Events: Invite them to special events, webinars, or product launches to make them feel valued.

    Loyal Customers (Cluster 0)

Characteristics: Frequent purchases, moderate spending, moderate recency.

Strategies:

Surprise and Delight: Occasionally send them surprise discounts or free samples to show appreciation.
Referral Programs: Encourage them to refer friends and family with rewards for successful referrals.
Feedback Requests: Engage them by asking for feedback and suggestions, making them feel involved in the brand’s growth.
Regular Updates: Keep them informed about upcoming sales, new arrivals, and exclusive offers through newsletters.

    At-Risk Customers (Cluster 1)

Characteristics: Low frequency, low monetary, high recency.

Strategies:

Re-engagement Campaigns: Send targeted campaigns with special discounts or incentives to encourage them to return.
Win-back Offers: Offer significant discounts or promotions that are time-sensitive to prompt immediate action.
Survey and Feedback: Send surveys to understand why they stopped purchasing and address any issues they mention.
Personalized Recommendations: Highlight new or relevant products that match their past purchases to rekindle their interest.

    Average Customers (Cluster 2)

Characteristics: Average values across recency, frequency, and monetary.

Strategies:

Consistent Engagement: Keep them engaged with regular updates, promotions, and newsletters.
Cross-Selling and Up-Selling: Recommend products that complement their previous purchases to increase average order value.
Seasonal Promotions: Target them with special offers during key shopping seasons (e.g., Black Friday, Christmas).
Customer Service: Ensure excellent customer service to maintain satisfaction and encourage repeat purchases.

    Potential Loyalists (Cluster 3)

Characteristics: Moderate spending, low frequency, moderate recency.

Strategies:

Incentivize Frequency: Offer discounts or rewards for more frequent purchases, like “buy more, save more” deals.
Personalized Offers: Provide personalized offers based on their browsing history and past purchases.
Content Marketing: Send them valuable content, such as tips, guides, or blog posts related to their interests.
Follow-Up: After each purchase, follow up with product recommendations and a thank you note to build a stronger relationship.

    New Customers (Cluster 4)

Characteristics: Recent purchases, moderate frequency, low spending.

Strategies:

Welcome Campaigns: Send a welcome email series with a special offer for their next purchase.
Onboarding: Provide information on how to make the most of their purchases and introduce them to your brand’s values and offerings.
First-Time Buyer Discounts: Offer a discount on their next purchase to encourage repeat business.
Engagement: Engage them with personalized recommendations and highlight popular products to drive additional purchases.

Implementation Tips

Segmented Email Marketing: Use email marketing platforms that allow segmentation to tailor messages for each customer group.
Customer Relationship Management (CRM): Utilize a CRM system to track customer interactions and tailor your approach based on their behavior.
Data Analysis: Continuously analyze customer data to refine your strategies and ensure they remain effective.
Feedback Loop: Regularly collect feedback to understand customer needs and adjust your marketing strategies accordingly.

By implementing these targeted strategies, you can enhance customer engagement, increase loyalty, and drive higher revenue from each customer segment.
1

​Contributor: Khadija Sultana
