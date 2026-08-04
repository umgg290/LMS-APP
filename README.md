# 🎓 Learning Management System (LMS)

A full-stack Learning Management System (LMS) built using the MERN Stack. The platform enables educators to create and manage courses while allowing students to browse, purchase, and learn through an intuitive interface.

## 🚀 Features

### 👨‍🎓 Student
- User Authentication (Clerk)
- Browse available courses
- Purchase courses using Stripe
- Enroll in courses
- Track learning progress
- Responsive dashboard

### 👨‍🏫 Educator
- Secure educator authentication
- Create and publish courses
- Upload course thumbnails
- Manage course content
- View enrolled students
- Monitor earnings and course statistics

## 🛠 Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Authentication
- Clerk

### Payment
- Stripe

### Cloud Storage
- Cloudinary

## 📂 Project Structure

```
LMS/
│
├── client/          # React Frontend
├── server/          # Express Backend
├── models/          # MongoDB Models
├── routes/          # API Routes
├── controllers/     # Business Logic
├── middleware/      # Authentication & Validation
├── config/          # Database & Cloud Config
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/lms-mern.git
cd lms-mern
```

### Install Dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd server
npm install
```

### Configure Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

STRIPE_SECRET_KEY=your_stripe_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Run the Application

Backend

```bash
npm run server
```

Frontend

```bash
npm run dev
```

## 📸 Screenshots

Add screenshots here after deployment.

- Home Page
- Course Page
- Student Dashboard
- Educator Dashboard
- Payment Page

## 🔗 API Highlights

- User Authentication
- Course Management
- Enrollment Management
- Payment Processing
- Progress Tracking
- Image Upload

## 🎯 Future Improvements

- AI Quiz Generation
- AI Notes Generator
- Video Progress Analytics
- Certificate Generation
- Email Notifications
- Course Reviews & Ratings
- Admin Dashboard

## 🤝 Contributing

Contributions are welcome. Feel free to fork this repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

---
