# Expense Book

A web application using React.js that allows users to input transactions by category (e.g., food, transport, entertainment) and view financial data by day, month, or year.  

## Features
- **Transaction Input**: Users can log their transactions, categorizing them as food, transport, entertainment, etc.
- **Data Visualization**: View financial data by day, month, or year to track spending patterns.
- **Mock API**: Utilizes **Json-Server** to simulate an API for managing transactions.
- **State Management**: Uses **Redux** for centralized state management.
- **Responsive Design**: Mobile-first design using **Ant Design Mobile (antd-mobile)** components.
- **Date Handling**: Utilizes **Day.js** for easy manipulation and formatting of dates.
- **Routing**: Navigation between different views using **React Router DOM**.

## Tech Stack

- **React**: JavaScript library for building user interfaces.
- **Redux**: State management for predictable and centralized data flow.
- **Axios**: HTTP client for making API requests.
- **Day.js**: Lightweight library for date manipulation.
- **Ant Design Mobile (antd-mobile)**: UI component library optimized for mobile interfaces.
- **React Router DOM**: For routing and navigation between views.
- **Json-Server**: Mock API for simulating backend data and CRUD operations.

## Project Setup  

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/expense-book.git
   cd expense-book
2. Install dependencies: Using npm:  
   ```bash
   npm install  
3. Start the mock API using json-server:
   ```bash
   npm run dev
4. Start the development server: To run the app locally, use:
   ```bash
   npm start
