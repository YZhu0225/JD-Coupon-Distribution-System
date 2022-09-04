# JD-Coupon-Distribution-System
## Background
With the rapid development of e-commerce platforms, the competition among major e-commerce platforms is particularly fierce. Coupon distribution is an important means to attract new customers and revitalize old customers, but sending coupons randomly may be counterproductive, and personalized placement is an important technique to improve coupon usage.

This project uses the coupon usage data of Jingdong platform users to explore the usage of coupons by each user group to ensure the usage rate of coupons. Three main dimensions are used to build the model: first, product characteristics: the sales price of products, discounts, etc.; second, consumer characteristics: the number of single purchases by users, the total price of products purchased by users, etc.; third: coupon characteristics: the duration of coupon discounts, the number of products to which coupons apply. Based on these dimensional data, to predict whether users will use coupons, so as to achieve a coupon intelligent distribution system and improve the effectiveness of coupon usage.

## Introduction of Dataset
The dataset is 78369 * 46 in size, where "redemption_status" is whether the coupon is used or not, which is also the target variable of this project, and other characteristics are features, such as: total discount amount", "activity type ", "start date", "end date", 'campaign duration', 'age range ', 'marital status', 'family size', 'no children', 'income bracket '.

## Steps：
1. Clarify the problem category of the project (regression or classification) and determine the indicators of the project.
2. Eda data exploration. Through visualization, calculation of statistical values, etc. to find the anomalies in the data, and to further familiarize with the data at hand.
3. Establish a baseline, followed by in-depth adjustments on it.
4. Determine a good cross-validation strategy ( kfold / stratifiedkfold).
5. Identify the problem according to the performance of the model and then implement corresponding feature engineering methods to derive new features, convert the original features or feature selection.
6. Apply stacking and other integrated methods to further improve the model.
