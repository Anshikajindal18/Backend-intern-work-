Backend Developer Intern Assignment

A scalable REST API with authentication & role-based access control, built with Node.js, Express, MongoDB, and React.js.

## 🚀 Features

### Backend
- User registration & login with JWT authentication
- Role-based access control (User/Admin)
- CRUD operations for Tasks
- Password hashing with bcrypt
- Input validation and error handling
- MongoDB database with Mongoose
- Security middleware (Helmet, Rate Limiting)
- Docker containerization

### Frontend
- React.js user interface
- User registration and login
- Task management (Create, Read, Update, Delete)
- JWT token handling
- Responsive design
- Error/success notifications

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt
- **Frontend**: React.js, Axios
- **Database**: MongoDB
- **Containerization**: Docker, Docker Compose
- **Security**: Helmet, CORS, Rate Limiting

## 📋 API Endpoints

### Authentication
- `POST /api/v1/auth/register` - User registration
- `POST /api/v1/auth/login` - User login
- `GET /api/v1/auth/me` - Get current user

### Tasks
- `GET /api/v1/tasks` - Get all tasks (authenticated)
- `POST /api/v1/tasks` - Create new task (authenticated)
- `PUT /api/v1/tasks/:id` - Update task (authenticated)
- `DELETE /api/v1/tasks/:id` - Delete task (authenticated)

## 🐳 Quick Start with Docker

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Backend_Intern_Project
