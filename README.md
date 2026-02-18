## 📌 Project Overview  

The **Little Lemon Restaurant Web App** is designed to manage restaurant-related operations such as displaying restaurant pages, handling reservations, and managing data through the Django Admin Panel.  

It follows Django best practices and provides a scalable base for future enhancements like authentication and APIs.

---

## 🚀 Features  

- Dynamic restaurant website using Django templates  
- Booking / reservation management system  
- Admin dashboard for managing data  
- SQLite database integration  
- Modular Django app structure  
- Secure and scalable backend  

---

## 🧩 Tech Stack  

| Layer        | Technology        |
|--------------|-------------------|
| Backend      | Python, Django    |
| Frontend     | HTML, CSS         |
| Database     | SQLite            |
| Architecture | Django MTV        |

---

## 📂 Project Structure  

```bash
littlelemon/
│
├── restaurant/          # Main application
│   ├── migrations/
│   ├── models.py        # Database models
│   ├── views.py         # Business logic
│   ├── urls.py          # URL routing
│   ├── templates/       # HTML templates
│   └── static/          # CSS and assets
│
├── littlelemon/         # Project configuration
│
├── db.sqlite3           # Database file
├── manage.py

```
---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the Repository

```bash
git clone https://github.com/palakkayare19/Little-Lemon-Restaurant-Django-Web-Application.git
cd Little-Lemon-Restaurant-Django-Web-Application
```
2️⃣ Create Virtual Environment
```bash
python -m venv env
```
3️⃣ Activate Virtual Environment

Mac / Linux
```bash
source env/bin/activate
```
Windows 
```bash
env\Scripts\activate
```
4️⃣ Install Dependencies
```bash
pip install django
```
5️⃣ Apply Migrations
```bash
python manage.py migrate
```
6️⃣ Create Admin User
```bash
python manage.py createsuperuser
```
7️⃣ Run the Server
```bash
python manage.py runserver
```
Open in browser:
```bash
http://127.0.0.1:8000/
```
Admin panel:
```bash
http://127.0.0.1:8000/admin
```
---

## 🔐 Admin Panel Capabilities
- Manage restaurant data
- Manage bookings
- Manage menu items
- Perform full CRUD operations

--- 

## 🛣️ Future Enhancements

- User authentication (Login/Signup)
- Online food ordering system
- Payment gateway integration
- REST API using Django REST Framework
- Responsive UI using Bootstrap
- Role-based access control

---

## 🧠 Learning Outcomes
This project helped strengthen understanding of:
- Django project structure
- URL routing and views
- ORM and database models
- Template rendering
- Admin panel usage
- CRUD operations

---

## 👩‍💻 Author

- Palak Kayare
- Aspiring Backend Developer
- GitHub: 👉 https://github.com/palakkayare19

---

## 📜 License

This project is developed for educational and portfolio purposes only.




