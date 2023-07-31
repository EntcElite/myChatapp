# My Chatting App

![Chatting App Screenshot](screenshot.png)
## Introduction

My Chatting App is a real-time chat application that allows users to communicate with each other in a seamless and intuitive way. It provides a user-friendly interface for sending and receiving messages instantly.

This project was developed as part of [your course name or personal project, if applicable].

## Features

- Real-time messaging: Users can send and receive messages in real-time without the need to refresh the page.
- User authentication: Secure user authentication system for signing up and logging in.
- Avatar support: Users can upload an avatar image during registration.
- Online status: Shows the online status of other users.
- Emoji support: Users can use emojis in their messages.
- Responsive design: The app is designed to work smoothly on both desktop and mobile devices.

## Technologies Used

- React: Front-end library for building user interfaces.
- Firebase: Backend-as-a-Service (BaaS) platform for real-time database, authentication, and cloud storage.

## Installation

To run the application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/my-chatting-app.git`
2. Navigate to the project directory: `cd my-chatting-app`
3. Install dependencies: `npm install` or `yarn install`

## Firebase Configuration

Before running the app, you need to set up your Firebase configuration in the `src/Firebase.js` file. Open the `src/Firebase.js` file and replace the existing configuration object with your own Firebase credentials:

```javascript
// src/Firebase.js

import { initializeApp } from "firebase/app";
import { getAuth } from "firebase/auth";
import { getStorage } from "firebase/storage";
import { getFirestore } from "firebase/firestore";

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID",
};

export const app = initializeApp(firebaseConfig);
export const auth = getAuth(app);
export const storage = getStorage();
export const db = getFirestore(app);

```


## Contributing

Contributions to My Chatting App are welcome! If you have any bug fixes, feature implementations, or suggestions, please follow these steps:

1. Fork the repository
2. Create a new branch:

Author - @Vaibhav-Kshirsagar
