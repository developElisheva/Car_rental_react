# 🚗 Car Rental System – Client Side

An advanced system for managing and renting cars, emphasizing a convenient user interface, clean design, and advanced use of React components and third-party libraries.  
Includes role-based permissions for regular users and system administrators, enabling full management of cars, rentals, returns, pricing, and more.

## 🛠 Main Technologies
- React  
- Redux  
- React Router  
- useState / useRef / navigate hooks  
- Dynamic CSS based on status  
- Local data storage  

## 👤 User Types

### Regular User
- View a list of available cars  
- Filter by city and location  
- Make a rental:  
  - Automatically fill fields based on car selection  
  - Calculate price by rental duration  
- Return a car:  
  - Fill in car details, return date and time  
  - Calculate final price  
- Payment:  
  - Option for immediate payment with credit  
  - Fill in credit details (dummy data only)  

### System Administrator
- View all rentals  
- View all inquiries (rental history)  
- Add new vehicles  
- Edit and delete existing vehicles  
- Manage images, categories, and vehicle types  
- Set prices per vehicle type or category  

## 🔒 Data Security and Integrity Checks
- Form validation  
- Integrity check on sensitive fields (e.g., credit details) using validation libraries  
- Role-based access permissions (user / administrator)  
