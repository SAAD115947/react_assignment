# React Routing & Firebase Authentication
<h2><mark><strong>Student ID: C243085</strong></mark></h2>
**Course:** Tools & Technologies for Internet Programming

A simple React app with React Router, Firebase Email/Password Authentication, and protected routes.

## Pages

| Page | Route | Access |
|---|---|---|
| Home | `/` | Public |
| Login | `/login` | Public |
| Register | `/register` | Public |
| Dashboard | `/dashboard` | Protected |
| Profile | `/profile` | Protected |

## Features

- Navigation with React Router
- Register, Login, and Logout with Firebase Authentication
- Dashboard and Profile accessible only to logged-in users (others are redirected to Login)
- Navbar shows Login/Register or Logout based on login status
- User stays logged in after page refresh

## Run the Project

```
npm install
npm install react-router-dom firebase
npm start
```



Open http://localhost:3000
