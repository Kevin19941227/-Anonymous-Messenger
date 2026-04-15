# 無名信使 Anonymous Messenger

A PHP + MySQL web project focused on anonymous emotional sharing and interaction.

## Introduction
**無名信使** 是一個以匿名信件交流為核心的網站專案。  
使用者可以在平台上分享自己的心情、接收陌生人的故事、進行回覆互動，並瀏覽心理協助資源。  
本專案希望提供一個較安全、柔和、低壓力的文字交流空間，讓人們能夠說出平常不容易表達的感受。

## Project Features
- User registration and login system
- Anonymous story posting
- Random story receiving mechanism
- Reply interaction system
- Like / feedback mechanism
- Psychological resource page
- Story status management with MySQL database

## Tech Stack
- PHP
- MySQL
- HTML
- CSS
- JavaScript
- XAMPP / phpMyAdmin

## Database Structure
Main tables used in this project:
- `users`
- `stories`
- `replies`
- `likes`

## Project Goal
This project was created for a database/web system course.  
The main concept is to build an anonymous message-sharing platform where users can express emotions, read stories from strangers, and interact through text in a more comfortable way.

## My Contribution
You can adjust this section based on your actual work:

- Participated in website development and system integration
- Assisted with database-related functionality
- Implemented or helped organize user interaction flow
- Worked on front-end / back-end page integration
- Supported testing and feature adjustment

## Pages / Core Modules
- Home page
- Login / Register
- Send message page
- Receive message page
- Story / warm story section
- Psychological resources page
- About page

## How to Run
1. Install **XAMPP**
2. Put the project folder into `htdocs`
3. Start **Apache** and **MySQL**
4. Import the SQL file into phpMyAdmin
5. Update database connection settings in `db_connect.php`
6. Open the project in your browser

## Notes
This project is intended for educational and portfolio use.  
If deployed publicly, additional security improvements should be added, such as:
- password hashing
- input validation
- SQL injection protection
- session security enhancement

## License
This project is for learning and portfolio demonstration purposes.
