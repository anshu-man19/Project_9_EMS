# Employee Management System

A simple role-based Employee Management System built using React and Vite.

## Features
- Login system with two roles: Manager and Employee
- Separate dashboards for Manager and Employee
- Managers can create and assign tasks to employees
- Employees can accept tasks and mark them as completed or failed
- Task status tracking (New, Accepted, Completed, Failed)

## Tech Stack
- React
- Vite
- JavaScript
- CSS
- React Context API
- Browser localStorage

## Project Structure
src/
 ├─ components/
 │   ├─ Auth/
 │   ├─ Dashboard/
 │   ├─ TaskList/
 │   └─ other/
 ├─ context/
 │   └─ AuthProvider.jsx
 ├─ utils/
 │   └─ localStorage.jsx
 ├─ App.jsx
 ├─ main.jsx
 └─ index.css
## Notes
- This is a frontend-only project
- Data is stored using browser localStorage
- No backend is used

## Future Scope
- Backend integration using Node.js and Express
- Database support