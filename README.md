# Online Examination System

A PHP and MySQL based web application for conducting online multiple-choice examinations.

The project provides separate user and administrator workflows for registration, authentication, quiz participation, scoring, results, rankings, feedback, and quiz management.

## Features

### User
- User registration and login
- Browse available quizzes
- Attempt multiple-choice examinations
- Automatic score calculation
- Quiz result display
- Attempt history
- Ranking / leaderboard
- Feedback submission

### Administrator
- Administrator login
- View registered users
- View rankings
- View feedback
- Add quizzes
- Add questions and answer options
- Remove quizzes

## Tech Stack

- **Backend:** PHP
- **Database:** MySQL / MariaDB
- **Frontend:** HTML, CSS, JavaScript
- **UI:** Bootstrap
- **JavaScript libraries:** jQuery, Modernizr
- **Web Server:** Apache (for example, through XAMPP)

## Project Structure

```text
online-examination-system/
├── account.php
├── admin.php
├── dash.php
├── dbConnection.php
├── feed.php
├── feedback.php
├── index.php
├── login.php
├── logout.php
├── project.sql
├── sign.php
├── update.php
├── css/
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.min.css
│   ├── font.css
│   └── main.css
├── fonts/
│   ├── glyphicons-halflings-regular.eot
│   ├── glyphicons-halflings-regular.ttf
│   ├── glyphicons-halflings-regular.woff
│   ├── glyphicons-halflings-regular.woff2
│   ├── gothic.ttf
│   └── typo.ttf
├── image/
│   ├── CAM00121.png
│   ├── bg.jpg
│   ├── bg1.jpg
│   └── cd-icon-menu.svg
└── js/
    ├── bootstrap.js
    ├── bootstrap.min.js
    ├── jquery.js
    ├── main.js
    └── modernizr.js
```

## Database

The project uses MySQL/MariaDB for storing application data.

The supplied SQL database contains tables for:
- Administrators
- Users
- Quizzes
- Questions
- Options
- Answers
- Exam history
- Rankings
- Feedback

## Running Locally

1. Install a local PHP and MySQL environment such as XAMPP.
2. Copy the project folder into the Apache web root (`htdocs`).
3. Start Apache and MySQL.
4. Create a MySQL database named `project`.
5. Import `project.sql`.
6. Check `dbConnection.php` and update the local database configuration if required.
7. Open the project through your local Apache server.

## Notes

- This is an academic/portfolio project.
- The original project was developed as a PHP, MySQL and web-development project.
- The public repository contains sanitized source and sample data.
- Personal information, credentials, and non-public sample data have been removed or replaced.
- The original project report is intentionally excluded from the repository.
- The project is preserved primarily as a portfolio and interview reference and should not be considered production-ready authentication software.
