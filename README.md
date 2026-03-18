# 🚀 Taskify — Scalable Kanban Task Management App

A modern task management application built with **React + TypeScript**, focused on clean architecture, predictable state management, and a Kanban-style workflow.

---

## ✨ Overview

Taskify is designed to reflect how real-world frontend applications are structured.
It emphasizes **scalability, maintainability, and clear separation of concerns** rather than just feature implementation.

---

## 🧠 Features

* 🔐 JWT-based authentication with session persistence
* 🛡️ Role-based access control (RBAC)
* 📋 Kanban-style task management (create, update, delete)
* 💬 Modular comments system
* 🔍 Search, filters, and pagination via URL params
* 📄 Form validation using React Hook Form + Zod
* ⚡ Optimistic UI updates for better user experience
* 🧩 Scalable and modular project structure

---

## 🏗️ Tech Stack

| Category           | Tech                                              |
| ------------------ | ------------------------------------------------- |
| Frontend           | React 18, TypeScript, Vite                        |
| State Management   | Redux Toolkit, React Query                        |
| Routing            | React Router v6 (protected + nested routes)       |
| Forms & Validation | React Hook Form, Zod                              |
| Styling            | Tailwind CSS                                      |
| Auth               | JWT-based (extensible to Firebase / backend APIs) |

---

## 📁 Project Structure

src/
│
├── features/        # Domain-based modules (tasks, auth, projects)
├── components/      # Reusable UI components
├── routes/          # Route configuration & guards
├── services/        # API layer
├── store/           # Redux store setup
├── hooks/           # Custom hooks
└── utils/           # Helper functions

---

## ⚙️ Key Engineering Decisions

* **Redux Toolkit** → predictable global state (auth, UI)
* **React Query** → server state, caching, async handling
* **URL-driven state** → shareable filters and pagination
* **Optimistic updates** → improved perceived performance
* Clear separation between **UI, business logic, and API layer**

---

## 🔄 Project Evolution

This project was initially built in JavaScript and later rewritten in **TypeScript** to improve scalability and maintainability.

### Why TypeScript?

* Strong type safety reduces runtime errors
* Better developer experience with autocomplete
* Safer component props and API contracts
* Easier refactoring and long-term scaling


## 📈 Future Improvements

* Backend integration (Node / Express / Next.js API routes)
* Real-time updates (WebSockets)
* Testing (React Testing Library / Vitest)
* Improved mobile responsiveness
* Dark mode support

---

## 🎯 What This Project Demonstrates

* Real-world React architecture
* State management at scale
* Clean and maintainable code practices
* Thoughtful UX decisions


⭐ If you found this useful, consider giving it a star.
