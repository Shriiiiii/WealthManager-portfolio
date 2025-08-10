Portfolio Analytics Dashboard
A full-stack web application that provides a comprehensive, interactive view of a user's investment portfolio, built as part of the Full-Stack Developer Intern Assignment for WealthManager.online.

Live Demo: [https://portfolio-frontend-shriiiiii.vercel.app/](https://portfolio-frontend-chi-woad.vercel.app/)
<img width="1918" height="1031" alt="Screenshot 2025-08-10 100153" src="https://github.com/user-attachments/assets/961e370f-fb28-4c37-a979-34fad42cc1c0" />
<img width="1915" height="1031" alt="Screenshot 2025-08-10 100210" src="https://github.com/user-attachments/assets/d8791fa0-7066-4cd9-8fff-789e96a8af55" />
<img width="1913" height="1026" alt="Screenshot 2025-08-10 100221" src="https://github.com/user-attachments/assets/4f74c745-372a-4f54-ace1-29d076a90297" />
<img width="1914" height="1034" alt="Screenshot 2025-08-10 100229" src="https://github.com/user-attachments/assets/4d3d8d2d-a109-43d2-bd20-8199d68b7948" />

Features
This application meets all the requirements outlined in the assignment, providing a rich and interactive user experience.

✅ Portfolio Overview
Four Key Metric Cards: Prominently displays Total Portfolio Value, Total Gain/Loss, Portfolio Performance %, and the total Number of Holdings.

Color-Coded Performance: Gain/Loss and Return % are dynamically colored green for gains and red for losses.

✅ Asset Allocation
Three Interactive Pie Charts: Visual breakdown of assets by Sector, Market Cap, and Asset Class.

Detailed Tooltips: Hovering over chart segments reveals precise values and percentages.

✅ Holdings Table
Dynamic Data Grid: A detailed table of all individual stock holdings.

Interactive Sorting: All columns can be sorted in ascending or descending order.

Live Search/Filter: A search bar allows users to instantly filter stocks by name or symbol.

Performance Coloring: Gain/Loss values are color-coded for quick visual assessment.

✅ Performance Analysis
Historical Line Chart: Compares the portfolio's performance over time against key benchmarks (Nifty 50, Gold).

Trailing Returns Table: A clear, concise table showing 1-month, 3-month, and 1-year returns for the portfolio and benchmarks.

✅ Key Insights
Top & Worst Performers: Highlights the best and worst-performing stocks in the portfolio.

Portfolio Metrics: Displays a Diversification Score and a calculated Risk Level.

✅ General UX/UI
Fully Responsive: The entire interface is mobile-friendly and adapts to all screen sizes.

Loading & Error States: The application displays a loading spinner while fetching data and shows a user-friendly error message if the backend API fails.

Technology Stack
This project is a full-stack application with a clear separation between the frontend and backend.

Frontend:
React.js: A JavaScript library for building user interfaces.

Material-UI (MUI): A comprehensive component library for a clean and modern design.

Chart.js (with react-chartjs-2): For creating interactive and beautiful charts.

Deployment: Hosted on Vercel.

Backend:
Node.js: A JavaScript runtime for building the server.

Express.js: A minimal and flexible Node.js web application framework.

CORS: Middleware to enable cross-origin requests from the frontend.

Deployment: Hosted on Render.

Local Setup and Installation
To run this project on your local machine, you will need to run the frontend and backend servers in separate terminals.

1. Backend Setup:
# Navigate to the backend directory
cd portfolio-backend

# Install the required dependencies
npm install

# Start the server (runs on http://localhost:5000)
node server.js

2. Frontend Setup:
# Navigate to the frontend directory in a new terminal
cd portfolio-frontend

# Install the required dependencies
npm install

# Start the React development server (runs on http://localhost:3000)
npm start

Your browser should automatically open to the dashboard.

API Endpoints
The backend provides four RESTful API endpoints to serve the portfolio data.

Method

Endpoint

Description

GET

/api/portfolio/summary

Returns key metrics and insights.

GET

/api/portfolio/holdings

Returns a complete list of all stock investments.

GET

/api/portfolio/allocation

Returns asset distribution by sector, market cap, etc.

GET

/api/portfolio/performance

Returns historical performance and trailing returns.

The backend performs all data calculations (gains, losses, percentages) on the fly and includes robust data validation and error handling.

AI Usage in Development
As encouraged by the assignment, AI tools were utilized to accelerate development and solve specific challenges.

Tool Used: Google's Gemini

How it was used:

Boilerplate Code Generation: Generated initial setup code for React components and the Express server.

Debugging Assistance: Helped identify and resolve errors, such as the Cannot GET / error and CORS issues, by explaining the root cause and providing corrected code snippets.

Code Refactoring & Documentation: Assisted in refactoring the backend to perform on-the-fly calculations and automatically generated detailed, human-readable comments for all files.

Best Practices: Provided guidance on professional practices like creating a comprehensive README, deploying to services like Vercel and Render, and setting up environment variables.

Code Origin: Approximately 40% of the boilerplate and initial component structure was AI-generated, while the remaining 60%, including the application logic, state management, and final styling, was hand-written and customized. AI served as a powerful assistant and quality checker throughout the process.
