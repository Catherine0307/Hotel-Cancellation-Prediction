# Hotel-Cancellation-Prediction

![Hotel-Booking-1280x720](https://user-images.githubusercontent.com/128668596/228053799-fae98a6f-3bec-478d-8a89-1372cbafd5d0.jpg)

There are many aspects considered when choosing a hotel. The main idea is to find the appropriate prediction model for predicting hotel booking cancellations which finds the finest explaining variables for customer cancellations. This Hotel Booking Cancellation model can be useful not only for the vacationer but for the hotels’ owners.


## Details of Dataset
1. hotel :(H1 = Resort Hotel or H2 = City Hotel).
2. is_canceled Value: showing if the booking had been cancelled (1) or not (0).
3. lead_time: Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.
4. arrival_date_year: Year of arrival date.
5. arrival_date_month: The months in which guests are coming.
6. arrival_date_week_number: Week number of year for arrival date.
7. arrival_date_day_of_month: Which day of the months guest is arriving.
8. stays_in_weekend_nights: Number of weekend stay at night (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
9. stays_in_week_nights: Number of weekdays stay at night (Monday to Friday) in the hotel.
10. adults: Number of adults.
11. children: Number of children.
12. babies: Number of babies.
13. meal: Type of meal booked.
14. country: Country of origin.
15. market_segment: Through which channel hotels were booked.
16. distribution_channel: Booking distribution channel.
17. is_repeated_guest: The values indicating if the booking name was from a repeated guest (1) or not (0).
18. previous_cancellations: Show if the repeated guest has cancelled the booking before.
19. previous_bookings_not_canceled: Show if the repeated guest has not cancelled the booking before.
20. reserved_room_type: Code of room type reserved. Code is presented instead of designation for anonymity reasons.
21. assigned_room_type: Code for the type of room assigned to the booking. Code is presented instead of designation for anonymity reasons.
22. booking_changes: How many times did booking changes happen.
23. deposit_type: Indication on if the customer deposited something to confirm the booking.
24. agent: If the booking happens through agents or not.
25. company: If the booking happens through companies, the company ID that made the booking or responsible for paying the booking.
26. days_in_waiting_list: Number of days the booking was on the waiting list before the confirmation to the customer.
27. customer_type: Booking type like Transient – Transient-Party – Contract – Group.
28. adr: Average Daily Rates that described via way of means of dividing the sum of all accommodations transactions using entire numbers of staying nights.
29. required_car_parking_spaces: How many parking areas are necessary for the customers.
30. total_of_special_requests: Total unique requests from consumers.
31. reservation_status: The last status of reservation, assuming one of three categories: Canceled – booking was cancelled by the customer; Check-Out
32. reservation_status_date: The last status date.


## Following are the steps for the implementation.

* Exploratory Data Analysis
* Data Pre-Processing
* Model Building
* Model Comparison


## Exploratory Data Analysis
![newplot](https://user-images.githubusercontent.com/96882935/226996368-3164365d-2b8c-4d20-bd52-0a1892dabfff.png)

<img src="https://user-images.githubusercontent.com/96882935/226996470-b9ada551-cb09-4dc1-b7b9-7f521da9b68d.png" width="800" height="600">

![download-2](https://user-images.githubusercontent.com/128668596/228054576-04590e6c-f481-49ce-8ef2-7591a387d01a.png)

![newplot (1)](https://user-images.githubusercontent.com/96882935/226998378-33b74a2a-2f65-485b-a630-29d6555fe157.png)


## Building Machine Leaning Models
<img width="729" alt="Screenshot 2023-03-22 at 1 11 47 PM" src="https://user-images.githubusercontent.com/96882935/226998785-a3350b51-4310-4d7a-8fa2-111f403f325a.png">

<img width="546" alt="Screenshot 2023-03-22 at 1 12 45 PM" src="https://user-images.githubusercontent.com/96882935/226999000-6bb01987-521b-45cb-ac1d-2c325662e70c.png">

## Summary
The given dataset is a supervised classification dataset. It holds booking information for a city hotel and a resort hotel with information such as How and when the booking was made, the length of passengers’ stay with the number of parking slots available, the number of adults, children, and babies. The Logistic regression, K-Nearest Neighbor, Decision Tree, Random Forest algorithms are used to handle this supervised classification model. Among these four machine learning algorithms, Random forest and Decision trees perform well with respect to accuracy.
