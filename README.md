# 🏨 Hotel Management Dashboard

A web-based hotel management system built using **Laravel**, designed to help administrators manage room types, bookings, and customer data efficiently through a secure dashboard.

---

## 🚀 Features

- Admin authentication and role-based access control
- Dashboard overview with room & booking stats
- CRUD operations for:
  - Room Types
  - Rooms
  - Bookings/Orders
- User profile management
- Admin panel with sidebar navigation
- Responsive UI built with Blade templates

---

## 🛠️ Tech Stack

- **Backend:** Laravel 10+
- **Frontend:** Blade, Bootstrap/CSS
- **Database:** MySQL
- **Authentication:** Laravel Auth
- **AJAX (optional):** For dynamic search/filtering

---

## ⚙️ Installation

1. **Clone the repository**
   git clone https://github.com/your-username/hotel-management-dashboard.git
   cd hotel-management-dashboard

2. **Install dependencies**
    composer install
    npm install && npm run dev   # (if using Laravel Mix)

3. **Set up environment**
   cp .env.example .env
   php artisan key:generate

4. **Configure database**
   **Update .env with your MySQL credentials:**
   DB_DATABASE=hotel_db
   DB_USERNAME=root
   DB_PASSWORD=

5. **Run migrations and seeders**
   php artisan migrate --seed

6. **Start the development server**
   php artisan serve

7. **Access**
   http://127.0.0.1:8000


👨‍💻 Author
Abhishek Badadhe
Laravel Developer | PHP | MySQL | Web Development
📍 Sinnar, Nashik, Maharashtra, India
📧 abhibadadhe43@gmail.com
