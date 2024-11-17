# Meta-Clone  

Meta-Clone is a full-stack web application replicating core functionalities of the social media platform **Meta** (formerly Facebook). This project is built using the MERN stack:  

- **M**ongoDB: NoSQL database for storing user data, posts, comments, and more.  
- **E**xpress.js: Backend framework for routing and handling API requests.  
- **R**eact.js: Frontend library for building dynamic and responsive user interfaces.  
- **N**ode.js: JavaScript runtime for running server-side code.  

This project aims to provide a practical demonstration of full-stack development while showcasing the integration of modern web technologies.  

## Features  

- **User Authentication**: Sign-up, login, and logout functionalities with secure password handling.  
- **User Profiles**: Each user has a customizable profile.  
- **Post Creation & Interaction**: Add new posts with images and text. Like and comment on posts.  
- **Real-Time Updates**: Posts, likes, and comments dynamically update without page reloads.  
- **Responsive Design**: Mobile-friendly layout for seamless usage on various devices.  
- **Backend API**: RESTful API for handling data operations.  
- **Scalable Architecture**: Designed to add more features with ease.  

## Tech Stack  

### Frontend  
- **React.js**: For building the user interface.  
- **CSS**: For styling the application.  
- **Redux (Optional)**: For state management, if implemented.  

### Backend  
- **Node.js**: JavaScript runtime environment.  
- **Express.js**: Web framework for creating APIs.  
- **MongoDB**: Database for data persistence.  
- **Mongoose**: ODM for MongoDB, simplifying database operations.  

### Other Tools  
- **JWT**: For secure user authentication.  
- **Cloudinary** (Optional): For managing and storing images.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TirthRadadiya/Meta-Clone.git
   cd Meta-Clone
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Set up the environment variables:
   - Create a `.env` file in the `backend` folder.
   - Add the following variables:
     ```env
     PORT=5000
     MONGO_URI=your_mongo_connection_string
     JWT_SECRET=your_jwt_secret_key
     CLOUDINARY_NAME=your_cloudinary_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm start

   # Start frontend server
   cd ../frontend
   npm start
   ```

5. Open the application in your browser:
   ```
   http://localhost:3000
   ```

## Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository:
   ```bash
   git fork https://github.com/TirthRadadiya/Meta-Clone.git
   ```
2. Clone your fork:
   ```bash
   git clone https://github.com/<your-username>/Meta-Clone.git
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
4. Make your changes and commit:
   ```bash
   git commit -m "Add feature-name"
   ```
5. Push to your fork and create a pull request:
   ```bash
   git push origin feature-name
   ```
