#  WanderLust

A full-stack Airbnb clone built with the MERN stack — a platform to explore, list, and book unique stays around the world.

> 🚧 **Status:** In active development. This project is currently on Day 1 of build progress.

---

## ✨ Overview

WanderLust replicates the core experience of Airbnb, allowing users to browse property listings, view details, and (eventually) create, edit, and book stays. This project is being built as a learning exercise in full-stack development with MongoDB, Express, React, and Node.js.

---

## 🛠️ Tech Stack

**Backend**
- Node.js
- Express.js
- MongoDB with Mongoose

**Frontend**
- React
- HTML5 / CSS3
- JavaScript (ES6+)

**Tools**
- Nodemon (dev server auto-reload)
- Git & GitHub (version control)

---

## 📋 Features

### Implemented
- [x] Express server setup
- [x] MongoDB connection
- [x] Listing schema/model (title, description, image)
- [x] Sample data seeding

### Planned
- [ ] Full CRUD routes for listings (Create, Read, Update, Delete)
- [ ] EJS/React-based frontend views
- [ ] Image upload support
- [ ] User authentication (Passport.js)
- [ ] Reviews and ratings
- [ ] Search and filtering
- [ ] Booking functionality

---

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- MongoDB installed locally or a MongoDB Atlas connection string

### Installation

```bash
# Clone the repository
git clone https://github.com/Swatipal06/wanderlust.git
cd wanderlust

# Install dependencies
npm install

# Set up environment variables
# Create a .env file in the root directory with:
# MONGO_URI=your_mongodb_connection_string

# Run the development server
nodemon app.js
```

The server will start on `http://localhost:8080` by default.

---

## 📁 Project Structure

```
MajorProject/
├── models/
│   └── listing.js       # Mongoose schema for listings
├── app.js               # Entry point, server + DB connection
├── package.json
└── README.md
```

---

## 🤝 Contributing

This is currently a solo learning project, but suggestions and feedback are welcome! Feel free to open an issue.

---

## 📬 Contact

**Swati Pal**
- GitHub: [@Swatipal06](https://github.com/Swatipal06)
- LinkedIn: [swati-pal06](https://linkedin.com/in/swati-pal06)
- Email: swatipal1512@gmail.com

---

## 📄 License

This project is open source and available for educational purposes.
