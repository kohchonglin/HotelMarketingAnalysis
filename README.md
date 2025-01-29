# The Reverie Hotel Dashboard and Marketing Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [About Data](#about-data)
- [The Reverie Dashboard](dashboard)
- [Key Insights and Recommendations](key-insights-and-recommendations)

### Project Overview
The shareholders of The Reverie have requested a dashboard to analyze the performance of past bookings, along with customer profiles and preferences. Additionally, they seek actionable insights to support the development of a targeted and impactful marketing campaign.

### About Data
Dataset retrieved from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data).

The data used in this project is being adapted to represent a hotel within the fictional universe of Honkai: Star Rail.
To match the project context, I modified several name entries in the dataset like Resort Hotel/City Hotel to Reality/Dreamscape and Meal Codes to names of dishes in the game.

Data cleaning is performed using Excel before importing into Tableau.

### Dashboard
![TheReverieDashboard](https://github.com/user-attachments/assets/06fd65c7-d0ab-4e20-bf47-56101577f9f7)  
[Click here to view dashboard ](https://public.tableau.com/app/profile/chong.lin.koh/viz/TheReverieHotel/TheReverieDashboard?publish=yes)  

The dashboard is divided into three distinct categories:  
Bookings Overview: Displays the average number of bookings and ADR, analyzed by seasonality and reservation status.   
Customer Information: Provides insights into the guests' origins, the breakdown of adults and children, and their booking methods.  
Customer Preferences: Highlights guests' preferred room types and meal choices.  

### Key Insights and Recommendations
1. Observing the dashboard, the off-peak period from November to January records the lowest number of bookings. Additionally, the chart below reveals that a lead time of 15 to 80 days achieves the highest average ADR and the lowest cancellation rate.  
![HighADRLowCancellation](https://github.com/user-attachments/assets/8c56a9ad-99a9-44c8-afaf-5b4c2d5a0969)  
**Recommendation:** Launch the marketing campaign 80 days ahead of the off-peak period from November to January to maximize the benefits of the optimal ADR and low cancellation rate

2. Online Travel Agencies (Online TA) generate the highest number of bookings, even during off-peak periods, as illustrated in the heatmap below. However, the repeat rate for Online TA is notably low, at just 1.53%.
![MarketSegment](https://github.com/user-attachments/assets/ed4d57f2-287f-47a3-a63e-c6dedd3cde41)  
**Recommendation:** Create a marketing campaign that introduces loyalty programs, exclusive return offers, and discounts for repeat stays, particularly targeting the Online TA market segment. This strategy aims to foster stronger connections with guests, boosting the repeat rate while increasing bookings during the off-peak period.

3. The chart below illustrates the correlation between guests with children and the average ADR. As the percentage of guests with children or babies increases, the ADR also rises.  
![ADRGuestwithChildren](https://github.com/user-attachments/assets/9ce8e4e8-41d5-4fdd-a915-34753bde8bfb)  
**Recommendation:** Focusing marketing efforts on families or guests traveling with children is recommended, as this demographic tends to have a higher average ADR. Targeting this group specifically can help increase overall ADR and drive more revenue for the hotel.





