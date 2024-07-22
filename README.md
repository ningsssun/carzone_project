## 🚙 Car Zone - A Used Car Selling Business Website

Car Zone is a Django web application designed for a used car business owner who aims to list cars online, allowing users to browse, search, and inquire about available vehicles.

### ⚙️ Technical Stack

- Framework: Django
- Frontend: HTML, Bootstrap
- Database: PostgreSQL
- Authentication: Login with Facebook, Login with Google
- Email Service: Django Email Functionality
- Deployment: Heroku with Gunicorn and Whitenoise for static files
- Other: RichText Editor, Multi-Select Fields in Admin, etc

### ⚙️ Features

- Car Listings: Display all, latest, and featured cars
- Search and Filter: Users can search and filter cars by model or price
- User Inquiries: Users can make inquiries about cars for sale
- Admin Customization: Customized admin panel for better management
- User Authentication: Supports login via Facebook and Google
- Pagination: Efficient page navigation for car listings
- Rich Media Management: Manage static and media files effectively

### 👩‍💻 Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ningsssun/carzone_project
   cd carzone_project
2. Setup virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Database setup:
   ```bash
   python manage.py migrate
5. Run the development server:
   ```bash
   python manage.py runserver
