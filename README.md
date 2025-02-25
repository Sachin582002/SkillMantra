# SkillMantra - An Online Learning Platform

SkillMantra is a full-stack online learning platform that allows students to browse, enroll in courses, and filter courses by category. Instructors can create, manage, and delete courses. The platform features authentication, authorization, and an integrated stripe payment gateway.

## Features

### Authentication & Authorization
- Secure user authentication (JWT-based).
- Role-based authorization (Instructor & Student).

### Student Features
- Browse and filter courses by category.
- Enroll in courses.
- View enrolled courses and track progress.

### Instructor Features
- Upload, manage, and delete courses.
- Manage course content and structure.

### Payment Integration
- Secure payments using stripe payment gateway.

## Tech Stack

### Frontend
- React.js
- Redux (State Management)
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose for ODM)
- JWT for authentication

### Other Tools
- Cloudinary for course media uploads.
- Stripe for payments.
- Git & GitHub for version control.

## Installation & Setup

### Prerequisites
- Node.js & npm installed.
- MongoDB set up (local or cloud-based).
- Git installed.

### Clone the Repository
```sh
git clone https://github.com/yourusername/skillmantra.git
cd skillmantra
```

### Backend Setup
```sh
cd backend
npm install
npm run dev
```

### Frontend Setup
```sh
cd frontend
npm install
npm run dev
```

## Environment Variables
Create a `.env` file in the backend directory with the following variables:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SECRET_KEY=
API_KEY=
API_SECRET=
CLOUD_NAME=
STRIPE_SECRET_KEY=
STRIPE_PUBLISHABLE_KEY=
WEBHOOK_ENDPOINT_SECRET=
FRONTEND_URL=
```

## Contribution
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-branch`.
3. Commit changes: `git commit -m "Added new feature"`.
4. Push to the branch: `git push origin feature-branch`.
5. Create a Pull Request.

### Feedback
If you have any feedback, please reach out to me at sachinkunwar284@gmail.com