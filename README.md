# 🍕 Fast React Pizza

Fast React Pizza is a simple and modern pizza ordering web application built using React, Redux, TailwindCSS, and Vite.

## 📖 Table of Contents

- [✨ Features](#-features)
- [🔧 Installation](#-installation)
- [🚀 Available Scripts](#-available-scripts)
- [💻 Technologies](#-technologies)
- [📁 Project Structure](#-project-structure)
- [📝 License](#-license)

## ✨ Features

- ⚛️ React for building reusable UI components
- 🛠️ Redux Toolkit for state management
- 🧭 React Router DOM for navigation
- 🎨 TailwindCSS for utility-first styling
- ⚡ Vite for fast development and build setup

## 🔧 Installation

To install and run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/KarimAdel-1/Pizza-Delivery.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Pizza-Delivery
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

## 🚀 Available Scripts

In the project directory, you can run the following scripts:

- **`npm run dev`**: Runs the app in development mode using Vite. Open [http://localhost:5173](http://localhost:5173) to view it in your browser.
  
- **`npm run build`**: Builds the app for production.

- **`npm run preview`**: Preview the production build locally.

## 💻 Technologies

This project uses the following technologies:

- ⚛️ **React**: Version 18.2.0
- 🛠️ **Redux Toolkit**: Version 2.2.7
- 🧭 **React Router DOM**: Version 6.11.0
- 🎨 **TailwindCSS**: Version 3.4.10
- ⚡ **Vite**: Version 4.2.0
- 👮‍♂️ **ESLint**: For linting and maintaining code quality
- 💅 **Prettier**: For code formatting
- 🛠️ **PostCSS**: For processing CSS files with Autoprefixer
- 🧩 **Vite Plugin ESLint**: To ensure ESLint runs during development

## 📁 Project Structure

```bash
.
├── public/             # 📂 Static assets
├── src/                # 🗂️ Application source code
│   ├── features/       # 🔍 Redux features (cart, order, user)
│   ├── services/       # 🌐 API services (e.g., Geocoding, Restaurants)
│   ├── ui/             # 🎨 Reusable UI components
│   ├── utils/          # 🛠️ Utility helper functions
│   ├── App.jsx         # ⚛️ Main app component
│   └── store.js        # 🛠️ Redux store configuration
├── postcss.config.js   # 📝 PostCSS configuration for Tailwind
├── tailwind.config.js  # 🎨 TailwindCSS configuration
├── vite.config.js      # ⚡ Vite configuration
└── package.json        # 📦 Project metadata and dependencies
```
