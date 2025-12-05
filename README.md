# Subscription Management System

A PHP/MySQL application that lets users manage subscriptions, pay, and renew plans.  
The system demonstrates secure backend processing, database joins, and renewals.

## Features
- View available subscription plans  
- Start new subscriptions with payment records  
- View all subscriptions with JOINed plan and payment data  
- Renew subscriptions with transactions that update payment and dates  
- Responsive interface using Bootstrap

## Tech Stack
Built with PHP, MySQL, HTML5, CSS, and Bootstrap.

## Setup Instructions
1. Copy the project into `C:\xampp\htdocs\subscription-app`
2. Import the SQL file into a MySQL database named `subscriptions`
3. Update credentials in `app/config/db.php`
4. Run locally at `http://localhost/subscription-app/public/`

## Folder Structure
subscription-app/
├─ app/config/db.php
├─ public/index.php
├─ public/start.php
├─ public/subs.php
├─ public/renew.php
└─ sql/schema.sql

Kevin Ilagorre CIS 344 Professor Peralta Ramos
