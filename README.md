AI StudyBuddy

AI StudyBuddy is an AI-based learning assistant designed to help students with studying, answering questions, generating summaries, and improving their learning experience.

Features

- AI-powered study assistance
- Question and answer system
- Study material support
- Notes and summary generation
- User-friendly interface
- Backend API using Node.js and Express
- MongoDB database support

Technologies Used

- HTML, CSS, JavaScript
- Node.js
- Express.js
- MongoDB
- Mongoose
- REST API
- AI/ML

Project Structure

AI-StudyBuddy/
│
├── client/
│   └── frontend files
│
├── server/
│   ├── server.js
│   ├── package.json
│   ├── .env
│   └── routes/
│
├── README.md
└── .gitignore

Server Setup

1. Open the server folder

cd server

2. Initialize Node.js

npm init -y

3. Install dependencies

npm install express cors dotenv mongoose

For development:

npm install --save-dev nodemon

4. Start the server

node server.js

The server will run at:

http://localhost:5000

API Test

Open the following URL in your browser:

http://localhost:5000/

Expected output:

AI StudyBuddy Server is Running

Environment Variables

Create a ".env" file inside the "server" folder:

PORT=5000
MONGODB_URI=your_mongodb_connection_string

Future Enhancements

- AI chatbot integration
- User authentication
- Personalized study plans
- Quiz generation
- Progress tracking
- Voice-based learning assistant
- Study reminders

Project Goal

The main goal of AI StudyBuddy is to provide students with an intelligent and interactive platform that supports their learning and makes studying easier and more effective.

License

This project is developed for educational and academic purposes.
