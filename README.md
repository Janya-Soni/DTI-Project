Silent Struggles – Smart Classroom Feedback & Doubt Resolution Platform
Overview

Silent Struggles is a web-based platform designed to improve classroom interaction between students and teachers. Students can provide feedback on their understanding of topics and submit doubts, while teachers can view analytics and respond accordingly.

The system helps teachers identify topics that students struggle with and resolve doubts more efficiently.

Features
Student Portal

Students can:

Mark their understanding of a topic

Understood

Partially Understood

Not Understood

Submit doubts through a chat system

View previously submitted doubts

Interact with a simple UI

The system also includes abusive word detection in the chat system to maintain a respectful learning environment.

Teacher Dashboard

Teachers can:

View student understanding statistics

Monitor class performance through graphs

Review student doubts

Mark doubts as solved

Clear resolved doubts

The dashboard uses Chart.js to visualize student feedback data.

Project Structure
Silent-Struggles

── login.html

── student.html

── teacher.html

── README.md

login.html – login page where users choose student or teacher role

student.html – student portal for feedback and doubts

teacher.html – teacher dashboard showing analytics and doubts

Technologies Used

HTML

CSS

JavaScript

Chart.js

Browser LocalStorage

How to Run the Project
Method 1 — Run Directly in Browser (Recommended)

Download or clone the repository.

git clone https://github.com/your-username/silent-struggles.git

Open the project folder.

Double-click login.html.

The login page will open in your browser.

Select a role:

Student → opens student portal

Teacher → opens teacher dashboard

System Workflow

User opens login.html

Student logs in and submits:

understanding feedback

doubts

Data is stored using LocalStorage

Teacher dashboard reads this data and displays:

charts

statistics

student doubts

Future Improvements

Database integration

Real-time messaging

AI-based doubt answering

Authentication with institutional email

Cloud deployment

Mobile app version

Project Purpose

This project was created as part of a Design Thinking and Innovation course project to explore ways technology can improve classroom engagement and learning outcomes.
