# GetQuiz - MERN Stack Quiz Platform

GetQuiz is a modern quiz platform built using the MERN stack. It features authentication, quiz management, and a user-friendly dashboard. Designed with Vite.js and Tailwind CSS, it provides a sleek dark beige theme, smooth animations, and real-time quiz handling for an engaging experience.

## Features
- **User Authentication** (Sign up, Login, Logout)
- **Quiz Management** (Create, Edit, Delete Quizzes)
- **Question Handling** (Add, Modify, Remove Questions)
- **Real-time Quiz Execution**
- **Dark Beige Themed UI** (Built with Tailwind CSS)
- **Smooth Animations for Better UX**

## Tech Stack
- **Frontend:** React.js (Vite.js, Tailwind CSS, Redux Toolkit)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **API Management:** Redux Toolkit Query

## Installation
### Prerequisites
Make sure you have **Node.js** and **MongoDB** installed on your system.

### Clone the Repository
```sh
git clone https://github.com/yourusername/GetQuiz.git
cd GetQuiz
```

### Backend Setup
```sh
cd server
npm install
npm start
```

### Frontend Setup
```sh
cd client
npm install
npm run dev
```

## Usage
1. Register or log in to access the platform.
2. Create quizzes and add questions.
3. Take quizzes and view results in real-time.

## Folder Structure
```
GetQuiz/
├── client/  # Frontend (React + Vite)
│   ├── src/
│   │   ├── components/  # Reusable UI elements
│   │   ├── pages/  # Full-page views (Auth, Dashboard, Quiz Management)
│   │   ├── api/  # API handling with Redux Toolkit
│   │   ├── reducer/  # Store
│   │   ├── Services/  # backend function to frontend
│   │   ├── styles/  # Tailwind CSS styles
│   ├── public/
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
├── server/  # Backend (Node.js + Express)
│   ├── models/  # Mongoose models
│   ├── routes/  # API routes
│   ├── controllers/  # Business logic
│   ├── middleware/  # Authentication & validation
│   ├── config/  # Database connection
│   ├── server.js  # Main entry point
│   ├── package.json
├── README.md
```

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries, reach out to jaindayanshi123@gmail.com or visit https://github.com/Dayanshi123.
