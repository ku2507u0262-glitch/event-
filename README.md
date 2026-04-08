# 🎓 Campus Events Registration Portal

A modern, responsive web application for browsing and registering for university events. This platform allows students to explore events, select their preferred ones, and securely register using Firebase.

---

## 🚀 Features

* 🎯 Browse events by category (Tech, Cultural, Workshop)
* 🧾 Interactive event cards with seat availability
* ✅ Step-by-step registration process (Stepper UI)
* 🧑‍🎓 Student registration form
* 🔥 Real-time data storage using Firebase Firestore
* 🎉 Success confirmation overlay after registration
* 📱 Fully responsive design
* ⚡ Smooth UI interactions and animations

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
* **Backend (Database):** Firebase Firestore
* **Hosting (optional):** Firebase Hosting / GitHub Pages

---

## 📂 Project Structure

```
📁 project-folder
 ├── index.html   # Main application file
 ├── README.md    # Project documentation
```

---

## ⚙️ Firebase Setup

1. Go to Firebase Console
2. Create a new project
3. Enable **Firestore Database**
4. Copy your Firebase config
5. Replace the config in your code:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

---

## 📋 How It Works

1. User browses available events
2. Selects an event
3. Fills in personal details
4. Clicks **Register Now**
5. Data is saved to Firestore
6. Success message is displayed

---

## 🧠 Key Functionalities

* **Event Filtering**

  * Filter by category (Tech, Cultural, Workshop)

* **Dynamic UI Rendering**

  * Events rendered using JavaScript

* **Form Validation**

  * Ensures all required fields are filled

* **Cloud Storage**

  * Data stored in Firestore with timestamp

---

## 📊 Firestore Data Structure

Collection: `registrations`

```json
{
  "fullName": "John Doe",
  "studentId": "CS2024001",
  "email": "john@university.edu",
  "department": "Computer Science",
  "yearOfStudy": "2nd Year",
  "eventId": 1,
  "eventName": "TechFest 2025",
  "eventDate": "Jan 18, 2025",
  "eventVenue": "Main Auditorium",
  "registeredAt": "timestamp"
}
```

---

## 🧪 How to Run

1. Download or clone the project
2. Open `index.html` in your browser
   OR
3. Use Live Server in VS Code

---

## 🎨 UI Highlights

* Elegant typography (Playfair Display + Instrument Sans)
* Minimal aesthetic color palette
* Interactive hover effects
* Smooth transitions and animations

---

## 🔒 Security Note

* Do NOT expose Firebase config in production without rules
* Set proper Firestore security rules

---

## 📌 Future Improvements

* 🔐 User authentication (login/signup)
* 📧 Email confirmation system
* 📊 Admin dashboard for event management
* 🎟️ QR-based event entry system

---

## 👨‍💻 Author

**Your Name Here**

---

## ⭐ Acknowledgements

* Firebase for backend services
* Google Fonts for typography inspiration

---

## 📜 License

This project is for educational purposes. Feel free to modify and use.

---
