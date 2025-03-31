# POS_Services
Backend service layer for the POS system, providing APIs for managing order processing and user authentication.

# API for transaction processing:

1. Login : POST request and get response the Token.
2. Home page: GET all active orders.
3. Create New Order: POST request customer's phone.
4. Skip button: PUT request .
5. Click "OK" button at "Enter customer's phone number" page: GET request and check if:
   - POST request with new customer.
   - PUT request with available customer.
6. Click "OK" button at "Enter customer's phone number" page: PUT request, add name for new customer.
7. Menu page : GET request all services and all staffs.
8. Select Staff: PUT request to update order.
9. Select service : PUT request to update service to order.
10. Check-out button: PUT request to update status of order(ACTIVE -> DONE)
11. Open order history: GET request with all orders status DONE
12. Open Voided page: GET request with all orders status VOIDED

# Database design documents: 
Use SQL-server for POS system. And all needed tables:
1. Customers.
2. Staffs.
3. Products.
4. Orders.
5. OrderItem.
   <img width="1213" alt="Screenshot 2025-03-30 at 6 19 44 PM" src="https://github.com/user-attachments/assets/c56341d6-4fbe-4e4e-8300-1eff53db6e66" />


#Installation:
 Clone the repository:
     git clone https://github.com/ThuyPhamict/POS_Services.git
  2. Install NPM packages:
     npm install
  



