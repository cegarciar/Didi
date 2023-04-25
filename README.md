# Didi
Didi Business Intelligence Challenge

We have the following data. 

The file ‘restaurants_visitors.csv’ has the next five columns:
-id: Has the id of a restaurant in Japan and it is unique per restaurant.
-reserve_visitors: Has the amount of visitors that the restaurant of the row had at the date and time of the column visit_datetime.
-visit_datetime: Has the date and the hour of the day.
-visit_date: Has the date extracted from the column visit_datetime.
-reserve_datetime: Hour of the reservation.

The file ‘date_info.csv’ has the next three columns:
-calendar_date: Has the calendar date
-day_of_week: Has the day of the week that corresponds with the calendar date of the row. Format: ()
-holiday_flg: Has a dummy variable that value 1 if the calendar day is a holiday in Japan and 0 if is not.

The file ‘store_info.csv’ has the next five columns:
-store_id: Same id that in the  ́restaurants_visitors.csv’ file. -genre_name: Genre (type) of the restaurant in the row. -area_name: City or geological area of the restaurant. -latitude: Latitude coordinate of the restaurant. -longitude: Longitude coordinate of the restaurant.[restaurants_visitors.csv]
