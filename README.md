# 🚀 Leads Tracker PWA

A Progressive Web App (PWA) for tracking leads, built using Firebase Realtime Database. This project is a mobile version of a leads tracker that helps store links efficiently in the cloud instead of relying solely on Local Storage.

🔗 Inspired by Scrimba, where I learned the concepts of local storage and Firebase database integration! 🎓

## 📌 Features

- ✅ Add links to track important leads 🔗
- ✅ Retrieve saved leads from Firebase in real-time ⏳
- ✅ Delete all leads with a double-click 🗑️
- ✅ Mobile-friendly for quick access 📱
- ✅ Uses Firebase Realtime Database instead of local storage for better scalability ☁️

## 🛠️ Technologies Used

- HTML, CSS, JavaScript 🖥️

- Firebase Realtime Database 🔥

- Progressive Web App (PWA) Concepts 📲

## 📜 Code Explanation

### 🔥 Firebase Initialization

- Firebase is initialized and connected to the Realtime Database.

- A reference (leads) is created in the database to store the saved URLs.

### 🎨 UI Elements

- References to input fields, buttons, and the list container are set up to interact with the DOM.

### 📜 Render Function

- Converts an array of saved URLs into clickable links.

- Updates the UI with the list of leads whenever new data is added.

### 🔄 Fetching Data from Firebase

- Listens for real-time changes in the Firebase database.

- Retrieves saved leads and updates the UI automatically.

### 🗑️ Delete Functionality

- Allows users to delete all saved leads by double-clicking the delete button.

- Removes the data from Firebase and clears the UI.

### ➕ Add Leads

- Pushes a new URL to Firebase when the save button is clicked.

- Clears the input field after saving the lead.

## 📢 Why This Project?

- I was practicing Firebase instead of using local storage repeatedly.

- It helps store leads online, making it accessible from multiple devices.

- A simple yet effective real-world Firebase implementation.

## 🚀 How to Use?

- Enter a link in the input field.

- Click Save to store it in Firebase.

- Click the saved link to open it.

- Double-click Delete to remove all saved leads.
