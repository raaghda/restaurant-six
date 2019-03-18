# Six
Restaurant
Minimalistic restaurant website. 
Restaurant has two seatings every evening, at 18.00 and 21.00. The tables are therefore bookable twice a night. The visitor can search available tables for a given date and for upto six guests. Form informes of collection of personal information requested to make a booking, inform about GDPR, and confirm a booking has been made. There is further an admin mode for restaurant staff: where reservations are administrated (modified, deleted, added).

Technical Description

- Creation and usage of API
- When choice of time and date have been made, a form will appear where the user can type name, email address and phone number. Save or cancel (reservation in db via an API call)
- For admin mode: simpler CRUD against the database and a simple interface
- App pages set with react router
- Forms contain validation and error messages
- Confirmation is sent to user through email where cancellation is also managed
