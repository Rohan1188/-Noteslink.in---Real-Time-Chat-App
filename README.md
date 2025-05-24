# Noteslink.in---Real-Time-Chat-App
A modern, minimalistic real-time group chat application built with HTML, CSS, and JavaScript, powered by Firebase for authentication and Firestore for message storage.


# 🗨️ Noteslink.in - Real-Time Chat App

A modern, minimalistic real-time group chat application built with **HTML**, **CSS**, and **JavaScript**, powered by **Firebase** for authentication and Firestore for message storage.

Deployment : https://noteslink-in-real-time-chat-app.vercel.app/

 Preview: ![image](https://github.com/user-attachments/assets/20da3735-6e52-40e6-acdc-0d6abea6744d)



 
## 🚀 Features

* 🔐 Google Sign-In authentication
* 💬 Real-time chat updates using Firestore
* 👤 User avatars and usernames
* 🌐 Responsive design for all devices
* 🔄 Live presence indicator and UI transitions
* 🌈 Beautiful gradient UI with intuitive layout
* 🚫 Error handling with friendly messages

## 🔧 Technologies Used

* **Frontend**: HTML, CSS, Vanilla JavaScript
* **Authentication**: Firebase Auth (Google)
* **Database**: Firebase Firestore
* **Hosting**: Can be deployed on Firebase Hosting, Vercel, Netlify, etc.

## 🔥 Firebase Configuration

This app uses Firebase for backend services. Make sure to replace the config in the JavaScript block with your own Firebase project settings:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
```

## 📦 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/noteslink-chat.git
   cd noteslink-chat
   ```

2. **Set up Firebase**

   * Go to [Firebase Console](https://console.firebase.google.com/)
   * Create a project
   * Enable **Authentication > Google Sign-In**
   * Create a **Cloud Firestore** database
   * Add your Firebase configuration to `index.html`

3. **Run the app**

   * Open `index.html` in your browser
   * Sign in with Google and start chatting!

## 📁 Project Structure

```
📦 noteslink-chat
 └── index.html      # Main HTML file with embedded CSS and JS
```

## ✅ To-Do / Improvements

* [ ] Add private 1-on-1 chat
* [ ] Add chat room creation feature
* [ ] Emoji support
* [ ] Message editing and deletion
* [ ] Push notifications

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions.
