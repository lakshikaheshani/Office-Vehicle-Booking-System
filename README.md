🚗 Office Vehicle Booking System
A modern Office Vehicle Booking System built with HTML, CSS, and JavaScript.
This system allows employees to book company vehicles while enabling administrators to manage vehicles, drivers, and bookings efficiently.

The application includes role-based login, vehicle scheduling, driver assignment, and WhatsApp notifications for instant communication.

✨ Features
👤 User Roles
Admin
Manage vehicles
Assign drivers
View all bookings
Edit or delete vehicles
Notify drivers via WhatsApp
Dashboard statistics
Employee
View available vehicles
Book vehicles with date & time
Prevent overlapping bookings
View blocked time slots
View personal booking history
Notify driver automatically via WhatsApp
🧩 Functional Highlights
Prevents duplicate vehicle booking times
Displays blocked time slots
Stores data in browser localStorage
Sends WhatsApp message automatically to driver
Clean modern UI with glassmorphism design
Fully responsive layout
Role-based dashboard (Admin / Employee)
🛠️ Technologies Used
Technology	Purpose
HTML5	Structure
CSS3	Styling & responsive design
JavaScript (Vanilla JS)	Application logic
LocalStorage	Data persistence
WhatsApp API	Driver notification
📂 Project Structure
office-vehicle-booking-system
│
├── index.html    # Main application file
└── README.md     # Project documentation
🔐 Demo Login Credentials
Admin Login
Email: admin@office.com
Password: 1234
Employee Login
Email: employee1@office.com
Password: 1234
Email: employee2@office.com
Password: 1234
🚀 How to Run the Project
Download or clone the repository
git clone https://github.com/your-username/office-vehicle-booking-system.git
Open the project folder
Double click index.html
OR open in browser:
Right click → Open with → Chrome
No installation required ✅

📊 System Workflow
Admin
Login as admin
Add vehicle details
Assign driver details
View all bookings
Notify drivers using WhatsApp button
Employee
Login as employee
Select available vehicle
Choose booking date and time
Enter purpose & destination
Confirm booking
WhatsApp opens automatically to notify driver
📱 WhatsApp Notification Format
Driver receives a message like:

Hello Sandu,

You have a new vehicle booking.

Vehicle: Toyota Corolla (CAR-001)
Date: 2026-03-25
Time: 10:00 - 12:00
Booked By: Employee One
Purpose: Client visit
Destination: POB Office

Please be ready for the trip.
💾 Data Storage
All data is stored in browser localStorage:

users
vehicles
bookings
current logged user
No backend required.

🔮 Future Improvements
Possible enhancements:

Firebase integration
Email notifications
Driver availability calendar
Mobile app version
Vehicle maintenance tracking
Role permissions management
Export booking reports (PDF/Excel)
🧑‍💻 Author
Developed for internal office transport management.

📄 License
This project is free to use for learning and internal company use.
