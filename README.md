# Exploratory-Data-Analysis-of-Hotel-Booking-Dataset

EDA on the Hotel Booking Dataset Performing EDA on the Hotel Booking Dataset

## What is EDA?
Exploratory Data Analysis refers to the critical process of performing initial investigations on data to discover patterns, to spot anomalies, test hypotheses and check assumptions with the help of summary statistics and graphical representations.

Exploratory Data Analysis (EDA) is an approach to analyze the data using visual techniques. It is used to discover trends, and patterns, or to check assumptions with the help of statistical summaries and graphical representations.

## Steps involved in EDA:-
● Data Analysis (Data Pre-processing, Cleaning and Manipulation).

● Data Visualisation (Visualize relationships in data using different types of plots).

## About Hotel Booking Dataset
* hotel : Hotel(There is only two categories one is resort hotel and other is city hotel)
* is_canceled : The value represents 1 if the booking is canceled or it represents 0 .
* lead_time :It is the number of days between the time a guest books their room and the time they are scheduled to arive at the hotel.
* arrival_date_year : It indicates the year in which the guest will arrive to the hotel.
hotel : Hotel(There is only two categories one is resort hotel and other is city hotel)
* is_canceled : The value represents 1 if the booking is canceled or it represents 0 .
* lead_time :It is the number of days between the time a guest books their room and the time they are scheduled to arive at the hotel.
* arrival_date_year : It indicates the year in which the guest will arrive to the hotel.
* arrival_date_month : It indicates the month in which guest will arrive to the hotel.
* arrival_date_week_number : This indicates the week number in which the guest will arrive to the hotel
* arrival_date_day_of_month : This indicates the day of the month in which the guest will arrive to the hotel.
* stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
* stays_in_week_nights : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
* arrival_date_month : It indicates the month in which guest will arrive to the hotel.
* arrival_date_week_number : This indicates the week number in which the guest will arrive to the hotel
* arrival_date_day_of_month : This indicates the day of the month in which the guest will arrive to the hotel.
* stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
* stays_in_week_nights : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
* adults : Number of adults
* children : Number of children
* babies : Number of babies
* meal : Type of meal booked . Categories are presented in standard hospitality meal packages:
(BB:"Bed & Breakfast"; HB:"Bed,Breakfast & Dinner ; FB: "Bed & All meals(Breakfast,Lunch & Dinner)
* country : Country of origin.
* market_segment : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
* distribution_channel : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
* is_repeated_guest : The value represents 1 if the booking name was from a repeated guest or it represents 0 .
* previous_cancellations : Number of previous bookings that were cancelled by the customer prior to the current booking
* previous_bookings_not_canceled : Number of previous bookings not cancelled by the customer prior to the current booking
* reserved_room_type : Code of room type reserved. Code is presented instead of designation for anonymity reasons.
* assigned_room_type : Code for the type of room assigned to the booking.
* booking_changes : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
* deposit_type : Indication on if the customer made a deposit to guarantee the booking.
* agent : ID of the travel agency that made the booking
* company : ID of the company/entity that made the booking or responsible for paying the booking.
* days_in_waiting_list : Number of days the booking was in the waiting list before it was confirmed to the customer
* customer_type : Type of booking, assuming one of four categories
* adr : Average Daily Rate (ADR) measures the average rental revenue earned for an occupied room per day .
"The operating performance of a hotel or other lodging business can be determined by using the ADR."
* required_car_parking_spaces : Number of car parking spaces required by the customer
* total_of_special_requests: Number of special requests made by the customer (e.g. twin bed or high floor)
* reservation_status : Reservation last status, assuming one of three categories
* Canceled – booking was canceled by the customer
Check-Out – customer has checked in but already departed
No-Show – customer did not check-in and did inform the hotel of the reason why
* reservation_status_date : Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel


The data set that is going to be used is the 'Hotel Booking Dataset'.It contains Hotel Booking data, we are going to clean the data if required and perform Exploratory Data Analysis (EDA). The tools that are going to be used for the EDA would be NumPy, Pandas, Matplotlib and Seaborn.
