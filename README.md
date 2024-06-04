Features
User authentication (Sign In/ Sign Up)
Movie search using OMDB API
Create and manage movie lists
Lists can be public or private
Tech Stack
Frontend: React.js
Backend: Node.js with Express.js
Database: MongoDB
Authentication: JWT
Installation
Clone the repository:

git clone [https://github.com/dananya1/movie_library](https://github.com/AVDHANUSH/movie)
cd movie-library
Install backend dependencies:

cd backend
npm install
Create a .env file in the backend directory and add your MongoDB URI and JWT secret:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the backend server:

npm run dev
Install frontend dependencies:

cd ../frontend
npm install
Start the frontend server:

npm start
Access the application at http://localhost:3000.

Usage
Sign up or sign in to the application.
Search for movies using the search bar.
Create lists of movies, and set them as public or private.
View your movie lists on the home page.
