# Static To-Do List React App

A simple, static To-Do List application built with React and Vite.

## Features

- Clean, modern UI with gradient background
- Responsive design
- Hover effects on list items
- Custom checkbox-style bullets

## Setup Instructions

### 1. Create a New React App with Vite

```bash
npm create vite@latest static-todo-react-app
```

- Choose **React** as the framework
- Choose **JavaScript** as the variant

### 2. Navigate to Project Directory

```bash
cd static-todo-react-app
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Set Up the Project Structure

Create a `components` folder inside the `src` directory:

```bash
mkdir src/components
```

### 5. Add the Component Files

Copy the following files to their respective locations:

- `Header.jsx` → `src/components/Header.jsx`
- `ToDoList.jsx` → `src/components/ToDoList.jsx`
- `App.jsx` → `src/App.jsx` (replace existing)
- `App.css` → `src/App.css` (replace existing)

### 6. Start the Development Server

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173`

## File Structure

```
static-todo-react-app/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   └── ToDoList.jsx
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── package.json
└── README.md
```

## Components

### Header.jsx
Displays the main heading "My To-Do List"

### ToDoList.jsx
Renders a static list of tasks:
- Learn React
- Build a project
- Read documentation

### App.jsx
Main component that combines Header and ToDoList components

## Styling

The app features:
- Centered content layout
- Gradient purple background
- White card container with shadow
- Custom checkmark-style bullets
- Smooth hover effects with color transitions
- Clean typography with proper spacing

## GitHub Repository Setup

1. Create a new repository named: `practice-toDoList-[YourFirstName]-[YourLastInitial]`
2. Make sure it's set to **public**
3. Clone the repository to your local machine
4. Copy all project files into the repository
5. Commit and push your changes:

```bash
git add .
git commit -m "Initial commit: Static To-Do List React App"
git push origin main
```

## Technologies Used

- React 18
- Vite
- CSS3

## License

This is a practice project for learning React basics.
