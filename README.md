# 🧠 React State Management Counter Series

This project series demonstrates different approaches to state management in React applications by building an interactive counter app. It progresses from simple to advanced solutions: `useState`, `Context API`, and `Redux`.

---

## 📌 Project Description

Each version of the counter app builds upon the previous one:

1. **useState**: Local state management in a component.
2. **Context API**: Global state shared across multiple components.
3. **Redux**: Scalable, modular state for complex applications.

---

## 🎯 Learning Objectives

By completing this project series, you will:

- Understand fundamental React state management using `useState`.
- Implement global state with Context API.
- Master Redux and Redux Toolkit.
- Compare the strengths and use-cases of each solution.
- Maintain a single source of truth for your application.
- Structure scalable and maintainable React apps.

---

## ⚙️ Requirements

### ✅ Technical

- Node.js (v14+)
- npm or yarn
- React (v18+)
- TypeScript
- Next.js
- Redux Toolkit
- React-Redux

### 💻 Development Environment

- Code editor (VS Code recommended)
- Terminal or command-line access
- Modern browser (Chrome, Firefox, or Edge)

---

## 💡 Best Practices

### 🔹 General React

- Use TypeScript for type safety.
- Keep components focused and small.
- Separate concerns (UI vs. logic/state).
- Use immutable state updates.
- Follow the Single Responsibility Principle.

### 🔸 Context API

- Use context providers at the right level in the component tree.
- Create custom hooks for consuming context.
- Type your context values properly.

### 🔺 Redux

- Follow Redux Toolkit's slice-based architecture.
- Use typed hooks for dispatch and state selection.
- Memoize selectors when appropriate.
- Use middleware for side effects where needed.

---

## 🗂 Project Structure

```bash
├── pages/
│   └── counter-app.tsx  # Main app logic
├── components/
│   └── layouts/
│       └── Header.tsx  # Shared header with counter
├── context/             # (Context API version)
│   └── CountContext.tsx
├── store/               # (Redux version)
│   └── store.ts
