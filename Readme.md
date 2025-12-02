Little Lemon Restaurant API

Here are the API endpoints to test:

1. User Registration and Authentication:
   - Create User: POST /auth/users/
   - Login (Get Token): POST /auth/token/login/

2. Menu Operations:
   - List/Create Menu Items: GET/POST /restaurant/menu/
   - Retrieve/Update/Delete Menu Item: GET/PUT/DELETE /restaurant/menu_item/{id}/

3. Booking Operations (Requires Authentication):
   - List/Create Bookings: GET/POST /restaurant/booking/
   - Retrieve/Update/Delete Booking: GET/PUT/DELETE /restaurant/booking/{id}/

Note: For authenticated requests, include the header:
Authorization: Token <your_token>
