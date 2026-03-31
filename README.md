# Course Material Hub (CourseHub)

##  Project Description

CourseHub is a web-based platform that allows students to upload, search, and download study materials in one place. It provides a centralized system for managing lecture notes and resources.

---

##  Features

* User registration and login authentication
* Secure password storage using bcrypt
* File upload system using Multer
* Search and download lecture files
* My Profile section
* Responsive UI with dark/light mode

---

##  Tech Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Node.js, Express.js
* Database: MongoDB

---

##  Dependencies

### Backend Dependencies

The project uses the following npm packages:

* express
* mongoose
* multer
* bcrypt
* express-session
* connect-mongo

👉 These will be automatically installed using `npm install`.

---

##  Prerequisites

Make sure you have installed:

* Node.js
* MongoDB


---

##  Installation Steps

### 1. Clone the repository

```bash
git clone https://github.com/ItsRayo/CourseHub.git
cd CourseHub
```

### 2. Install backend dependencies

```bash
cd backend
npm install
```

### 3. Start MongoDB

```bash
mongod
```

### 4. Run the server

```bash
node app.js
```

### 5. Open in browser

```
http://localhost:3000
```

---



## 📂 Project Structure

* `backend/` → server code and database models
* `frontend/` → HTML, CSS, JS files

---

## 🔐 Security Note

Sensitive files such as `.env`, `node_modules`, and uploaded files are excluded from this repository.

---


