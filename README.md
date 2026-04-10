# Thoughts App

> A full-stack application for creating, managing, and sharing personal thoughts with authentication and user dashboards

[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express.js-4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Handlebars](https://img.shields.io/badge/Handlebars.js-4.x-f0772b?style=for-the-badge&logo=handlebarsdotjs&logoColor=white)](https://handlebarsjs.com/)

![Project Demo](https://github.com/user-attachments/assets/68784de6-ca9a-4150-8065-a8ffec4a205b)
![Project Demo](https://github.com/user-attachments/assets/4834e2ff-731d-4528-ab7a-72bcc7536c8b)
![Project Demo](https://github.com/user-attachments/assets/fb3f297c-5188-4e07-8079-f08809d0781f)

---

## 🎯 About

Thoughts App is a full-stack web application that allows users to create, manage, and share personal thoughts in a simple and intuitive way.

The project was built to practice backend architecture using Node.js and Express, focusing on MVC structure, authentication, and CRUD operations. It simulates a real-world application where users can manage their own content securely.

## ✨ Key Features

- 🔐 **User Authentication** - Register and login system with session handling
- 📝 **CRUD for Thoughts** - Create, edit, delete, and view personal thoughts
- 📊 **User Dashboard** - Manage all your thoughts in one place
- 🌐 **Server-Side Rendering** - Dynamic pages using Handlebars
- 🔒 **Protected Routes** - Only authenticated users can manage content

## 🛠️ Tech Stack

**Backend:**
- Node.js - Runtime environment
- Express.js - Web framework
- Sequelize - ORM for database management

**Frontend:**
- Handlebars - Template engine for dynamic views
- CSS - Styling

**Database:**
- SQLite (or configured database via Sequelize)

**Tools:**
- Nodemon - Development server
- Express-session - Session management

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/thoughts.git

# Navigate to project
cd thoughts

# Install dependencies
npm install

# Run the project
npm start
```

Access in your browser:
```bash
http://localhost:3000
```

## 📁 Project Structure

```
thoughts/
├── controllers/        # Business logic
├── models/             # Database models
├── routes/             # Application routes
├── views/              # Handlebars templates
│   ├── layouts/
│   ├── auth/
│   └── toughts/
├── public/             # Static files (CSS, images)
├── db/                 # Database connection
├── helpers/            # Helper functions
└── index.js            # Entry point
```

## 💡 Technical Highlights

### MVC Architecture
The project follows a clear MVC pattern:
- **Models:** Handle database structure and relationships
- **Controllers:** Contain business logic
- **Routes:** Define endpoints and request handling

```javascript
// Example route structure
router.get('/dashboard', checkAuth, ToughtController.dashboard)
```

### Authentication System

Custom authentication using sessions:
- Login & registration flow
- Route protection via middleware
- User-specific data handling

## 📚 What I Learned

**Technical Skills:**
- Building RESTful applications with Express
- Structuring projects using MVC architecture
- Implementing authentication and session management

**Best Practices:**
- Separation of concerns (controllers, models, routes)
- Middleware usage for authentication
- Organized folder structure

## 🗺️ Roadmap
- [ ] Add likes or reactions to thoughts
- [ ] Implement comments system
- [ ] Improve UI/UX design
- [ ] Add pagination for thoughts
- [ ] Deploy to production (Render / Railway)

## 📝 Notes
- This is a practice/learning project
- Focused on backend architecture and fundamentals

## 📄 License
MIT License - see LICENSE for details

## 👤 Author

**Luan Henrique Neumann**

- LinkedIn: [LuanNeumannDev](https://www.linkedin.com/in/luan-henrique-neumann-dev/)
- GitHub: [@Luan-Neumann-Dev](https://github.com/Luan-Neumann-Dev)
- Email: luan.neumann.dev@gmail.com

---

⭐ Found this helpful? Give it a star!