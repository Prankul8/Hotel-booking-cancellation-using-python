# Hotel Booking Cancellation Analysis

This project analyzes cancellation trends in hotel bookings, focusing on City Hotels and Resort Hotels. High cancellation rates have negatively impacted revenue and occupancy rates, leading to inefficiencies in hotel operations. This analysis aims to provide insights and suggestions to reduce cancellations and optimize hotel revenues.




The **"Hotel Booking Cancellation"** dataset contains **119,390 entries** with **32 columns**. Here’s a brief overview of some key features:

- **hotel**: Type of hotel (either "City Hotel" or "Resort Hotel").
- **is_canceled**: Indicates if the booking was canceled (1) or not (0).
- **lead_time**: Number of days between booking and arrival.
- **arrival_date_year/month/week_number/day_of_month**: Detailed information about the arrival date.
- **stays_in_weekend_nights** and **stays_in_week_nights**: Number of weekend and weekday nights stayed.
- **adults**, **children**, **babies**: Number of guests by category.
- **meal**: Type of meal booked.
- **country**: Guest’s country of origin.
- **market_segment** and **distribution_channel**: Source of booking (e.g., travel agents, groups).
- **adr**: Average daily rate (price per day of stay).
- **reservation_status**: Current status of the reservation (e.g., "Check-Out", "Canceled").
---

## Table of Contents

- [Business Problem](#business-problem)
- [Assumptions](#assumptions)
- [Research Questions](#research-questions)
- [Hypotheses](#hypotheses)
- [Analysis and Findings](#analysis-and-findings)
- [Suggestions](#suggestions)
- [Conclusion](#conclusion)

---



## Business Problem 

City Hotels and Resort Hotels have observed high cancellation rates, resulting in:

- Lower revenues
- Suboptimal room utilization

### Objective
To identify the factors driving cancellations and provide actionable business advice to reduce cancellation rates and enhance hotel revenue generation.

## Assumptions

- No unusual events between 2015 and 2017 significantly affected the data.
- The data reflects current trends and is applicable for future planning.
- Recommendations have not been previously implemented by the hotels.
- Cancellations leave rooms vacant for the booked duration.
- Customers generally cancel within the same year they booked.

## Research Questions

1. What factors influence hotel reservation cancellations?
2. How can hotels minimize cancellations?
3. How can data insights guide hotels in pricing and promotional strategies?

## Hypotheses

- Higher prices lead to increased cancellations.
- A longer waiting list correlates with a higher cancellation rate.
- Most clients book through offline travel agents.

## Analysis and Findings

### Key Insights

1. **Cancellation Rates**  
   - 37% of clients canceled their reservations, impacting revenue significantly.

2. **Hotel Type Comparison**  
   - City hotels experience higher bookings compared to resort hotels, possibly due to cost differences.

3. **Daily Rate Fluctuations**  
   - Resort hotels have higher daily rates, especially on weekends and holidays.

4. **Monthly Cancellation Trends**  
   - August has the highest confirmed and canceled bookings, while January sees the most cancellations.

5. **Pricing Influence on Cancellations**  
   - Higher room prices lead to increased cancellations, as illustrated by the bar graph analysis.

6. **Geographical Impact**  
   - Portugal shows the highest cancellation rate.

7. **Booking Sources**  
   - 46% of clients book through travel agencies, 27% through groups, and only 4% directly with the hotel.

## Suggestions

1. **Pricing Strategy**  
   - Implement dynamic pricing to lower rates in specific locations or seasons.
   - Offer discounts for resort hotels during weekends and holidays to reduce cancellations.

2. **Targeted Marketing**  
   - Conduct marketing campaigns in January to reduce the high cancellation rate in that month.

3. **Quality Improvement**  
   - Enhance services, particularly in Portugal, to decrease cancellation rates.

---

## Conclusion

This project provides actionable insights into the factors influencing hotel cancellations, highlighting the importance of pricing strategies and seasonal promotions. The findings can help hotels optimize room occupancy and maximize revenue.

---

## Report 

This project was conducted using data analysis techniques in Python.

**Presented by Prankul Wadhwa, 2024**
