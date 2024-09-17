# HoldInfo_Clone

### Deployed link : https://hodlinfotop10-a80e02.netlify.app/
### Demo video : https://drive.google.com/file/d/1gOGqSdigDhIJG8G4BZWXtnO1GURHS5RL/view?usp=drive_link

## Project Overview
**Crypto Dashboard**: A web application that displays live data for the top 10 cryptocurrencies from WazirX, updating every 60 seconds.

## Technologies Used
- **Frontend:** Html, Css,Javascript
- **Backend:** Node.js, Express, MongoDB, Mongoose

## Features
- **CRUD Operations:** read
- **Live Cryptocurrency Data:** Displays real-time data for the top 10 cryptocurrencies.
- **Automatic Updates:** Refreshes data every 60 seconds for up-to-date information.
- **Responsive Design:**  Adapts to various screen sizes for a seamless experience on different devices.
- **Error Handling:** Shows appropriate messages for data fetch or processing errors.

## Setup Instructions

### Backend
1. **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd <your-repo-directory>
    ```

2. **Navigate to the routes directory:**
    ```bash
    cd routes
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up environment variables:**
    Create a `.env` file in the backend directory and add the following:
    ```env
    PORT=3000
    MONGODB_URI=<your-mongodb-uri>
    ```

5. **Run the backend server:**
    ```bash
    npm start
    ```

### Frontend
1. **Navigate to the public directory:**
    ```bash
    cd public
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the frontend directory and add the following:
    ```env
    REACT_APP_API_URL=http://localhost:3000
    ```

4. **Run the frontend server:**
    ```bash
    go live withserver HTMl
    ```
---

### Usage

1. **Access the Application:**
    Open your browser and navigate to `http://localhost:3000`.

2. **View Cryptocurrency Data:**
    The dashboard displays real-time data for the top 10 cryptocurrencies.

3. **Refresh Data:**
    Data updates automatically every 60 seconds. 

4. **View Detailed Information:**
    Click on a cryptocurrency to view additional details, such as historical data or specific metrics.

---

## Contributing
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch to your fork.
4. Create a pull request to the main repository.
