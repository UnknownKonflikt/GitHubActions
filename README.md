Tech-Quiz
This quiz application provides users with a dynamic quiz experience where they can answer a series of questions, view their score, and retry the quiz if desired. The backend API is built with Express and Node.js, connects to a MongoDB database to fetch quiz questions, and serves the data to a React frontend.


Dynamic Question Fetching: Retrieves questions from MongoDB via an Express API.
Score Tracking: Shows users their score upon completing the quiz.
Retry Option: Restart the quiz to try again.
Loading Indicator: Displays a spinner while questions are being fetched.
Comprehensive Testing: Includes Cypress tests for both End-to-End and Component Testing.
Technologies Used
Frontend: React, CSS
Backend: Node.js, Express.js
Database: MongoDB
Testing: Cypress
Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (v14 or above)
MongoDB (local instance or MongoDB Atlas)
npm (Node package manager)
Installation
Clone the Repository:
git clone git@github.com:UnknownKonflikt/GitHubActions.git
Navigate to Project Directory:
bash cd Tech-Quiz

Install Server and Client Dependencies:
npm install
Running the Application
Development Mode
Run Backend and Frontend Together: From the project root, run:

npm run start:dev
This starts both the backend server and the frontend development server. The backend server will run on http://localhost:3001 and the frontend will run on http://localhost:3001 by default.

Usage
Start the Quiz: Click the "Start Quiz" button to begin.
Answer Questions: Select the answer by clicking the respective button.
View Results: Once all questions are answered, view your score and click "Take New Quiz" to retry.
Environment Variables
Create a .env file in the root directory and add the following variables:

MONGO_URI=<Your MongoDB connection string>
MONGO_URI: Connection URI for MongoDB.
Testing with Cypress
This project includes Cypress tests for both End-to-End (E2E) and Component Testing.

Start the Server: Ensure the backend server is running before running tests.

Run Tests with Cypress:

E2E Tests
To run only the E2E tests:

npm run test:e2e
Component Tests
To run only the Component tests:

npm run test:component
Run All Tests Sequentially
To run both E2E and Component tests sequentially, use:

npm run test:all

License
Distributed under the MIT License. See LICENSE for more information.

Contact Information
For any inquiries or collaborations, please reach out to:
email: unknownkonflikt@gmail.com
github: https://github.com/UnknownKonflikt
