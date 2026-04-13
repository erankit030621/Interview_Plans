# AI-Powered MERN Web Application

## Project Overview
AI-Powered MERN Web Application is a modern full-stack platform built with MongoDB, Express.js, React.js, and Node.js. The application combines secure authentication, CRUD operations, and responsive front-end design with an AI-powered explanation engine that transforms user queries into intelligent, contextual responses.

This application demonstrates how AI can enhance the support experience by interpreting user input, generating clear explanations, and delivering actionable feedback. It is ideal for use cases such as customer support assistants, learning tools, knowledge-base interfaces, and intelligent response systems.

## Key Features
- ✅ JWT-based authentication for secure login and registration
- 🔒 Protected routes for authenticated users
- 📝 Full CRUD functionality for managing app data
- 🤖 AI-powered explanation / response generation
- 🌐 RESTful API architecture for clean backend design
- 📱 Responsive UI for an optimized user experience on desktop and mobile
- ⚠️ Error handling and validation across client and server

## Tech Stack
- **Frontend:** React.js, CSS, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **AI Integration:** OpenAI API (or similar AI service)

## AI Workflow
1. **User inputs query** in the frontend interface
2. **Frontend sends request** to the backend API endpoint
3. **Backend processes the request** and calls the AI API
4. **AI generates a response** based on the user prompt and context
5. **Response is returned** to the frontend and displayed instantly

## Installation Guide
### 1. Clone the repository
```bash
git clone https://github.com/ankit-jayswal/ai-powered-mern-web-app.git
cd ai-powered-mern-web-app
```

### 2. Install dependencies
```bash
cd Backend
npm install

cd ../Frontend
npm install
```

### 3. Setup environment variables
Create a `.env` file inside the `Backend` folder with the following values:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
```

### 4. Run development server
```bash
cd Backend
npm run dev
```
Then start the frontend:
```bash
cd ../Frontend
npm run dev
```

## Environment Variables
- `MONGO_URI` - MongoDB connection string
- `JWT_SECRET` - Secret key for JWT authentication
- `OPENAI_API_KEY` - API key for the AI service

## Folder Structure
```
/client
/server
/routes
/controllers
/models
```

## KPIs / Highlights
- 🚀 Scalable application architecture designed for growth
- 🧹 Clean code practices and modular project organization
- 🔐 Secure authentication using JWT
- 🤝 AI integration for enhanced user interactions

## Future Enhancements
- 🗂️ Chat history management for better user context
- 🎙️ Voice-based AI interaction for accessibility
- ☁️ Deployment to AWS, Vercel, or other cloud platforms
- ⚡ Performance optimization for faster load times

## Author
- **Name:** Ankit Jayswal
- **GitHub:** https://github.com/erankit030621
- **LinkedIn:** https://www.linkedin.com/in/erankit030621/
- **Portfolio:** https://port-folio-theta-plum.vercel.app/
