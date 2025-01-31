# Hotel-Booking-Analysis

# Project Summary

This Project was given to us by the Anudip Foundation team with an intention to understand the Business done by Hotel Group. This Dataset had two hotels City Hotel and Resort Hotel.The data provided was for 3 years 2015 , 2016 and 2017.we also have the revenue and booking details with number of days of stay and booking cancellation,total number of guests including children. It also specifies guests wait period for booking , repetation of guests,their food choices among others.The data also gives us an analysation of countries from which bookings have been done. We also a agent and other channels who also help in business by booking rooms for guests on the resort and city hotel behalf.

The data is divided between city hotel and resort hotel. Hence we can make a fair comparision between both.

Before visualize any data from the data set We will do the data cleaning as to fill any null values and delete any duplicated values and after that we have to do data wrangling.

Also we will do our analysis for both city and resort as individual businesses and in comparision to one another. We will also take help of charts for better analysis.

# Dataset:
The given dataset have information of city and resort hotel. This dataset have 119389 rows and 32 coulumns. The columns from the dataset is as follows:

 Hotel: Type of hotel(City or Resort)

is_cancelled: If the booking was cancelled(1) or not(0)

lead_time: Number of days before the actual arrival of the guests

arrival_date_year: Year of arrival date

arrival_date_month: Month of arrival date

arrival_date_week_number: Week number of year for arrival date

arrival_date_day_of_month: Day of arrival date

stays_in_weekend_nights: Number of weekend nights(Saturday or Sunday) spent at the hotel by the guests.

stays_in_weel_nights: Number of weeknights(Monday to Friday) spent at the hotel by the guests.

adults: Number of adults among the guests

children: Number of children

babies: Number of babies

meal: Type of meal booked

country: country of the guests

market_segment: Designation of market segment

distribution_channel: Name of booking distribution channel

is_repeated_guest: If the booking was from a repeated guest(1) or not(0)

previous_cancellation: Number of previous bookings that were cancelled by the customer prior to the current booking

previous_bookings_not_cancelled: Number of previous bookins not cancelled by the customer prior to the current booking

reserved_room_type: Code from room type reserved

assigned_room_type: Code of room type assigned

booking_changes: Number of changes made to the booking

deposit_type: Type of deposite made by the guest

agent: ID of travel agent who made the booking

comapny: ID of the company that made the booking

days_in_waiting_list: Number of the days the booking was in the waiting list

customer_type: Type of customer, assuming one of four categories

adr: Average daily rate

required_car_parking_spaces: Number of car parking spaces required bt the customer

total_of_special_requesrs: Number of special requests made by the customer

reservation_statuse: Reservation status(Canceled, check-out or no-show)

reservation_status_date: Date at which the last reservation status was updated

# Overall conclusion:

1.We found that 61.07% preferred city hotel and 38.93% preferred to book a resort hotel

2.The city hotel has made more number of bookings in years 2016 and 2017.The resort did have more bookings in 2016 but there was a noticeable decline in 2017.

3.The city hotels have more ADR that means City hotels Generate more Revenue than Resort Hotels

4.91.6 % guests did not required the parking space. only 8.3 % guests required only 1 parking space.

5.City hotel bookings had a higher waiting time.

6.Here, we found that overall more than 27% of booking got cancelled

7.The month of July and August had the most Bookings. Summer vaccation can be the reason for the bookings.

8.Agent no. 9 and 240 made highest bookings, where as least number of bookings are made by agent no 1 and 6

9.The maximum bookings have been done from Portugal,United Kingdom France and Spain.

10.The maximum bookings is done through Online TA and Offline TA/TO.

11.Room type A and D have been booked maximum in the last 3years.

12.We have a very small percentage of clients repeating the hotel and though we have a large clientile

13.From above insight we have found that the avrage stay length is 7 days for both types

14.Bed and Breakfast(BB)is the most preferred type of booking for Guest.

15.arrival_date_year and arrival_date_week_number columns has negative correlation which is -0.51 stays_in_week_nights and total_stay has positive correlation which is 0.95

16.As the total number of people increases adr also increases.Thus adr and total people are directly proportional to each other.
