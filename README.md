# Restaurant Menu - Django Project

## Introduction
This is a simple **Restaurant Menu** web application built using Django. It allows restaurant owners to manage their menu items, including adding, updating, and deleting dishes.

## Features
- User authentication (Admin panel for restaurant owners)
- Add, update, and delete menu items
- Categorize menu items (Starters, Main Course, Desserts, Beverages, etc.)
- Display menu items with images and prices
- Search functionality for menu items
- Responsive design

## Technologies Used
- **Backend:** Django (Python)
- **Database:** SQLite
- **Frontend:** HTML, CSS, Bootstrap
- **Authentication:** Django's built-in authentication system

## Installation
### Prerequisites
- Python 3.x installed
- Virtual environment 

### Setup Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/yashkumargupta12345/Restaurant-Menu.git
   cd Restaurant-Menu
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run database migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser** (for admin access)
   ```bash
   python manage.py createsuperuser
   ```
   Follow the instructions to set up an admin account.

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```
   Open your browser and go to `http://127.0.0.1:8000/`

## Usage
- **Admin Panel:** Log in at `http://127.0.0.1:8000/admin/` to manage menu items.
- **Menu Display:** Users can browse the menu and see item details.
- **Search:** Use the search bar to find menu items.

## Project Structure
```
restaurant-menu/
│── menu/                # Django app for managing the menu
│   ├── migrations/      # Database migrations
│   ├── templates/       # HTML templates
│   ├── views.py         # Application logic
│   ├── models.py        # Database models
│   ├── urls.py          # URL routing
│── static/              # Static files (CSS, JS, images)
│── templates/           # Global templates
│── db.sqlite3           # Database file (SQLite)
│── manage.py            # Django management script
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
```

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributors
- **Your Name** - [GitHub Profile](https://github.com/yashkumargupta12345)

---
Feel free to contribute by submitting issues or pull requests!

