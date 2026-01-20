###**Login Experiment – Context API & Redux Toolkit**###
A React application demonstrating modern state management patterns by combining Context API for authentication and Redux Toolkit for product catalog and shopping cart functionality.


**🎯 Description**

This project serves as a learning experiment to understand when and how to use different state management solutions in React. 
It showcases:
Context API for global authentication state (login/logout, user roles)
Redux Toolkit for complex state management (product catalog, cart operations)
Role-based access control with separate Admin and User experiences

**✨ Features**

Role-based login system (Admin / User)
Admin capabilities: Full product management (add, edit, delete products)
User capabilities: Browse products and manage shopping cart
Shopping cart: Add/remove products, view cart contents
Clean, intuitive UI built with modern React patterns
Persistent state across component re-renders

**🛠️ Tech Stack**

React - UI library for building component-based interfaces
Redux Toolkit - Official Redux toolset for efficient state management
Context API - React's built-in solution for sharing state across components
Vite - Next-generation frontend build tool for fast development
JavaScript/ES6+ - Modern JavaScript features

**📋 Prerequisites**
Before running this project, make sure you have:

Node.js (v14 or higher)
npm (v6 or higher) or yarn

**🚀 How to Run**
1. Clone the repository
bashgit clone <your-repository-url>
cd fsdexplugin-main
2. Install dependencies
bashnpm install
This command reads package.json and installs all required packages into the node_modules folder.
3. Start the development server
bashnpm run dev
This runs the Vite development server with hot module replacement (HMR).
4. Open in browser
Navigate to: http://localhost:5173/
The application will automatically reload when you make changes to the source code.
📁 Project Structure
fsdexplugin-main/
├── node_modules/          # Dependencies (auto-generated)
├── public/                # Static assets
├── src/
│   ├── assets/           # Images, icons, etc.
│   ├── Component/        # React components
│   ├── context/          # Context API setup (Auth context)
│   ├── redux/            # Redux store, slices, and actions
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Application entry point
│   └── index.css         # Global styles
├── .gitignore            # Git ignore rules
├── eslint.config.js      # ESLint configuration
├── index.html            # HTML template
├── package.json          # Project metadata and dependencies
├── package-lock.json     # Locked dependency versions
├── README.md             # Project documentation
└── vite.config.js        # Vite configuration


**🎮 How It Works**
Authentication Flow (Context API)

User selects role (Admin/User) on login screen
Context API stores authentication state globally
Protected routes check authentication before rendering
Role determines available features

Product & Cart Management (Redux Toolkit)

Product data stored in Redux store
Admin can dispatch actions to modify product catalog
Users can dispatch cart actions (add/remove items)
Redux manages state updates and ensures consistency

**🔧 Available Scripts**
CommandDescriptionnpm installInstall all project dependenciesnpm run devStart development server at http://localhost:5173/npm run buildCreate optimized production buildnpm run previewPreview production build locallynpm run lintRun ESLint to check code quality


**🎓 Learning Objectives**
This project demonstrates:

When to use Context API vs Redux Toolkit
How to combine multiple state management solutions
Implementing role-based access control
Modern React patterns and best practices
Setting up a Vite-based React project

**🤝 Contributing**
Feel free to fork this project and experiment with:

Adding new features (wishlist, product search, etc.)
Implementing persistent storage (localStorage, backend API)
Improving UI/UX with component libraries
Adding unit tests with Jest and React Testing Library

**📝 License**
This project is for educational purposes.

###**EXAMPLE:**###
<img width="1456" height="787" alt="image" src="https://github.com/user-attachments/assets/f8ec8bcd-d559-4777-9e82-e3612926a58a" />
<img width="1456" height="787" alt="image" src="https://github.com/user-attachments/assets/b0440d2e-db73-4a2d-88b4-a2fd8cc07afd" />
<img width="1456" height="787" alt="image" src="https://github.com/user-attachments/assets/ef5edd1e-1515-4ebd-aabd-2d82a9fcc4e9" />




**URl Link** : http://localhost:5173/
