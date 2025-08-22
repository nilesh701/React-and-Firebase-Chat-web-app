# React-and-Firebase-Chat-web-app

React and Firebase Chat App Tutorial

This project demonstrates how to build a real-time chatroom application using React, Firebase Firestore for real-time messaging, and Firebase Authentication for user authentication with Google. In this tutorial, you'll learn key React concepts such as managing global state with the Context API, creating custom hooks for consuming context, and synchronizing data with external services like Firebase.

What You'll Learn in This Tutorial

Context API for Global State: Learn how to store and manage global state across your app.

Custom Hooks: Understand how to create and use custom hooks to consume context and synchronize with external data sources, like Firebase.

Authenticated and Unauthenticated States: Build different UI components for users based on their authentication status—whether they are logged in or not.

Real-Time Messaging with Firestore: Use Firebase Firestore to handle real-time updates of messages in the chatroom.

Google Authentication with Firebase: Set up Firebase Authentication for users to log in using their Google account, ensuring secure user authentication.

Steps to Get Started

Obtain Firebase Configuration:

Go to the Firebase Console and create a new Firebase project.

Navigate to your project settings and obtain your Firebase configuration.

Add Firebase Configuration to Your Project:

Open the src/services/firebase.js file in your project.

Paste your Firebase configuration object there to initialize Firebase services (Firestore, Authentication).

Install Dependencies and Start the Project:

Install the required dependencies by running:
