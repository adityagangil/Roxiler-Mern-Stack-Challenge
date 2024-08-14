# Dashboard Project

## Overview

This project consists of a client and server application that work together to display transaction data and statistics. The client is built with React and Ant Design, while the server is built with Node.js and Express, connected to a MongoDB database.

---

## Client

The client application is a React-based dashboard that displays transaction statistics and details. It includes the following components:

- **Stats**: Displays statistical information and charts for a selected month.
- **Transactions**: Lists transactions with options for searching and pagination.
- **App**: The main application component that includes navigation and month selection.

### Technologies

- React
- Ant Design
- Chart.js
- Axios
- React Router DOM

### Features

- **Statistics**: Shows total sales, sold items, and unsold items with bar and pie charts.
- **Transactions Table**: Displays transaction details with search and pagination functionality.
- **Month Selector**: Allows users to select different months to view data.

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo.git

2. **Navigate to the client directory**

   ```bash
   cd client

3. **Install dependencies**

   ```bash
   npm install

4. **Start the client**

   ```bash
   npm start


##  Server

The server application provides APIs to fetch transaction data and statistics. It connects to a MongoDB database and includes the following features:


###  API Endpoints:

- **/transactions**: Retrieves transaction data with pagination and search.
- **/statistics**: Provides monthly statistics.
- **/bar-chart**: Returns data for bar charts.
- **/pie-chart**: Returns data for pie charts.
- **/combined-data**: Fetches combined data for statistics, bar chart, and pie chart.


### Technologies

- Node.js
- Express
- MongoDB
- Mongoose
- Axios
- dotenv

1. **Navigate to the Server directory**

  ```bash
  cd server

2. **Install dependencies**

  ```bash
  npm install

3. **Set up environment variables**:

Create a `.env` file in the `server` directory with the following content:

   ```bash
   MONGO_URI=your-mongodb-uri
   DATA_URL=your-data-url (if needed)
   PORT=8080


4. **Start the server**

  ```bash
  npm start
