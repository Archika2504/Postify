# Postify

Postify is a simple social media web application built using Node.js, Express.js, MongoDB, and EJS. Users can register, log in, create posts, like posts, and edit their own posts.

---

## Features

- User Registration & Login
- JWT Authentication
- Password Hashing using bcrypt
- Protected Routes
- Create Posts
- Like / Unlike Posts
- Edit Posts
- User Profile Page
- MongoDB Database Integration
- EJS Templating

---

## Tech Stack

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT (JSON Web Token)
- bcrypt

### Frontend
- EJS
- Tailwind CSS

---

## Project Structure

```bash
Postify/
│
├── modules/
│   ├── user.js
│   └── post.js
│
├── views/
│   ├── index.ejs
│   ├── login.ejs
│   ├── profile.ejs
│   └── edit.ejs
│
├── public/
│
├── app.js
├── package.json
├── .gitignore
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/postify.git
```

### Go To Project Folder

```bash
cd postify
```

### Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory.

```env
JWT_KEY=your_secret_key
```

---

## Run Project

```bash
npm start
```

Server will run on:

```bash
http://localhost:3000
```

---

## Routes

| Method | Route | Description |
|---|---|---|
| GET | `/` | Register Page |
| POST | `/register` | Register User |
| GET | `/login` | Login Page |
| POST | `/login` | Login User |
| GET | `/profile` | User Profile |
| POST | `/post` | Create Post |
| GET | `/like/:id` | Like/Unlike Post |
| GET | `/edit/:id` | Edit Post Page |
| POST | `/update/:id` | Update Post |
| GET | `/logout` | Logout User |

---

## Future Improvements

- Delete Posts
- Upload Profile Pictures
- Comments System
- Follow / Unfollow Users
- REST API Version
- React Frontend
- Realtime Notifications
- Dark Mode

---

## Author

Developed by Archika

---

## License

This project is licensed under the MIT License.
