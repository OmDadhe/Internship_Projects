# Dr. A.P.J. Abdul Kalam Tribute Page

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

A responsive and elegant tribute page honoring the life and contributions of Dr. A.P.J. Abdul Kalam, India's "Missile Man" and former President. This project showcases fundamental web development skills with a focus on clean design and accessibility.



## 🌟 Features

- **Responsive Design**: Optimized for all device sizes from mobile to desktop
- **Timeline View**: Chronological presentation of key life events and accomplishments
- **Quote Gallery**: Collection of inspiring quotes by Dr. Kalam
- **Image Showcase**: Curated gallery highlighting significant moments
- **Smooth Scroll**: Enhanced user experience with smooth navigation

## 🚀 Live Demo

[View the live tribute page](https://venerable-klepon-9772a8.netlify.app/)

## 📋 Project Structure

```
Tribute-Page-APJ-Abdul-Kalam/
│
├── index.html          # Main HTML document
├── style.css           # CSS styling
├── script.js           # Optional JavaScript for interactive elements
│
└── assets/
    ├── images/         # Image resources
    └── fonts/          # Custom fonts (if any)
```

## 🛠️ Development

### Prerequisites

- Any modern web browser
- Basic text editor (VS Code recommended)

### Setup & Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Internship_Projects.git
   cd "1 Tribute Page-APJ-Abdul-Kalam"
   ```

2. Open `index.html` in your browser to view the project.

3. To make changes, edit the files using your preferred editor and refresh the browser to see updates.

## 📌 Learning Outcomes

- Implementation of semantic HTML5 elements
- Advanced CSS styling and layout techniques
- Responsive design principles
- Web accessibility best practices
- Performance optimization for web content

## 👨‍💻 Author

- **Om Dadhe** - [LinkedIn](https://www.linkedin.com/in/contactom/) | [GitHub](https://github.com/OmDadhe)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspiration from the life and work of Dr. A.P.J. Abdul Kalam
- [freeCodeCamp](https://www.freecodecamp.org/) for project guidelines
- Images sourced from [appropriate attribution]




# School Management System

[![MERN Stack](https://img.shields.io/badge/MERN-Stack-green?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/mern-stack)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Material UI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)](https://mui.com/)

A comprehensive school management platform built with the MERN stack, designed to streamline administrative tasks, enhance communication between teachers and students, and provide insightful performance analytics.


## 📑 Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Architecture](#-architecture)
- [Installation](#-installation)
- [Environment Setup](#-environment-setup)
- [User Roles](#-user-roles)
- [API Documentation](#-api-documentation)
- [Author](#-author)
- [License](#-license)

## 🌟 Features

- **Multi-role Authentication & Authorization**
- **Real-time Attendance Management**
- **Performance Analytics Dashboard**
- **Secure Document Management**
- **Internal Messaging System**
- **Automated Reporting**
- **Mobile-responsive Interface**

## 🚀 Demo
- **[🌐 Live Frontend Demo](https://schoolmanagementsystembyom.netlify.app/)**
- **[⚙️ Backend API](https://pms-backend-0ne7.onrender.com)**

### Test Credentials

| Role    | Username        | Password    |
|---------|-----------------|-------------|
| Admin   | admin@school.com | admin123    |
| Teacher | teacher@school.com | teacher123 |
| Student | student@school.com | student123 |

## 🏗 Architecture

```
School-Management-System/
│
├── frontend/                # React application
│   ├── public/              # Static files
│   ├── src/                 # Source code
│   │   ├── components/      # Reusable components
│   │   ├── pages/           # Application pages
│   │   ├── context/         # React context
│   │   ├── redux/           # State management
│   │   ├── utils/           # Helper functions
│   │   └── App.js           # Main application
│   └── package.json         # Dependencies
│
└── backend/                 # Express server
    ├── controllers/         # Request handlers
    ├── models/              # Database models
    ├── routes/              # API routes
    ├── middleware/          # Custom middleware
    ├── config/              # Configuration files
    ├── utils/               # Utility functions
    └── server.js            # Entry point
```

## 🔧 Installation

### Prerequisites

- Node.js (v14+)
- MongoDB (local or Atlas)
- npm or yarn

### Backend Setup

```bash
# Navigate to backend directory
cd "2 School-Management-System"/backend

# Install dependencies
npm install

# Create .env file (see Environment Setup section)
# Start development server
npm run dev
```

### Frontend Setup

```bash
# Navigate to frontend directory
cd "2 School-Management-System"/frontend

# Install dependencies
npm install

# Create .env file (see Environment Setup section)
# Start development server
npm start
```

## 🔐 Environment Setup

### Backend (.env)

```
NODE_ENV=development
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/school_management
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=30d
EMAIL_SERVICE=gmail
EMAIL_USERNAME=your-email@gmail.com
EMAIL_PASSWORD=your-app-password
CLIENT_URL=http://localhost:3000
```

### Frontend (.env)

```
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_NODE_ENV=development
```

## 👥 User Roles

### Admin
- Manage school-wide settings
- Create/edit user accounts
- Generate comprehensive reports
- Handle class assignments

### Teacher
- Mark student attendance
- Create and grade assessments
- Communicate with students/parents
- Upload learning materials

### Student
- View grades and attendance
- Submit assignments
- Access learning resources
- Communicate with teachers

## 📊 API Documentation

API endpoints are documented using Swagger UI, available at `/api-docs` when running the backend server.

Key endpoints include:

- **Authentication**: `/api/auth/*`
- **Users**: `/api/users/*`
- **Classes**: `/api/classes/*`
- **Attendance**: `/api/attendance/*`
- **Assessments**: `/api/assessments/*`

## ⚠️ Troubleshooting

### Common Issues

1. **Connection Errors**
   - Verify MongoDB connection string in `.env`
   - Check if MongoDB service is running

2. **Authentication Problems**
   - Clear browser cookies and localStorage
   - Ensure JWT_SECRET is properly configured

3. **Missing Features**
   - Some delete operations are disabled by default for data safety
   - Enable them by setting `ENABLE_DELETE=true` in backend `.env`

## 👨‍💻 Author

**Om Dadhe**
- [LinkedIn](https://www.linkedin.com/in/contactom/)
- [GitHub](https://github.com/OmDadhe)
- [Portfolio](https://your-portfolio-website.com)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Material UI](https://mui.com/) for the component library
- [React Table](https://react-table.tanstack.com/) for data grids
- [Chart.js](https://www.chartjs.org/) for analytics visualizations
- All the beta testers who provided valuable feedback
