🚗 Office Vehicle Booking System
📌 What is this system?

This is a web-based system that helps an office manage its vehicles.

👉 Employees can:

Book vehicles for work
Choose date & time
Send trip details

👉 Admin can:

Manage vehicles
Assign drivers
Monitor all bookings
👥 Who uses this system?
👨‍💼 Admin
Adds new vehicles (e.g., CAR-001)
Assigns drivers (name + WhatsApp number)
Views all bookings
Edits or deletes vehicles
Sends WhatsApp messages to drivers
👩‍💻 Employee
Logs into the system
Sees available vehicles
Books a vehicle with date & time
Cannot book already booked time (blocked)
Views their booking history
⚙️ How the system works (Step-by-step)
1️⃣ Login
User logs in as Admin or Employee
2️⃣ Vehicle Booking (Employee)
Select vehicle
Select date
Select time
Enter:
Purpose
Destination
Click Book

👉 System checks:
❌ If already booked → Not allowed
✅ If free → Booking confirmed

3️⃣ WhatsApp Notification

After booking:

👉 Driver gets a WhatsApp message like:

Hello Sandu,

You have a new vehicle booking.

Vehicle: Toyota Corolla (CAR-001)
Date: 2026-03-25
Time: 10:00 - 12:00
Booked By: Employee One
Purpose: Client visit
Destination: POB Office
4️⃣ Admin Management

Admin can:

Add / Edit / Delete vehicles
Assign drivers
See all bookings in one place
🧠 Smart Features

✔ Prevents double booking (same time blocked)
✔ Shows unavailable time slots
✔ Automatically notifies driver
✔ Works without internet server (no backend)
✔ Saves data in browser (localStorage)

💾 Where is data stored?

All data is saved in the browser using:

Users
Vehicles
Bookings
Logged user

👉 No database needed

🛠️ Technologies Used
Technology	Purpose
HTML	Structure
CSS	Design (glass UI)
JavaScript	Logic
LocalStorage	Save data
WhatsApp API	Send messages
🚀 How to run the system
Download project
Open folder
Double click index.html

👉 That’s it — no installation needed

🔐 Demo Accounts

Admin:

Email: admin@office.com
Password: 1234

Employees:

employee1@office.com
employee2@office.com
Password: 1234
🔮 Future Improvements (Ideas)
Add Firebase (real database)
Email notifications
Mobile app version
Driver availability calendar
Export reports (PDF/Excel)
