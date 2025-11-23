# WanderLust-An Airbnb-Inspired Accommodation Booking Platform.
WanderLust is a full-stack hotel & stay booking web application inspired by Airbnb. It allows users to explore listings, view details, upload properties, write reviews, manage accounts, and much more — built using Node.js, Express, MongoDB, and EJS.

## Features
- User Authentication
- Property Listings
- Reviews & Ratings
- Fully Responsive UI
- Session Management

## Tech Stack
- Frontend (EJS Templating, Bootstrap 5, CSS, JavaScript)
- Backend (Node.js, Express.js)
- Database (MongoDB, Mongoose ORM, MongoDB Atlas)
- Authentication (Passport.js, passport-local-mongoose)
- Image Storage (Cloudinary, Multer)
- Other Libraries (Method-override, dotenv, connect-mongo,express-session, ejs-mate, joi)
  
## Requirements
- Node.js
- MongoDB Atlas account (or local MongoDB)
- Cloudinary account (for image uploads)

## Environment Variables
Create a .env file in the root folder with:
```bash
ATLASDB_URL=your_mongodb_atlas_url
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_secret
SECRET=your_session_secret
```
## Installation
```bash
git clone https://github.com/tarung-15/WanderLust-An-airbnb-clone.git
cd WanderLust-An-airbnb-clone
npm install
nodemon app.js
```
### Open http://localhost:8080/listings in your browser.

## Author
Tarun G
Developer of WanderLust – a full-stack Airbnb-inspired accommodation booking platform.
GitHub: https://github.com/tarung-15
