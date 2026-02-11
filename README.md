# 🌍 Wanderlust – Travel Listing Platform

Wanderlust is a full-stack travel accommodation web application designed and developed to allow users to explore, create, and manage unique travel stays — from cozy cabins to luxury resorts.

The platform provides secure authentication, dynamic listing management, interactive maps, image uploads, and review systems — all built using modern full-stack technologies.

---

## 🚀 Key Features

- 🔐 **User Authentication & Authorization**
  Secure signup, login, logout using Passport.js and session-based authentication.

- 🏠 **Dynamic Listing Management**
  Create, edit, and delete travel listings with images, categories, pricing, and geolocation.

- 🗺️ **Interactive Map Integration**
  Location-based listings displayed using Mapbox with geocoding support.

- ☁️ **Cloud Image Uploads**
  Images stored and optimized via Cloudinary.

- ⭐ **Review & Rating System**
  Authenticated users can post and manage reviews.

- 🛡️ **Robust Validation & Error Handling**
  Joi validation and centralized custom error handling.

- 📱 **Fully Responsive UI**
  Optimized for desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

### Backend

- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose

### Frontend

- EJS
- HTML5
- CSS3
- JavaScript

### Authentication

- Passport.js
- express-session
- connect-mongo

### File & Media Handling

- Multer
- Cloudinary

### Maps & Geolocation

- Mapbox API

---

## 📂 Project Structure

```
WanderlustProject/
│
├── app.js
├── middleware.js
├── cloudConfig.js
├── schema.js
├── package.json
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
└── init/
```

The project follows an MVC architecture to maintain clean code structure and scalability.

---

## ⚙️ Installation & Setup

1️⃣ Clone the repository:

```bash
git clone https://github.com/Vinay-Yadav-07/WanderlustProject.git
cd WanderlustProject
```

2️⃣ Install dependencies:

```bash
npm install
```

3️⃣ Create a `.env` file in the root directory:

```env
DB_URL=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_secret
MAPBOX_TOKEN=your_mapbox_token
SECRET=your_session_secret
```

4️⃣ Start the server:

```bash
node app.js
```

Open in browser:

```
http://localhost:3000
```

---

## 📡 Core Routes Overview

| Method | Route         | Description         |
| ------ | ------------- | ------------------- |
| GET    | /listings     | Get all listings    |
| POST   | /listings     | Create new listing  |
| GET    | /listings/:id | View single listing |
| PUT    | /listings/:id | Update listing      |
| DELETE | /listings/:id | Delete listing      |
| POST   | /signup       | Register user       |
| POST   | /login        | Login user          |

---

## 🧩 Architecture Highlights

- MVC-based structured design
- RESTful routing
- Middleware-based authorization
- Modular route separation
- Environment-based configuration

---

## ☁️ Deployment

The project can be deployed on:

- Render
- Railway
- Vercel (frontend)
- Heroku (if available)

Database: MongoDB Atlas
Media Storage: Cloudinary

---

## 📌 Future Improvements

- Payment integration
- Advanced search filters
- Wishlist feature
- Booking system
- Admin dashboard

---

## 👨‍💻 Developer

**Vinay Yadav**
Full Stack Developer
Built with a focus on scalability, maintainability, and clean architecture.
