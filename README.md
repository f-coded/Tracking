
# Tracking App

## Description
A simple tracking app to query shipment details by tracking ID.

## Features
- Backend: Express.js with MongoDB.
- Frontend: Vanilla HTML, CSS, and JavaScript.

## Prerequisites
- Node.js
- MongoDB

## Setup Instructions

1. **Clone the Repository**:
    - Download and extract the project files.

2. **Start MongoDB**:
    - Run `mongod` to start the MongoDB service.

3. **Seed the Database**:
    - Open a terminal and run the following:
      ```
      mongo < seed_data.js
      ```

4. **Run Backend Server**:
    - Navigate to the `backend` directory.
    - Install dependencies:
      ```
      npm install express cors mongodb
      ```
    - Start the server:
      ```
      node server.js
      ```

5. **Open Frontend**:
    - Open `frontend/index.html` in your browser.

6. **Test the App**:
    - Use tracking ID `NG131024386R` to test.

## Notes
- Ensure MongoDB is running during the process.
