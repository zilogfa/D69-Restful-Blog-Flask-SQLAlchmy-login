# Object-Oriented Blogging System

Create, share, and engage with content in an interactive blogging platform that empowers users to write and comment on posts.

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Security](#security)
- [Credits](#credits)

## Introduction

Our blogging platform is a full-stack web application designed to offer a seamless blogging experience. It provides users with the ability to create, edit, and publish blog posts as well as comment on existing ones. The application upholds RESTful principles and responsive design, ensuring a smooth user experience across different devices.

## Technologies

- Python 3.8+
- Flask Web Framework
- Flask extensions: Flask-Bootstrap, Flask-CKEditor, Flask-Login, Flask-Gravatar
- SQLalchemy with SQLite (or PostgreSQL)
- HTML5, CSS3, Bootstrap
- JavaScript, jQuery

## Features

- User authentication system with admin (ID 1) and regular user roles.
- Users can create, edit, and delete blog posts.
- Commenting feature allows users to engage with content.
- Responsive design for a consistent experience across various devices and screen sizes.
- Admin-only route access ensures that only the admin can manipulate posts at a higher level.

## Setup

1. Ensure you have Python installed on your machine. If not, download it from [python.org](https://www.python.org/downloads/).
2. Install the required Python packages:

```
pip install Flask Flask-Bootstrap Flask-CKEditor Flask-Login Flask-Gravatar Flask-SQLAlchemy
```

3. Set up environment variables for `SECRET_KEY` and `DATABASE_URL`, or they will default to pre-set values in development.

## Usage

1. To start the application, run `python main.py`.
2. Access the application through `localhost:5000` in your web browser.
3. Register a new user account or use the admin account (ID 1) to access admin privileges.
4. Interact with the blogging system by creating, editing, or commenting on posts.

## Security

This application includes basic security features such as hashed passwords and login management. Remember to use environment variables to keep your `SECRET_KEY` and database credentials secure.

## Credits

Developed by Ali Jafarbeglou, this platform is a testament to the capabilities of modern web development with Flask and related technologies.

For any inquiries or issues, please contact the developer.


```
Remember, before running the application, ensure that all dependencies are properly installed and the database is correctly set up and migrated. Since the code provided suggests the use of an SQLite database by default, it would require the initialization and migration using Flask-Migrate if changes are made to the database models. If you are using PostgreSQL or another database, ensure that the connection string (DATABASE_URL) is properly configured.
```
