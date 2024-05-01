<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="100" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="120" alt="tailwindcss logo"  />
  <img width="12" />
  <img width="100" src="https://vitejs.dev/logo.svg" alt="Vite logo">
</div>

###
# React JS Practice Source Code Repository

Welcome to the repository dedicated to those embarking on the journey of learning React JS through hands-on practice! This repository contains a variety of source code examples, exercises, and project snippets specifically designed to help you grasp the fundamentals and advanced concepts of React JS. Whether you are a beginner looking to understand the basics or an experienced developer aiming to polish your skills, this repository serves as a valuable resource to support your learning journey.

## What's Inside?

The repository is structured to facilitate easy learning and exploration of React JS programming:

- **Component Basics**: Learn how to build and manage React components, the building blocks of any React application.
- **State & Props**: Dive into managing state and using props to pass data between components.
- **Hooks**: Understand how to use React hooks like `useState`, `useEffect`, and custom hooks to simplify your component logic.
- **Routing**: Implement navigation in your projects with React Router.
- **Context API**: Manage global state more elegantly using React's Context API.

## Getting Started with React JS Using Vite and Tailwind CSS

To get started with building React applications using Vite as your build tool and integrating Tailwind CSS for styling, follow these steps. Vite provides a modern build system that significantly speeds up the development process, and Tailwind CSS offers utility-first styling that can be easily applied to your React components.

### Prerequisites

Ensure you have the following installed on your computer:

- [Node.js](https://nodejs.org/en/download/) (latest stable version)
- A preferred text editor like [Visual Studio Code](https://code.visualstudio.com/Download)
- Website [React JS](https://react.dev/)
- Website [Vite](https://vitejs.dev/)
- Website [Tailwind CSS](https://tailwindcss.com/)

### Step 1: Create a New React Project with Vite

1. Open your terminal.
2. Run the following command to create a new project with Vite:
   ```bash
   npm create vite@latest my-react-app --template react
   
3. Navigate into your new project directory:
   ```bash
   cd my-react-app

### Step 2: Install Tailwind CSS

1. Install the necessary packages for Tailwind CSS:
    ```bash
    npm install -D tailwindcss postcss autoprefixer

2. Initialize Tailwind CSS by creating the default configurations:
    ```bash
   npx tailwindcss init -p

3. Configure tailwind.config.js to purge unused styles in production by editing it as follows:
     ```bash
     module.exports = {
    content: ["./index.html", "./src/**/*.{js,jsx,ts,tsx}"],
    theme: {
    extend: {},
    },
    plugins: [],
    }

4. Include Tailwind in your CSS by adding this to your src/index.css:
    ```bash
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

### Step 3: Run Your React Application
1. Start your React application:
   ```bash
   npm run dev
2. Open your browser and go to http://localhost:3000 to see your new React app running with Vite and styled with Tailwind CSS.


<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=120&section=footer"/>
