# PulseChat

**PulseChat** is a modern, responsive real-time chatting web application that allows users to sign up, log in, and start messaging instantly. Built using Firebase for authentication and storage, and Bootstrap for clean, responsive design.

---

## 🚀 Features

- **Responsive Design** — Works great on mobile, tablet, and desktop
- **Authentication** — Secure Sign Up & Login using Firebase Auth
- **Real-time Messaging**

---

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Animations:** LottieFiles
- **Backend:** Firebase Authentication, Firestore

---

## 📦 Setup Instructions

1. **Clone this repository:**

   ```bash
   git clone https://github.com/cdsmar/chat-application.git
   cd chat-application
   ```

2. **Open the project in your browser:**

   You can just open `home.html` directly, or serve it via a local server.

   ```bash
   # Using Python 3
   python -m http.server 9092
   ```

3. **Configure Firebase:**

   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project.
   - Enable **Authentication** → **Email/Password**.
   - In your project settings, get your Firebase config and replace it in the script:
   ```const firebaseConfig = {
        apiKey: "AIzaSyA3I-rham3JmOeM2ByfZqDNOY1ap81TbcI",
        authDomain: "users-12cc2.firebaseapp.com",
        projectId: "users-12cc2",
        storageBucket: "users-12cc2.appspot.com",
        messagingSenderId: "844212290093",
        appId: "1:844212290093:web:2575fe7121605bc3c4aea4",
        measurementId: "G-Y7E4Y31J32"
     ```};
