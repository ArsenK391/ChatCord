# ChatCord - Realtime Chat Application

ChatCord is a real-time chat application built with **Node.js**, **Express**, and **Socket.io**. It allows multiple users to join chat rooms and communicate instantly, with data persistence powered by **MongoDB**.

## Features

  * **Real-time Messaging:** Instant communication using WebSockets.
  * **Concurrent Users:** Support for multiple users interacting simultaneously.
  * **Responsive Design:** Fully functional on mobile and desktop devices.
  * **Persistent Storage:** Chat history and user data managed via MongoDB.
  * **Dynamic UI:** Interactive front-end built with vanilla HTML, CSS, and JavaScript.

## Tech Stack

  * **Backend:** Node.js, Express
  * **Real-time Engine:** Socket.io
  * **Database:** MongoDB
  * **Frontend:** HTML5, CSS3, JavaScript

-----

## Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/ArsenK391/ChatCord.git
    cd ChatCord
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Environment Setup:**
    Create a `.env` file in the root directory and add your MongoDB connection string:

    ```text
    MONGO_URI=your_mongodb_connection_string
    PORT=3000
    ```

4.  **Run the application:**

    ```bash
    # For production
    npm start

    # For development (if using nodemon)
    npm run dev
    ```

5.  **Open in Browser:**
    Navigate to `http://localhost:3000`

-----

## Project Structure

```text
CHATCORD/
├── public/          # Client-side files
│   ├── css/         # Stylesheets
│   ├── js/          # Frontend logic (main.js)
│   ├── chat.html    # Chat room interface
│   └── index.html   # Login/Entry page
├── utils/           # Helper functions (messages, users)
├── server.js        # Main entry point for the Node server
└── package.json     # Project dependencies
```
