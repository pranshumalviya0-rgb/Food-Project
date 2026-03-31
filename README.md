# 🍔 Food Reel App 

A full-stack web application that delivers a **short-video (reels-style) food discovery experience**, similar to YouTube Shorts or Instagram Reels — but focused on food content.

Users can scroll through food videos, like/save them, and food partners can upload and manage their content.

---

## 🚀 Features

### 👤 User Features

* User Registration & Login
* Scrollable **Reels Feed**
* Like & Save food videos
* View saved content

### 🍽️ Food Partner Features

* Food Partner Registration & Login
* Upload food videos
* Manage uploaded content
* Profile management

### 🎥 Core Functionality

* Short-video (reel-style) UI
* Smooth scrolling experience
* Media storage integration
* Authentication & authorization

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* React Router
* CSS (custom styling)

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

### Other

* Cloud/Local Storage for videos
* REST API architecture

---

## 📁 Project Structure

```
Youtube-project-food-view-main/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   ├── services/
│   │   └── db/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── routes/
│   │   └── styles/
│   ├── index.html
│   └── package.json
│
└── vdeos/
    └── sample video files
```


## 🎨 Screens / Pages

* Home (Reels Feed)
* Login / Register (User & Food Partner)
* Create Food (Upload)
* Profile Page
* Saved Videos

---

## 📦 Sample Data

The `vdeos/` folder contains sample video files used for testing the reel feed.

---

## 🔐 Authentication

* JWT-based authentication
* Protected routes for food partners
* Middleware for request validation

---

## 🚧 Future Improvements

* Comments on videos
* Follow system
* Video recommendations (AI-based)
* Real-time notifications
* Better UI animations

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

