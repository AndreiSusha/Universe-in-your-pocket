# Universe in your pocket

Welcome to the "Universe in your pocket" project! This website provides users with information about space, astronomy, and space missions. Various sections are available to explore space and delve into its mysterious depths.

It's a full-stack application: a React frontend backed by a Node.js / Express REST API with MongoDB, featuring user registration, a community blog, and an admin panel.

## About the Project

The project includes the following main components:

### Home Page
A brief description of the project, plus the latest news from the world of astronomy.

### Articles and News
Read interesting articles and the latest news about space, astronomy, and space missions.

### Space Blog
A blog section where registered users can share their thoughts, articles, and photos about space.

### Registration and Authorization
Create an account to publish your own materials for other participants. Authentication is handled with JWT.

### Administrator Panel
A control panel allowing administrators to add, edit, and delete articles, and to update information about space events and missions.

## Tech stack

- **React** — JavaScript library for building the user interface
- **Node.js / Express** — web framework handling HTTP requests and routing
- **MongoDB / Mongoose** — NoSQL database and object modeling for data storage and validation
- **JWT** — authentication and authorization
- **bcrypt** — password hashing
- **Multer** — handling image/file uploads
- **HTML / CSS**

## Project structure

```
.
├── server/                   # Node.js / Express REST API + MongoDB models
└── universe-in-your-pocket/  # React frontend
```

## Getting started

Prerequisites: **Node.js**, **npm**, and a **MongoDB** connection string.

### Backend

```bash
cd server
npm install

# Create a .env file based on the variables below, then:
npm run dev        # runs on http://localhost:3000
```

Environment variables (`server/.env`):

```
PORT=3000
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_NAME=blog
CLUSTER=your_cluster
```

### Frontend

```bash
cd universe-in-your-pocket
npm install
npm start          # runs on http://localhost:3001
```

## Accessibility

The project includes several accessibility enhancements: a high-contrast mode for improved visibility, and keyboard navigation for users who rely on alternative input methods.

## Contributors

- [Evgeny Gumenyuk](https://github.com/armelant)
- [Andrei Susha](https://github.com/AndreiSusha)
- [Beresnev Timofei](https://github.com/Timo-joinllur)
