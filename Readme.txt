Instructions for peers:

see secrets/tokens file for user tokens

Check that the web application use Django to serve static HTML content:
http://127.0.0.1:8000/restaurant/

API endpoints:

get all menu (GET request):
http://127.0.0.1:8000/restaurant/menu/

post menu item (POST request with title, price, inventory data provided):
http://127.0.0.1:8000/restaurant/menu/

get all bookings (GET request):
http://localhost:8000/restaurant/booking/tables/

post a booking (POST request with name, no_of_guests, booking_date data provided):
http://localhost:8000/restaurant/booking/tables/

get token (POST request with username and password provided):
http://127.0.0.1:8000/restaurant/api-token-auth/
