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

Hotel-Room-Booking-Management/
├── app.py # Main Flask app
├── database.db # SQLite database

├── requirements.txt # Python dependencies
├── README.md # Project documentation

├── static/
│ ├── css/
│ │ └── style.css # Custom styles
│ └── images/ # Image assets

├── templates/
│ ├── index.html # Homepage with Register/Login
│ ├── register.html # Staff/Guest registration
│ ├── login.html # Login page
│ ├── staff_dashboard.html # Staff hotel management dashboard
│ ├── guest_dashboard.html # Guest hotel booking dashboard
│ ├── book_hotel.html # Hotel room and food booking form
│ ├── hotel_list.html # Display available hotels

└── venv/ # Virtual environment

yaml
Copy
Edit

---

## 🖼️ Screenshots

> *(Add actual screenshots or mockups by uploading them and linking below)*

| ![Home Page](link_to_homepage_screenshot) | ![Hotel List](link_to_hotel_list_screenshot) |
|------------------------------------------|---------------------------------------------|
| ![Staff Dashboard](link_to_staff_dashboard) | ![Booking Page](link_to_booking_page) |

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Hotel-Room-Booking-Management.git
cd Hotel-Room-Booking-Management
2️⃣ Set Up Virtual Environment
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # On Windows
# OR
source venv/bin/activate  # On macOS/Linux
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Application
bash
Copy
Edit
python app.py
Open your browser and go to: http://127.0.0.1:5000

🔮 Future Enhancements
Add booking cancellation and modification

Hotel reviews and ratings

Admin panel for system-wide controls

Email confirmation for bookings

Payment integration (e.g., Razorpay/Stripe)

📬 Contact
Sai Sruthi Karnatakapu
📧 k.saisruthi913@gmail.com
🔗 LinkedIn

yaml
Copy
Edit

---

Let me know if you want the badges updated with your actual GitHub repo, or if you’d like help adding real screenshot image links.
