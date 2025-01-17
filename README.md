# Anois National Zoo Website 🦁 [Link](https://emonsur.pythonanywhere.com/)

Welcome to the official repository for the **Anois National Zoo**! This is a dynamic web application built using Flask, enabling users to explore animal exhibits, leave reviews, make donations, book tickets, and much more.


## 📂 Project Structure

```plaintext
.
├── static/               # Static files such as CSS, images, and JavaScript
├── templates/            # HTML templates used for rendering dynamic content
├── __pycache__/          # Python cache files (auto-generated)
├── app.db                # SQLite database file
├── app.py                # Main Flask application
├── database.py           # Database connection and utility functions
├── forms.py              # Flask-WTF forms for user interaction
├── freeze.py             # Utility script for creating a static version of the site
├── schema.sql            # SQL schema for initializing the database

````

## 🚀 Features

- **User Authentication**:
  - Secure registration and login system.
  - Passwords are hashed for security.
  
- **Reviews**:
  - Users can leave reviews for the zoo with a rating and a date.
  - Recent reviews are dynamically displayed.

- **Animal Exhibit Exploration**:
  - Explore animals categorized by habitats.

- **Donations**:
  - Users can donate and see acknowledgment messages.

- **Ticket Bookings**:
  - Book tickets directly through the website.

- **Admin and Employee Management**:
  - Admins can manage animals, employees, and review content.

## 🛠️ Technology Stack

- **Frontend**:
  - HTML
  - CSS (with a responsive design)

- **Backend**:
  - Python (Flask Framework)
  - SQLite (Database)

- **Libraries**:
  - Flask-WTF (for forms)
  - Werkzeug (for password hashing)
 
## Screenshots

### Homepage
![Homepage](Screenshots/homepage.png)

### Reviews Page
![Reviews Page](Screenshots/reviews.png)

### Animal Info Page
![Animal Info Page](Screenshots/animals.png)

### Login Page
![Login Page](Screenshots/login.png)
