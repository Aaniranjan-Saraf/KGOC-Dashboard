
# KGOC Admin Dashboard

The KGOC Admin Dashboard is a comprehensive web application designed to manage financial insights efficiently. Utilizing modern web technologies and frameworks, it provides a robust solution for revenue and expense management.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Revenue and Expense Overview**
  - Total revenue and expenses display
  - Monthly revenue and expense breakdown

- **Revenue Month by Month**
  - Detailed month-by-month revenue analysis

- **Operational vs Non-Operational Expenses**
  - Separate views for operational and non-operational expenses

- **Campaigns and Targets**
  - Track ongoing campaigns and their targets

- **List of Products**
  - Comprehensive list of products with detailed information

- **Recent Orders**
  - Overview of the most recent orders

- **Overall Summary and Explanation Data**
  - Summarized financial data with explanations

- **Revenue Predictions**
  - Charted revenue and predicted revenue using a simple linear regression model

## Technologies Used

**Backend:**
- Node.js
- Express.js
- MongoDB

**Frontend:**
- React
- JavaScript
- TypeScript
- Recharts

## Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies for backend and frontend:**
   - For backend:
     ```bash
     cd server
     npm install
     ```
   - For frontend:
     ```bash
     cd client
     npm install
     ```

3. **Set up environment variables:**
   - Create a `.env` file in the server directory and add your MongoDB connection string and other necessary configurations:
     ```plaintext
     MONGO_URI=your_mongodb_uri
     PORT=5000
     ```

4. **Run the backend server:**
   ```bash
   cd server
   npm run dev
   ```

5. **Run the frontend application:**
   ```bash
   cd client
   npm run dev
   ```

6. **Access the application:**
   - Once the setup is complete, you can access the dashboard at [http://localhost:5173](http://localhost:5173).

## Usage

After running the application, you can log in with the admin credentials. The dashboard will display various financial insights and allow you to navigate through the features outlined above. 

### Example Usage Scenarios
- **Analyze Monthly Revenue**: Check the monthly revenue breakdown to assess trends.
- **Manage Campaigns**: Monitor the effectiveness of campaigns against set targets.
- **Generate Revenue Predictions**: Utilize the predictive analytics feature to forecast future revenues.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Create a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Kangaroo®** for their collaboration in developing this dashboard.
- **IIT Ropar** for providing an enriching environment for project development.
- Special thanks to the open-source community for the various libraries and tools utilized in this project.
- Special thanks to **Ankit**, **Priyanka**, and **Avik** for their unwavering support throughout this project!