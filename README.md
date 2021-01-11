# **Amazon Vine Analysis**

### **Overview**

The purpose of the analysis is to observe if there is a percentage positivity bias in 5-star reviews between vine and non-vine Amazon subsribers.

### **Source**

Data source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Automotive_v1_00.tsv.gz

### **Results**

Based on the dataset, there were total of 82 Vine subsribers vs. 24,742 None-Vine subscribers.

*Figure 1.1: Total Vine and Non-Vine Count*
   
![Total_Vine_Reviews](https://user-images.githubusercontent.com/70525492/104233645-d76a9700-5417-11eb-988d-2dd34f7372d8.png)
![Total_non_Vine_Reviews](https://user-images.githubusercontent.com/70525492/104233699-eb15fd80-5417-11eb-9237-f14474be8290.png)


The distribution of 5-star reviews between vine and non-vine reviews were 33 and 12,807 respectively.

*Figure 1.2: Star review by vine and non-vine customers*
![star_rating](https://user-images.githubusercontent.com/70525492/104233775-14cf2480-5418-11eb-9643-e6e83ca12f4d.png)
![star_rating_nonvine](https://user-images.githubusercontent.com/70525492/104233779-16005180-5418-11eb-8bb5-1e0658f34cc8.png)

Ther percentage of 5-star reviews between vine and non-vine customers were 40.24% and 51.76% respectively.

*Figure 1.3: % 5-star review between vine and non-vine customers*

![vine_review_percentage](https://user-images.githubusercontent.com/70525492/104233798-1ac50580-5418-11eb-8142-d50c1f1d8686.png)
![non_vine_review_percentage](https://user-images.githubusercontent.com/70525492/104233846-2dd7d580-5418-11eb-933e-632eb0106214.png)

### **Summary**

Based on the observed percentage of 5-star reviews, there appeared to be bias in the review. Vine customers overall has a less 5-star review compare to non-vine customers. 

However, a hypothesis testing with the dataset will be recommended with null hypothesis being there is no difference in 5-star review between vine and non-vine customers. 


