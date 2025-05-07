# URL Shortener Microservice

This project is a simple URL shortener microservice built using **Express** and **Node.js**. It allows users to input a URL, which will then be shortened, and users can access the original URL by visiting the shortened version.

---

## 🚀 Features

- **Shorten URLs:** Users can submit URLs via a POST request, and the server will generate a short URL.
- **Redirect to Original URL:** Users can access the original URL by visiting the short URL.
- **In-memory Storage:** The URLs are stored in memory (i.e., within the server) and can be retrieved using the short URL.

---

## 📦 Requirements

- Node.js
- Express
- dotenv
- CORS

---

## 📂 Folder Structure

```txt
your-project/
├── routes/
│   └── index.js       # Contains the route handlers for POST and GET requests
├── public/
│   └── style.css      # Styling for the frontend HTML page
├── .env               # Environment configuration (e.g., server port)
├── app.js             # Main server file that initializes the Express app
└── README.md          # Project documentation
