# Hotel_Guest_Booking_Analysis_ML_Models

---

# **Data Information**

***Idea***
---

The online hotel reservation channels have dramatically changed booking possibilities and customers’ behavior. A significant number of hotel reservations are called-off due to cancellations or no-shows. The typical reasons for cancellations include change of plans, scheduling conflicts, etc. This is often made easier by the option to do so free of charge or preferably at a low cost which is beneficial to hotel guests but it is a less desirable and possibly revenue diminishing factor for hotels to deal with.

***Column Detail***
---

* *Features*
  * **Booking_ID** $:$ *unique identifier of each booking*
  * **no_of_adults** $:$ *Number of adults*
  * **no_of_children** $:$ *Number of Children*
  * **no_of_weekend_nights** $:$ *Number of **weekend nights (Saturday or Sunday)** the guest stayed or booked to stay at the hotel*
  * **no_of_week_nights** $:$ *Number of **week nights (Monday to Friday)** the guest stayed or booked to stay at the hotel*
  * **type_of_meal_plan** $:$ *Type of meal plan booked by the customer:*
    * *Mean Plan 1*
    * *Mean Plan 2*
    * *Mean Plan 3*
    * *Not Selected*
  * **required_car_parking_space** $:$ *Does the customer require a car parking space?*
    * *0 : No*
    * *1 : Yes*
  * **room_type_reserved** $:$ *Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels.*
    * *Room Type 1*
    * *Room Type 2*
    * *Room Type 3*
    * *Room Type 4*
    * *Room Type 5*
    * *Room Type 6*
    * *Room Type 7*
  * **lead_time** $:$ *Number of days between the date of booking and the arrival date*
  * **arrival_year** $:$ *Year of arrival date*
  * **arrival_month** $:$ *Month of arrival date*
  * **arrival_date** $:$ *Date of the month*
  * **market_segment_type** $:$ *Market segment designation.*
  * **repeated_guest** $:$ *Is the customer a repeated guest?*
    * *0 : No*
    * *1 : Yes*
  * **no_of_previous_cancellations** $:$ *Number of previous bookings that were canceled by the customer prior to the current booking*
  * **no_of_previous_bookings_not_canceled** $:$ *Number of previous bookings not canceled by the customer prior to the current booking*
  * **avg_price_per_room** $:$ *Average price per day of the reservation; prices of the rooms are dynamic. (in euros)*
  * **no_of_special_requests** $:$ *Total number of special requests made by the customer (e.g. high floor, view from the room, etc)*


* *Target*
  * **booking_status** $:$ *Flag indicating if the booking was canceled or not.*
    * *Cancelled*
    * *Not_Cancelled*

Have a look at the notebook for **data analysis** and **model building**.

Notebook : https://www.kaggle.com/code/utkarshsaxenadn/hotel-guest-analysis-model-comparision
Kaggle Account : https://www.kaggle.com/utkarshsaxenadn
LinkedIn : https://www.linkedin.com/in/utkarsh-saxena-deepnets/
