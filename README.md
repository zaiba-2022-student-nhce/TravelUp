# TravelUp Project

## Overview
TravelUp is an AI-powered travel website that provides smart recommendations for tourist activities based on user preferences. It also features an AI-based tour guiding system.

---

## Features
- *Smart Recommendations:* AI-driven suggestions for travel activities based on user preferences.
- *AI Tour Guide:* Interactive virtual tour guide using Gemini Flash Calls.
- *Search and Filters:* Users can search for destinations and filter results by city, duration, and ratings.
- *User Authentication:* Secure login and registration.

---

## Technologies Used
- *Backend:* Node.js
- *Database:* MongoDB
- *Frontend:* HTML, CSS
- *AI Integration:* [Gemini Flash Calls API](https://ai.google.dev/)

---

## Project Structure

|-- travelup
    |-- app.js                 # Main server file
    |-- cities.ejs             # EJS template for displaying city information
    |-- public/                # Static files (CSS, JS, Images)
    |-- routes/                # Route handlers for the application
    |-- views/                 # EJS templates
    |-- models/                # MongoDB models
    |-- db_config.js           # Database connection settings
    |-- city.csv               # CSV file with city data
    |-- ...


---

## Setup Instructions
1. *Clone the Repository:*
  
   git clone https://github.com/yourusername/travelup.git
   
2. *Install Dependencies:*
   sh
   cd travelup
   npm install
   
3. *Configure the Database:*
   - Update db_config.js with your MongoDB connection string.
4. *Run the Server:*

   npm start
   
   - Access the application via http://localhost:3000.

---

## Acknowledgements
- OpenAI's ChatGPT for assistance in documentation.
- [Gemini Flash Calls API](https://ai.google.dev/) for AI recommendations.

---
