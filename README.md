# Gas-Utility-Management-System
A web-based application developed using Django to help a gas utility company efficiently manage customer service requests. The application provides a seamless experience for customers to submit and track their service requests, while customer support representatives can manage and resolve these requests effectively.


📌 Features
✅ For Customers
Submit Service Requests: Request gas installation, repairs, or inspections with detailed descriptions and attachments.

Track Request Status: Monitor the progress of submitted requests in real-time.

Manage Account: View and update account details like address and phone number.

✅ For Admins and Support Representatives
Manage Service Requests: View, update, and resolve customer requests.

Customer Management: Access and update customer information.

Admin Panel: Leverage Django’s built-in admin panel for efficient management.

🛠 Tech Stack
Backend: Django & Django Rest Framework (DRF)

Database: SQLite (Can be switched to PostgreSQL or MySQL)

Authentication: Session and Token Authentication

Admin Management: Django Admin Panel



** Installation **



python -m venv env

env\Scripts\activate   

pip install -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
