#YelpCamp - Camping Site Management System

##Overview
YelpCamp is a full-stack web application that allows users to browse, create, edit, and delete camping site listings. Built with Node.js, Express, MongoDB, and EJS, this project demonstrates CRUD operations, user authentication, and session management.

🚀 Live Demo: YelpCamp on Render
📂 GitHub Repo: YelpCamp Repository

Features
✅ User authentication (Register/Login/Logout)
✅ Add, edit, and delete camping sites
✅ Upload images for each campsite
✅ Reviews and ratings system
✅ Interactive map using Mapbox
✅ Secure routes with authorization

Technologies Used
Frontend: EJS, Bootstrap
Backend: Node.js, Express.js, MongoDB (Mongoose)
Authentication: Passport.js
Storage: Cloudinary (for image uploads)
Mapping: Mapbox API

Clone the Repository
git clone https://github.com/DavidAjest/YelpCamp.git
cd YelpCamp

Install Dependencies
npm install


 Setup Environment Variables
 Create a .env file in the root directory and add the following:
 DATABASE_URL=<Your MongoDB Connection String>
CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
CLOUDINARY_KEY=<Your Cloudinary API Key>
CLOUDINARY_SECRET=<Your Cloudinary Secret>
MAPBOX_TOKEN=<Your Mapbox Token>
SESSION_SECRET=<Your Secret Key>

4. Start the Server
nodemon app.js
