# Logistics-Transportation-Analysis

## Introduction 
From an industry-wide perspective, disruptions in transportation and logistics contribute to supply chain disruptions, increased operational costs, and inefficiencies in freight movement. Whether in road, rail, air, or sea transport, delays can lead to congestion at ports and distribution hubs, increased fuel consumption, and higher carbon emissions, further impacting environmental sustainability.

Understanding the key factors contributing to disruptions is crucial for developing strategies to minimize their impact. Therefore, In today's fast-paced supply chain industry, optimizing shipment efficiency, reducing delivery times, and enhancing operational visibility are critical for success. **The goal of this project is to explore and derive actionable insights that drive decision making** from a real-world logistics tracking dataset, featuring shipment records, GPS tracking, vehicle information, and transportation distances.

## Strategy Implemented 🎯 

To effectively analyze the Logistics & Transportation data and provide actionable insights, I followed a systematic approach:
   1. **Business and Data understanding:** I started with making research on logistics processes, understanding the key [business questions](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/Intro%20%26%20Brief_Challenge%2024_English.docx) and Exploring the metadata and [data](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/Transportation%20%26%20Logistics%20Tracking%20Dataset.xlsx) to understand data structure and contents.
 
   2. **Data Cleaning & Transformation:** By removing duplicates and unnecessary columns e.g (Driver No), creating new columns both calculated and conditional colums, and creating a star schema model of the data. ![Image](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/ERD.PNG)

   3. **Exploratory Data Analysis (EDA):** Exploring the data, creating dax measures for key metrics and analyzing the data to answer the key business questions thereby identifying patterns and insights from the data.

   4. **Dashboard Development:** To visualize these insights effectively, I built a dynamic dashboard. The dashboard allows the monitoring of logistics performance and identifies delay causes.

   5. **Suggestions for Improvement:** Finally, based on the data analysis, I provided suggestions and strategies for reducing delay rate and optimizing efficiency.


## Insights 💡
Logistics Performance Overview 
![Image](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/Logistics%20%26%20Transport%20Tracking_page-0001.jpg)

Overall Booking Performance:
Total Bookings: 3,582
*On-Time Rate: 39%* (indicating a low efficiency in timely deliveries)
*Delay Rate: 61%* (high delay percentage, requiring investigation)
On average, *delivery takes: 9 days* after *7 days delay* from the planned delivery day.
Average Distance: 806 km
Also, the *Lead time is averagely 15hrs* (i.e the time between when the booking is made and when the delivery started) indicating that most shipments starts within 24hrs of booking. 

Booking Trends:
Monthly Booking is Peak in mid-year (June-August) and also January, but with noticeable spikes in delayed deliveries.

Peak booking time: 
Most bookings happen between 13:00 - 18:00 (1 PM - 6 PM) across all weekdays.
The second busiest period is 6:00 - 12:00 (6 AM - 12 PM).
Very few bookings occur between 0:00 - 5:00 AM, indicating minimal activity at night.

Day-wise Booking Trends:
Monday to Thursday show the highest volume of bookings.
Friday sees a decline in bookings,
while Saturday and Sunday have the lowest bookings, with Sunday showing very little activity.

Logistics Delay Analysis 
![Image](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/Logistics%20%26%20Transport%20Tracking_page-0002.jpg)


Check out the [Online Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmQxZTk1OGQtZjMzMi00YzgyLWI4YWYtMWM0MzI2NzhkYjUxIiwidCI6IjczMDc4ZWNkLWYzM2UtNDQxYy05ODYyLWVhZDdjNjFhNGU4MiJ9)
## Recommendations 🛠️
