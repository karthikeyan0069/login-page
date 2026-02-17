# 🌈 Colorful Authentication System

A modern and interactive **Login & Registration Web Application** built using **HTML, CSS, and JavaScript**.
This project includes user registration, login authentication, password strength checking, session handling, and logout functionality using **LocalStorage**.

---

## 📌 Project Overview

The **Colorful Auth System** provides a basic front-end authentication workflow where users can:

* Register new accounts
* Log in using saved credentials
* View a dashboard after login
* Log out securely

All user data is stored locally in the browser without requiring a backend server.

---

## ✨ Features

* 🔄 Login & Register tab switching
* 💾 User data stored using LocalStorage
* 🔐 Login authentication validation
* 🔒 Password strength checker (Weak / Medium / Strong)
* 👤 Dashboard after successful login
* 🚪 Logout button with session removal
* 🎨 Animated colorful gradient UI
* 📱 Responsive design
* 📄 Single HTML file implementation

---

## 🛠️ Technologies Used

* **HTML5** — Page structure
* **CSS3** — Styling, animations, and layout
* **JavaScript (Vanilla JS)** — Application logic
* **LocalStorage API** — Client-side storage & session handling

---

## 📂 Project Structure

```
Colorful-Auth-System/
│
├── index.html
└── README.md
```

No external libraries or frameworks are used.

---

## 🚀 How to Run the Project

1. Copy the code into a file.
2. Save as:

```
index.html
```

3. Open the file using any browser:

* Google Chrome
* Microsoft Edge
* Firefox

✅ Works offline
✅ No installation required

---

## 🧭 Application Workflow

```
Register User
      ↓
User Stored in LocalStorage
      ↓
Login with Credentials
      ↓
Dashboard Displayed
      ↓
Logout → Session Cleared
```

---

## 🔐 Authentication Logic

### Registration

* Creates a username and password.
* Prevents duplicate usernames.
* Saves user data in LocalStorage.

### Login

* Validates credentials against stored users.
* Creates a login session using `loggedUser`.

### Logout

* Removes session data from LocalStorage.
* Reloads application to return to login screen.

---

## 🔒 Password Strength Checker

Password strength updates dynamically while typing:

* 🔴 Weak — short password
* 🟡 Medium — basic password
* 🟢 Strong — contains uppercase letters and numbers

---

## 💾 LocalStorage Usage

| Key          | Purpose                 |
| ------------ | ----------------------- |
| `users`      | Stores registered users |
| `loggedUser` | Maintains login session |

---

## 🎯 Learning Outcomes

This project demonstrates:

* Form handling with JavaScript
* DOM manipulation
* Client-side authentication logic
* Session simulation
* UI state management
* LocalStorage data persistence

---

## 🔮 Future Enhancements

* 👁️ Show/Hide password toggle
* ✅ Confirm password validation
* 📧 Email-based login
* 🌙 Dark/Light theme toggle
* 🔐 Password encryption (backend integration)
* ☁️ Database connection (Node.js / Firebase)

---

## 👨‍💻 Author

**Karthikeyan V**
UI/UX Designer & Web Developer

📧 [karthikeyanv0069@gmail.com](mailto:karthikeyanv0069@gmail.com)
🔗 LinkedIn: https://www.linkedin.com/in/karthi-keyan-v-767271375
💻 GitHub: https://github.com/karthikeyan0069

---

⭐ *A beginner-friendly authentication project demonstrating modern frontend login system concepts.*


OUTPUT:https://karthikeyan0069.github.io/login-page/
