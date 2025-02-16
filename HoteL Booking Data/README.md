# Hotel Demand Analysis Project
## 1. Project Overview

This project analyzes hotel booking demand using a dataset sourced from Kaggle.  The goal is to understand and predict hotel demand by identifying key factors that influence bookings.  The dataset contains information on various booking attributes, including:

*   Hotel type (Resort Hotel or City Hotel)
*   Booking dates (Arrival and departure)
*   Guest demographics (Adults, children, babies, country of origin)
*   Room type (Reserved and assigned)
*   Cancellation status
*   Market segment (e.g., Online TA, Offline TA/TO)
*   Distribution channel (e.g., TA/TO, Direct)
*   Booking characteristics (Lead time, stays in weekend/week nights, meal type, etc.)

The analysis aims to identify key drivers of hotel demand, understand visitor demographics, and provide insights that can help hotels optimize operations, improve customer satisfaction, and increase revenue.

## 2. Data Understanding

The dataset provides a comprehensive view of hotel bookings, encompassing various aspects from booking details to guest characteristics.  The following sections provide a detailed overview of the key features:

### 2.1 Booking Information

*   **Hotel:** Type of hotel (Resort Hotel or City Hotel).
*   **Is Canceled:** Binary indicator (0 or 1) if the booking was canceled.
*   **Lead Time:** Number of days between booking and arrival.
*   **Arrival Date:** Year, month, week number, and day of month.
*   **Stays in Weekend/Week Nights:** Number of weekend and week nights booked.

### 2.2 Guest Demographics and Details

*   **Adults, Children, Babies:** Number of each type of guest.
*   **Meal:** Type of meal booked (e.g., BB, HB, FB).
*   **Country:** Country of origin.
*   **Market Segment:** Market segment of the booking (e.g., Online TA, Offline TA/TO).
*   **Distribution Channel:** How the booking was made (e.g., TA/TO, Direct).
*   **Is Repeated Guest:** Binary indicator if the guest is a repeat customer.

### 2.3 Room and Booking Characteristics

*   **Reserved Room Type:** Type of room reserved.
*   **Assigned Room Type:** Type of room actually assigned.
*   **Booking Changes:** Number of changes made to the booking.
*   **Deposit Type:** Type of deposit made (e.g., No Deposit, Non Refund).
*   **Agent, Company:** ID of the booking agent or company.

### 2.4 Booking Status and Price

*   **Days in Waiting List:** Number of days the booking was on the waiting list.
*   **Customer Type:** Type of customer (e.g., Transient, Contract).
*   **ADR (Average Daily Rate):** Average daily price of the room.
*   **Required Car Parking Spaces:** Number of car parking spaces requested.
*   **Total of Special Requests:** Number of special requests made by the guest.
*   **Reservation Status:** Current status of the reservation (e.g., Check-Out, Canceled).

## 3. Project Methodology

This section will detail the steps taken in the analysis, including:

*   Data cleaning and preprocessing
*   Exploratory data analysis (EDA)
*   Visualization and insights generation

## 4. Results and Findings


*   Key factors influencing hotel demand Targeting Portugal in Marketing strategies while expanding to othe european countries is essential
*   Visitor demographics and proportions majority are adults compared to Children and Babies assumptions made are that most adults visits the hotels accompanied by Children or Babies
*   Insights into booking patterns and trends whereby July/Agust is the peak period to book with January and November with a low ratio
*   Recommendations for hotels based on the analysis most customers prefer City hotel compared to Resort hotel


## 6.  Dependencies 

*   pandas
*   numpy
*   matplotlib
*   seaborn


## 7.  Dataset Source

[Link to the Kaggle dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
[Link to Tableau](https://public.tableau.com/shared/FH2DP26SQ?:display_count=n&:origin=viz_share_link)

## For more information
email : kipropgibson13@gmail.com
The contents are as follows:
* Data
* Images
* .gitignore
* HotelDemandData.ipynb
* README.md
Hotel 
