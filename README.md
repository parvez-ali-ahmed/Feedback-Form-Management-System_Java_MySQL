Overview
This Java-based Event Feedback Management System provides a comprehensive solution for collecting and managing feedback from event participants. The system features separate interfaces for administrators and participants with appropriate functionality for each role.

Features
Admin Features
View all feedback submissions

Add/remove admin accounts

Secure login system

Dashboard for feedback analysis

Participant Features
Submit feedback with ratings

Provide detailed reviews

Indicate future participation

Simple user-friendly interface

Technologies Used
Frontend: Java Swing (GUI)

Backend: Java 1.8

Database: MySQL

Database Connector: JDBC (mysql-connector-java-5.1.47)

Build Tool: Eclipse IDE

Version Control: Git/GitHub

System Architecture
The application follows a layered architecture:

Presentation Layer: Swing-based GUI forms

Business Logic Layer: Java classes handling application logic

Data Access Layer: JDBC for database operations

Database Schema
The MySQL database includes tables for:

Feedback submissions (stu table)

Admin accounts (facult table)

Event details

Key Components
Feedback Collection: Ratings for ambiance, service, and overall experience

Participant Information: Name, contact details, and attendance preferences

Admin Dashboard: Comprehensive view of all feedback

Installation Instructions
Prerequisites
Java JDK 8 or later

MySQL Server

MySQL Connector/J
