# swe_22013104_gocaff
A mobile app for selecting partner cafes/vendors, ordering from them outside of its location, and picking up the order at the café/vendor location. Notifications will be sent for payment process, order status (still in progress, ready for pickup, etc.)

Requirements:
•	Functionality and UI (Flutter)
•	Real-time Database Collection (Firebase from Google, Free Plan)

Planning:
https://docs.google.com/spreadsheets/d/1hXsVGAGqngY5pJ5bGbC2D2nWK-hChojHfJlWCZmBV0w/edit?usp=sharing
 
Application Layout:
-	User Login Page
o	Create account or sign in
-	User Account Page
o	Modify account information: name, date of birth, email address, password, etc.
-	Homepage (pick café)
o	Display available vendors/cafes
o	Location information (maybe if not too complicated, distance of cafe from user’s device)
-	Order at café
o	Picking which items to order
-	Payment for user’s order
o	Card or Kakaopay (any other mobile banking service)
-	Show order status and progress
o	Order number/code
o	Estimated duration until order is ready
o	If the order is ready for pickup
o	Cancellation from vendor, etc.
-	After pickup, the vendor will confirm pickup, or user can do so manually
