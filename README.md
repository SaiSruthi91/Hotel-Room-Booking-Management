# 🏨 Hotel Room Booking Management System

**A Full-Stack Hotel Booking Web Application built using Flask, SQLite, and HTML/CSS**

![License](https://img.shields.io/badge/license-MIT-green.svg)  
![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)  
![Frontend](https://img.shields.io/badge/frontend-HTML%20%7C%20CSS-blue.svg)  
![Status](https://img.shields.io/badge/status-Completed-brightgreen.svg)

---

## 🧠 Project Overview

This is a **Hotel Room Booking Management System** where users can register and book hotels, select room and food options, and view hotel promotions. Staff users can register hotels, manage room and food availability, and view guest bookings.  
The app uses **Flask (Python)** for backend, **SQLite** for database, and **HTML/CSS** for the frontend.

---

## ⚙️ Technologies Used

### 🖥️ Backend
- Python 3.8+
- Flask
- SQLite3
- Jinja2

### 🎨 Frontend
- HTML5
- CSS3
- Bootstrap 5

---

## 📦 Key Features

✅ Staff and Guest registration/login  
✅ Staff can add hotels, room types (Single/Double/Suite), and food options  
✅ Guests can search for hotels and book rooms with food preferences  
✅ Responsive UI for seamless experience  
✅ All booking and hotel data stored securely in SQLite database

---

## 📁 Project Structure
````
Hotel-Room-Booking-Management/
├── app.py                      # Main Flask application
├── database.db                 # SQLite database
├── README.md                   # Project documentation

├── static/
│   ├── food_images/            # Food-related image assets
│   └── images/                 # General UI images

├── templates/
│   ├── book.html               # Guest hotel booking form
│   ├── guest_dashboard.html    # Guest dashboard
│   ├── home.html               # Home page
│   ├── hotel_list.html         # List of available hotels
│   ├── register.html           # Registration page
│   ├── signin.html             # Login page
│   ├── staff_add_hotel.html    # Staff page to add hotel
│   ├── staff_add_room.html     # Staff page to add rooms
│   ├── staff_base.html         # Base template for staff pages
│   ├── staff_dashboard.html    # Staff dashboard
│   ├── staff_foods.html        # Staff page to manage food items
│   └── staff_manage_bookings.html  # Staff booking management page
````

---

## 🖼️ Screenshots

> *(Add actual screenshots or mockups by uploading them and linking below)*

| ![Home Page](link_to_homepage_screenshot) | ![Hotel List](link_to_hotel_list_screenshot) |
|------------------------------------------|---------------------------------------------|
| ![Staff Dashboard](link_to_staff_dashboard) | ![Booking Page](link_to_booking_page) |

---

🚀 How to Run the Project

1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Hotel-Room-Booking-Management.git
cd Hotel-Room-Booking-Management
```

2️⃣ Install Dependencies
```bash
Make sure Flask is installed:
pip install flask
(If you have a requirements.txt, you can still use pip install -r requirements.txt)
```

3️⃣ Run the Application
```bash
python app.py
Then open your browser and go to:
👉 http://127.0.0.1:5000
```

---

🔮 Future Enhancements

Add booking cancellation and modification
Hotel reviews and ratings
Admin panel for system-wide controls
Email confirmation for bookings
Payment integration (e.g., Razorpay/Stripe)

--- 

📬 Contact
**Sai Sruthi Karnatakapu**
📧 [k.saisruthi913@gmail.com](mailto:k.saisruthi913@gmail.com)
🔗 [LinkedIn Profile](https://www.linkedin.com/in/saisruthi-karnatakapu/)


