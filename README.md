# 📚 NITJ IT Resource Bank

A comprehensive web application for the IT department of NIT Jalandhar, providing centralized access to academic resources, course materials, and administrative tools.

📦 **GitHub Repo**: [GithubRohitSharma/resourceBankNITJ](https://github.com/GithubRohitSharma/resourceBankNITJ)

---

## 🚀 Features

### 📚 Academic Resources
- **Previous Year Question Papers** - Search and download PYQs by semester
- **Course Materials** - Access syllabus PDFs, presentations, and textbooks
- **Subject-wise Organization** - Browse resources by specific subjects (DSA, DBMS, OS, CN, Web Development)
- **Semester-wise Breakdown** - Organized content by academic semesters

### 👥 User Management
- **Student Registration & Login** - Secure authentication with JWT tokens
- **Faculty Access** - Special privileges for faculty members
- **Admin Dashboard** - Complete content and user management system
- **Role-based Access Control** - Different permissions for students, faculty, and admins

### 📊 Content Management
- **File Upload System** - Support for various document formats
- **Google Drive Integration** - Cloud storage for resources
- **Rating System** - Upvote/downvote functionality for resources
- **Search & Filter** - Advanced search capabilities

### 🎨 User Experience
- **Responsive Design** - Mobile and desktop optimized
- **Modern UI** - Bootstrap-based interface with animations
- **Email Notifications** - OTP verification and password reset
- **Error Handling** - Comprehensive error pages and logging

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| **Backend** | Node.js, Express.js |
| **Template Engine** | Handlebars (HBS) |
| **Database** | MongoDB with Mongoose |
| **Authentication** | JWT, bcryptjs |
| **File Management** | Multer, Google Drive API |
| **Email** | Nodemailer |
| **Styling** | Bootstrap, CSS3 |
| **Logging** | Winston |
| **Development** | Nodemon |

---

## 📁 Project Structure

```
resourceBankNITJ/
├── src/
│   ├── app.js              # Main Express application
│   ├── middleware/
│   │   └── auth.js         # Authentication middleware
│   ├── models/
│   │   ├── user.js         # User model
│   │   ├── fileManager.js  # File management logic
│   │   ├── rating.js       # Rating system
│   │   └── register.js     # Registration & email
│   └── views/              # Handlebars templates
│       ├── admin.hbs       # Admin dashboard
│       ├── curriculum.hbs  # Course curriculum
│       ├── faculty.hbs     # Faculty information
│       ├── semester.hbs    # Semester-wise content
│       ├── subject.hbs     # Subject-specific pages
│       └── team.hbs        # Developer information
├── public/                 # Static assets
│   ├── css/               # Stylesheets
│   ├── js/                # Client-side JavaScript
│   └── img/               # Images and media
└── partials/              # Reusable template components
```

---

## 🚀 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB database
- Google Drive API credentials

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/GithubRohitSharma/resourceBankNITJ.git
   cd resourceBankNITJ
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   PORT=8000
   SECRET=your_jwt_secret
   MONGODB_URI=your_mongodb_connection_string
   GOOGLE_DRIVE_CREDENTIALS=your_google_drive_credentials
   FORGOTPASS=your_email_password
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Access the application**
   Open your browser and navigate to `http://localhost:8000`

---

## 👨‍💻 Developer

**Rohit Sharma** - Full Stack Developer
- **Email**: rohitsharma2003r@gmail.com
- **GitHub**: [GithubRohitSharma](https://github.com/GithubRohitSharma)
- **LinkedIn**: [Rohit Sharma](https://www.linkedin.com/in/rohit-sharma-1ba50a24b/)

---

## 🔧 Key Features Implementation

### Authentication System
- JWT-based session management
- bcrypt password hashing
- Role-based access control (Student/Faculty/Admin)

### File Management
- Google Drive API integration for cloud storage
- Support for multiple file formats
- Organized file structure by subjects and semesters

### Admin Dashboard
- User management (view, add, remove users)
- Content moderation and approval
- Analytics and reporting features

### Rating System
- Upvote/downvote functionality for resources
- User feedback collection
- Quality assessment of uploaded content

---

## 📝 License

This project is licensed under the ISC License.

---

## 🤝 Contributing

This is a project for the IT department of NIT Jalandhar. For contributions or questions, please contact the developer directly.

---

*Built with ❤️ for the IT Department, NIT Jalandhar* 
