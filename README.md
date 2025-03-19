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

#### Logistics Performance Overview: This page highlights the key metrics, booking trend analysis in monthly, hourly and daily occurrence. It also identifies the top 10 performers ranked by shipping volume for Route, Suppliers, Customers, Material flow and Drivers.

![Image](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/Logistics%20%26%20Transport%20Tracking_page-0001.jpg)

**Overall Booking Performance:**
 - Total Bookings: 3,582
 - *On-Time Rate: 39%* (indicating a low efficiency in timely deliveries)
 - *Delay Rate: 61%* (high delay percentage, requiring investigation)
 - On average, *delivery takes: 9 days* after *7 days delay* from the planned delivery day.
 - Average Distance: 806 km
 - Also, the *Lead time is averagely 15hrs* (i.e the time between when the booking is made and when the delivery started) indicating that most shipments starts within 24hrs of booking. 

**Booking Trends Analysis:**
 - Monthly Booking: is Peak in mid-year (June-August) and also January, but with noticeable spikes in delayed deliveries.
 - Peak booking time: 
   - Most bookings happen between 13:00 - 18:00 (1 PM - 6 PM) across all weekdays. The second busiest period is 6:00 - 12:00 (6 AM - 12 PM).Very few bookings occur between 0:00 - 5:00 AM, indicating minimal activity at night.
 - Day-wise Booking Trends:
   - Monday to Thursday show the highest volume of bookings.Friday sees a decline in bookings,
while Saturday and Sunday have the lowest bookings, with Sunday showing very little activity.


#### Logistics Delay Analysis: This page identifies delay analysis causes as Distance, Vehicle Type, Driver, Route and Gps provider. It shows how far shipments go and delivery time efficiency, top 10 routes where most delays occur, top 10 vehicle and driver with high delay rate and Gps provider analysis.

![Image](https://github.com/Ben-Joan/Logistics-Transportation-Analysis/blob/main/Logistics%20%26%20Transport%20Tracking_page-0002.jpg)

**Distance Analysis:**
 - Most bookings are within shorter distances (i e 0 - 500km), followed by longer distance (2000+km). But delays persist across all ranges, most occurring at the 0-500km category.
 - Delivery time increases with distance but delay does not increase at the same rate, especially at shorter distances (0-500km) which shows very poor time efficiency. Time efficiency shows the percentage of delivery time that is actually spent on transit. The very poor time efficiency at shorter distance *(11%)* indicates a severe problem which might possibly be from poor scheduling, traffic congestion or vehicle inefficiency due to high shipment volume within this distance.

Check out the [Online Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmQxZTk1OGQtZjMzMi00YzgyLWI4YWYtMWM0MzI2NzhkYjUxIiwidCI6IjczMDc4ZWNkLWYzM2UtNDQxYy05ODYyLWVhZDdjNjFhNGU4MiJ9)


## Recommendations 🛠️
