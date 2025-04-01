Full-Stack-Authentication-System-using-React-and-Node.js
Setting up a full-stack authentication system, including a backend (Node.js/Express) and a frontend (React).

How to Run the Application
Backend
Navigate to the backend directory: cd backend

Install dependencies: npm install

Start the server: npm run dev (for development with auto-reload) or npm start (for production)

The server will run on http://localhost:5000.

Frontend
Navigate to the frontend directory: cd frontend

Install dependencies: npm install

Start the development server: npm run dev.

The application will be available at http://localhost:3000.

API Endpoints
POST /api/register - Register a new user
POST /api/login - Authenticate a user
GET /api/profile - Get user profile (requires API key)
PATCH /api/profile - Update user profile (requires API key)
API Key
All protected routes require the API key: EXAM2024-KEY-5678. Add it to request headers as X-API-Key.

Project Structure
backend/

server.js - Main server file
users.json - User database file
package.json - Backend dependencies
frontend/

src/
components/
AuthForm.jsx - Registration/Login component
Profile.jsx - User profile component
App.jsx - Main application component
App.css - Application styles
index.html - HTML entry point
vite.config.js - Vite configuration
exam_collection.json - Postman collection for API testing
