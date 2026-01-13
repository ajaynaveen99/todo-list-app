# 📝 Todo List Application (React)

A simple and interactive Todo List application built with React. This project demonstrates CRUD operations, search functionality, edit/save flow, and controlled components using React Hooks.

## 🌐 Live Demo
👉 [https://todo-list-app-component.netlify.app/]

## 📌 Project Overview

This Todo List app allows users to:
- Add new todo items
- Edit existing todo descriptions
- Mark todos as completed using a checkbox
- Delete todos only after marking them as completed
- Search todos by description or ID

The project focuses on React fundamentals and clean state management.

## 🧩 Features

### ✅ Add Todo
- Users can add a new todo using the input field
- Empty input is restricted with an alert message

### ✏️ Edit & Save Todo
- Click Edit to modify a todo description
- Click Save to update the changes
- Only one todo can be edited at a time

### 🔍 Search Todo
- Search todos by description text or Todo ID
- Search updates results dynamically

### ☑️ Complete Todo
- Each todo has a checkbox
- Checkbox marks the todo as completed

### 🗑️ Delete Todo (Conditional)
- Todo can be deleted only if marked as completed
- Prevents accidental deletion

## 🛠️ Technologies Used
- React.js
- JavaScript (ES6)
- React Hooks (useState)
- HTML & CSS
- Netlify (Deployment)

## 📂 Component Structure
```
src/
├── TodoList.jsx
├── TodoSearch.jsx
├── App.jsx
├── index.js
└── styles.css
```
