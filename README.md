Subscription SaaS Invoice & Billing System
MERN Stack Subscription SaaS Invoice & Billing System

Built with the MERN stack (MongoDB, Express, React, NodeJS).


Update

This repository now includes subscription management, recurring billing, PDF invoice generation, and Admin Panel features.
More exciting features are on the way!

Sachin Bodare

Introduction

Key Features

Technologies used

Client

Server

Database

Configuration and Setup

Troubleshooting

Docker

Author

License

Introduction

This is a full stack Subscription SaaS Invoice & Billing System designed for startups, freelancers, and small businesses.

It allows users to:

Subscribe to plans and manage recurring payments

Send and download invoices, receipts, and quotes as PDFs

Monitor billing history and subscription status

Admins can manage users, plans, subscriptions, and system analytics

Key Features

Subscription management with multiple plans

Recurring billing support

Send invoices, receipts, and quotes via email

Generate and download PDF invoices

Track payment history and subscription status

Clean Admin Panel with analytics and statistics

Authentication using JWT and optional Google login

Technologies used
Client

React JS

Redux (state management)

React Router DOM

Axios

TailwindCSS & Material UI

React Toastify / Snackbar for notifications

Server

Node.js & Express

MongoDB with Mongoose

JWT for authentication

bcryptjs for password hashing

Nodemailer for email notifications

html-pdf for generating invoice PDFs

Database

MongoDB (MongoDB Atlas)

Configuration and Setup

Clone the repo:

git clone <repo-url>
cd project-folder


Client setup:

cd client
npm install
cp .env.example .env
# Set API_URL=http://localhost:5000
npm start


Server setup:

cd server
npm install
cp .env.example .env
# Set DB_URL, PORT, JWT_SECRET, SMTP credentials
npm start


Visit http://localhost:3000 to access the app.

Troubleshooting

Ensure MongoDB is running

Verify .env variables are correct

Run npm install html-pdf -g if PDF generation fails

Docker

Add .env files for client and server and run:

docker-compose -f docker-compose.prod.yml build
docker-compose -f docker-compose.prod.yml up

Author

Name: Sachin Shankar Bodare

Website: 

Email: sachinbodare2@gmail.com

LinkedIn: Sachin Bodare

License

This project is MIT
 licensed.