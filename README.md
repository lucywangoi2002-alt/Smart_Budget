# SmartBudget – Personal Finance Management System

SmartBudget is a modern web-based personal finance management application built with **Django** and **Bootstrap** that helps users track income, expenses, and spending categories while gaining intelligent insights into their financial habits.

The system provides a simple, clean, and interactive dashboard designed to promote better budgeting and financial decision-making.

---

## Features

### Authentication
- User registration and login system
- Secure authentication using Django Auth
- Toast notifications for user actions
- Password visibility toggle
- Form validation with disabled submit until valid

### Financial Management
- Add Income records
- Add Expense records
- Create and manage expense categories
- Organized financial tracking

### Smart Insights
- Category-based expense analysis
- Smart spending insights
- Visual reports using Chart.js
- Budget behavior monitoring

### User Interface
- Responsive Bootstrap 5 design
- Modern navbar layout
- Toast notification system
- Clean login & signup UI
- Mobile-friendly interface

---
## Screenshots

### Sign Up Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/9bebb08c-35e9-4c0d-a237-d031890711f1" />


### Login Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/4f4fee83-d9fa-49b1-90cc-bbca0458a24a" />

### Dashboard Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/75993ff3-aee4-476c-9dae-75d12e3aaa8c" />

### Income List Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/292366fa-b6a7-4dbe-a417-42cd9344d4b9" />

### Add Income Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/352c4bcf-cb84-4fe6-81ba-3c721743a861" />

### Expense list Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/ea274264-4069-4f4e-ad3a-5e5862e50251" />

### Add Expense Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/dbe556ea-cb9c-4d5b-b8d2-b29a28694100" />

### Category List Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/49ee615f-5c8e-4299-96cc-852cd7417799" />

### Add category Page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/45ee5d28-af5b-4e48-b02c-9a676f17bedd" />

### Reset page

<img width="1867" height="964" alt="Image" src="https://github.com/user-attachments/assets/f5e19ba4-0d9f-458a-80a6-d5cd7f16e6f7" />

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3, Bootstrap 5
- **Database:** PostgrSQL
- **Charts:** Chart.js
- **Authentication:** Django Authentication System

---

---

## Installation

### Clone Repository

```
git clone https://github.com/yourusername/smartbudget.git
cd smartbudget
```

 ## Create Virtual Environment
 ```
python -m venv venv
source venv/bin/activate
```

## Install requirements
```
pip install -r requirements.txt
```

## Create database
```
sudo -u postgres psql

CREATE database my_database_name;
```

### Note: Update the database information in the settings.
        - 'ENGINE': 'django.db.backends.postgresql',
        - 'NAME': .....,
        - 'USER': .....,
        - 'PASSWORD': .....,
        - 'HOST': .....,
        - 'PORT': .....,
## Create .env file
 ```
 ALLOWED_HOSTS=127.0.0.1,localhost
 DB_NAME=your-database-name
 DB_USER=your-userdb
 DB_PASSWORD=your-bd-password
 DB_HOST=localhost
 DB_PORT=5432
 EMAIL_HOST=smtp.gmail.com
 EMAIL_PORT=587
 EMAIL_HOST_USER=your-email@gmail.com
 EMAIL_HOST_PASSWORD=your-app-specific-password
 EMAIL_HOST_USER=johndoe@gmail.com
 EMAIL_HOST_PASSWORD=your-app-password
 DEFAULT_FROM_EMAIL = EMAIL_HOST_USER
 ```

## Run migrations
```
python manage.py migrate
```

## Start server
```
python manage.py runserver
```

### Open 
```
http://127.0.0.1:8000/
```

### Future Improvements
AI-powered spending predictions
Monthly budget goals
Export reports (PDF/Excel)
REST API integration
Mobile app version

### Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

### MIT License

Copyright (c) 2026 Lucy Wangoi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



