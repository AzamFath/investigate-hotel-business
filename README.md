# Investigate Hotel Business using Data Visualization
Hotel Data Analysis using Python

## Background

In the increasingly digital era, data analysis and visualization have become key to business success in the hospitality industry. By employing data visualization techniques, hotel management can explore booking trends, cancellation patterns, and other factors influencing business performance. This enables them to design more effective marketing strategies, enhance overall customer experience, and facilitate communication of complex insights to stakeholders. Thus, investigating hotel business through data visualization has the potential to improve operational performance and competitiveness in the increasingly competitive market.

## Objective

This project aims to use data visualization as a tool to investigate hotel business performance, focusing on monthly booking trend analysis based on hotel types, the impact of length of stay on booking cancellation rates, and the relationship between lead time and booking cancellation rates. Through this approach, the project aims to provide a deeper understanding of business dynamics in the hospitality industry and generate valuable insights for hotel management to enhance marketing strategies and overall customer experience.

## Research Questions

1. How do monthly hotel booking trends vary based on hotel types, such as urban hotels and resort hotels?

2. What is the impact of length of stay on hotel booking cancellation rates? Are there consistent patterns in cancellation decisions based on length of stay?

3. What is the relationship between lead time, the period between booking and check-in date, and hotel booking cancellation rates? Does longer lead time tend to increase or decrease cancellation rates?

## Data and Assumptions

The dataset used can be downloaded from the [dataset source]( https://drive.google.com/file/d/1Cq4cHMSpnGml7a2PwDz8Dbp2W3pMbLbY/view). The assumption in this research is that the processed data belongs to one of the hotels in the world, although I cannot confirm whether the data is valid or not because here I ONLY process the dataset.

## Data Analysis

In this project, several Python libraries such as Pandas, NumPy, and Matplotlib are used for data analysis. The `Investigate Hotel Business.ipynb` file presents detailed analysis steps. However, here I will only display the results of data analysis according to the research questions that have been formulated, and for the analysis steps, they can be seen in the file `Investigate Hotel Business.ipynb`.

1. Monthly hotel booking trends based on hotel types
   
 ![Data Results](https://github.com/AzamFath/investigate-hotel-business/blob/main/investigate_hotel_business_v01.png)

2. Impact of length of stay on hotel booking cancellation rates
   
 ![Data Results](https://github.com/AzamFath/investigate-hotel-business/blob/main/investigate_hotel_business_v02.png)

3. Relationship between lead time and hotel booking cancellation rates
   
 ![Data Results](https://github.com/AzamFath/investigate-hotel-business/blob/main/investigate_hotel_business_v03.png)

## Conclusion

The analysis results indicate that:

1. Both hotels experience an increase in the number of bookings during the holiday season. For Resort Hotels, the peak booking increase is in June and December, while for City Hotels, there is a peak booking increase during July and December. Additionally, City Hotels have more customers compared to Resort Hotels.

2. There is an increasing trend in the percentage of canceled bookings against Total Nights. The longer the total nights booked, the higher the percentage of booking cancellations. Additionally, City Hotels also have a steeper trend compared to Resort Hotels.

3. Both hotels have the lowest cancellation ratio with a lead time of 1 month. Additionally, the cancellation ratio for Resort Hotels is relatively stable (around 40%), while City Hotels experience a much higher cancellation ratio (above 60%) with a waiting time of around 1 year.

## Recommendations

Based on the analysis results, some recommendations that hotel business owners can consider are:

1. **Adjustment of Marketing Strategies**
Considering the increasing trend in the number of bookings during the holiday season, it is recommended for both hotels to strengthen their marketing strategies to attract more guests during this period. City Hotels can consider more aggressive marketing campaigns to attract more customers, while Resort Hotels can target guests looking for a relaxed and exclusive holiday experience.

2. **Optimization of Cancellation Policies**
Given the increasing trend in the percentage of booking cancellations with the total nights booked, it is recommended for both hotels to review their cancellation policies. They can consider offering incentives to guests booking long-term stays to reduce the risk of cancellations, or introducing more flexible cancellation policies.

3. **Improvement in Lead Time Management**
Considering that both hotels have the lowest cancellation ratio with a lead time of 1 month, it is recommended to improve their lead time management. This can be done by encouraging guests to book earlier, for example by offering discounts or special benefits for early bookings.

4. **Further Analysis of City Hotels**
Considering that City Hotels have higher cancellation ratios and steeper trends in cancellation percentages, it is recommended to conduct further analysis on the reasons behind these trends. This may include customer surveys to understand cancellation motivations, reviewing cancellation policies, or improving customer service to reduce dissatisfaction that may lead to cancellations.
