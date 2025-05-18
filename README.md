# Job Recruitment Backend

This is the backend for a Job Recruitment application built using **Node.js**, **Express**, and **MongoDB**. It includes authentication, job posting, and application submission features. Postman was used for testing the API endpoints.

## 🚀 Features

- User authentication (JWT-based)
- Role-based access (admin, employer, applicant)
- Create, update, delete job listings
- Apply for jobs
- MongoDB as the database
- Environment variable support via `.env`

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- Postman (for API testing)
- dotenv
- nodemon (for development)

## 📁 Project Structure

job-recruitment-backend/
├── config/ # Database config
├── controllers/ # Route controllers
├── middlewares/ # Custom middleware (auth, error handling)
├── models/ # Mongoose models
├── routes/ # API routes
├── .env # Environment variables
├── app.js # Express app setup
├── server.js # App entry point
└── package.json


## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/job-recruitment-backend.git
   cd job-recruitment-backend

2. Install dependencies:
   npm install


3. Create a .env file in the root and add:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret


4. Start the development server:

npm run dev


5. Or to run in production:

npm start


📬 API Testing
Use Postman to test the endpoints. You can import the Postman collection provided in the project or manually test:

POST /api/auth/register - Register user

POST /api/auth/login - Login

POST /api/jobs - Create job (auth required)

GET /api/jobs - List jobs

POST /api/applications - Apply for a job

🧪 Environment
Make sure MongoDB is running and accessible. This app uses Mongoose to interact with MongoDB.

📄 License
This project is licensed under the MIT License.

