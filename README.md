# WanderLust

A secure and scalable vacation rental platform. This project primarily focuses on a robust backend system designed to manage listings, user authentication, and session handling, complemented by a responsive frontend.

## 🚀 Features

-   **Secure RESTful APIs:** Built for managing listings, user authentication, and session handling.
-   **User Authentication & Session Management:** Implemented using Passport.js and a MongoDB-based session store.
-   **Optimized Query Performance:** Achieved through schema optimization, indexing, and aggregation techniques.
-   **Role-Based Access Control (RBAC):** Ensures restricted endpoint access based on user roles.
-   **Automated Deployment:** Deployed on Render with automated CI/CD pipelines and environment configuration.
-   **Responsive Front-End:** Designed for cross-device usability.

## 🛠️ Technologies Used

-   **Backend:** Node.js, Express.js, MongoDB
-   **Authentication:** Passport.js 
-   **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 
-   **Deployment:** Render 
-   **Architecture:** MVC Framework

## 🎯 How to Use

(Note: Since this is primarily a backend project with a responsive frontend, "How to Use" steps will focus on setting up and running the server, and potentially accessing the frontend.)

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/sraj5252/WanderLust.git](https://github.com/sraj5252/WanderLust.git)
    cd WanderLust
    ```
2.  **Install backend dependencies:**
    ```bash
    npm install
    ```
3.  **Set up environment variables:**
    Create a `.env` file in the root directory with your MongoDB connection string, and any other necessary secrets (e.g., for Passport.js).
    Example `.env` content:
    ```
    MONGODB_URI=your_mongodb_connection_string
    SESSION_SECRET=your_secret_key
    ```
4.  **Start the development server:**
    ```bash
    node app.js
    ```
5.  **Access the application:**
    Open your browser and navigate to `http://localhost:3000` (or the port your server runs on) to view the front-end and interact with the backend.

## 📁 Project Structure
```
WanderLust/
├── controllers/          # Logic for handling requests (MVC)
├── models/               # Mongoose schemas for MongoDB (MVC)
├── routes/               # API endpoint definitions (MVC)
├── public/               # Static files for the frontend (HTML, CSS, JS)
│   ├── css/              # Stylesheets
│   ├── js/               # Client-side JavaScript
│   └── images/           # Images used in the frontend
├── views/                # Frontend templates (if using a templating engine like EJS, Pug)
│   ├── layouts/          # Common layout templates
│   └── partials/         # Reusable template partials
├── config/               # Configuration files (e.g., database connection, Passport setup)
├── utils/                # Utility functions (e.g., helpers, error handling)
├── .env                  # Environment variables
├── app.js                # Main application entry point
├── package.json          # Project metadata and dependencies
└── README.md             # This readme file
```

## 🌟 Future Enhancements

-   Advanced search and filtering options for listings.
-   Booking and payment integration.
-   Real-time notifications for bookings or inquiries.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. Please make sure your changes are well tested.

## ⚙️ Tools

-   Git
-   npm (Node Package Manager)
-   VS Code (or your preferred code editor) 
-   Google Colab (if used for any scripts/analysis) 
-   Web Browser (for viewing the app)
