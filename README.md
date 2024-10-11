A full-featured blog application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). 
This app allows users to create, read, update, and delete blog posts,


https://github.com/user-attachments/assets/45f73cce-3c1e-473d-a1c5-05f8bdfb22d7

and provides a user-friendly interface for both viewing and managing content.

Table of Contents

Features
Technologies Used
Installation
Usage
API Endpoints
Folder Structure
Contributing
License
Contact
Features
User authentication (sign up, login, logout)
CRUD operations for blog posts
Comments section for each blog post
Responsive design for various screen sizes
User profile management
Markdown support for blog content
Pagination for blog posts
Search functionality
Technologies Used
Frontend:

React
Redux (for state management)
Axios (for API requests)
React Router (for navigation)
Bootstrap (for styling)
Backend:

Node.js
Express.js
MongoDB (with Mongoose for database management)
JWT (for authentication)
Installation
To set up the project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/blog-app.git
cd blog-app
Install the backend dependencies:

bash
Copy code
cd backend
npm install
Set up the environment variables. Create a .env file in the backend directory and add your MongoDB URI:

env
Copy code
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the backend server:

bash
Copy code
npm start
Open a new terminal window and navigate to the frontend directory:

bash
Copy code
cd frontend
npm install
Start the frontend application:

bash
Copy code
npm start
Visit http://localhost:3000 to see the app in action!

Usage
Sign Up / Login: Users can create an account or log in to access the full features of the app.
Create a Post: Logged-in users can create a new blog post using the provided form.
View Posts: All users can view published blog posts.
Edit/Delete Posts: Authors can edit or delete their own posts.
Commenting: Users can leave comments on blog posts.
API Endpoints
Method	Endpoint	Description
POST	/api/auth/signup	Register a new user
POST	/api/auth/login	Log in an existing user
GET	/api/posts	Get all blog posts
POST	/api/posts	Create a new blog post
GET	/api/posts/:id	Get a specific blog post
PUT	/api/posts/:id	Update a specific blog post
DELETE	/api/posts/:id	Delete a specific blog post
POST	/api/posts/:id/comments	Add a comment to a blog post
Folder Structure
arduino
Copy code
blog-app/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   ├── redux/
    │   └── App.js
    └── public/
Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions or feedback, feel free to reach out:

Your Name: siddharthpandey799@gmail.com
GitHub: MRProgHammer
