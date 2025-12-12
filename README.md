# 📚 OpenStudy Planner

**Organize your studies. Track assignments. Manage deadlines.**

OpenStudy Planner is an open-source web application designed to help university students plan their study schedules, track assignments, and manage deadlines. The platform focuses on simplicity and usability, allowing students to organize their academic workload in one place without relying on multiple tools.

## 🎯 Project Goal

To provide a comprehensive study planning solution that helps students stay organized and improve their academic performance through effective time management and deadline tracking.

## ✨ Features

- **Course Management:** Create and manage all your courses and subjects in one place
- **Assignment Tracking:** Add assignments with deadlines, priority levels, and progress indicators
- **Calendar Views:** Weekly and monthly planner views to visualize your study schedule
- **Progress Tracking:** Monitor completed tasks and overall academic progress
- **Smart Reminders:** Optional notifications for upcoming deadlines and study sessions
- **Clean Interface:** Simple, intuitive design focused on usability

## 🚀 Getting Started

### For Students

1. **Sign up** for a free account
2. **Add your courses** for the current semester
3. **Import or manually add** assignments and deadlines
4. **Plan your study schedule** using our calendar view
5. **Track your progress** and stay on top of your academic goals

### For Developers

See our [Installation Guide](#installation) below to set up the project locally.

## 🛠️ Technologies

- **Frontend:** React.js
- **Backend:** Node.js + Express
- **Database:** PostgreSQL (with MongoDB as alternative)
- **Version Control:** Git, GitHub
- **License:** MIT

## 🤝 How to Contribute

We welcome contributions from everyone! Whether you're a student, educator, developer, or designer, there are many ways to get involved:

### 👨‍💻 Developers

- Fix bugs and improve functionality
- Add new features like calendar integrations
- Improve performance and accessibility
- Build mobile applications

### 🎨 Designers

- Improve UI/UX
- Create better visualizations for study schedules
- Design new features and workflows
- Optimize the mobile experience

### 📝 Documentation Writers

- Write user guides and tutorials
- Improve API documentation
- Create educational content
- Translate documentation

### 👥 Educators and Students

- Test the application and provide feedback
- Suggest new features based on real needs
- Share study strategies and best practices
- Help with user testing and quality assurance

## 🛠️ Installation (For Developers)

1. **Clone the repository**

    ```bash
    git clone https://github.com/w0nsdoof/OpenStudy.git
    cd OpenStudy
    ```

2. **Install dependencies**

    ```bash
    # Install backend dependencies
    cd server
    npm install

    # Install frontend dependencies
    cd ../client
    npm install
    ```

3. **Set up the database**

    ```bash
    # PostgreSQL (recommended)
    createdb openstudy_planner

    # Or MongoDB
    # Create database in MongoDB Atlas or local instance
    ```

4. **Configure environment variables**

    ```bash
    # Create .env file in server directory
    cp server/.env.example server/.env
    # Edit .env with your database credentials
    ```

5. **Run the development servers**

    ```bash
    # Start backend server (in server directory)
    npm run dev

    # Start frontend (in client directory)
    npm start
    ```

## 📋 Project Structure

```
OpenStudyPlanner/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Main application pages
│   │   ├── hooks/         # Custom React hooks
│   │   └── utils/         # Utility functions
├── server/                # Node.js backend
│   ├── controllers/       # API controllers
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   └── middleware/       # Custom middleware
├── docs/                 # Documentation
└── tests/                # Test files
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE file](LICENSE) for details.

## 🙏 Acknowledgments

- All contributors who help improve this project
- The open-source community for valuable tools and libraries
- Students and educators who provide feedback and suggestions

## 📞 Contact

- GitHub Issues: [Submit issues and feature requests](https://github.com/w0nsdoof/OpenStudy/issues)
- Email: contact@openstudyplanner.org
- Discord: [Join our community](https://discord.gg/openstudyplanner)