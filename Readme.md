<h1><b>🏠Settlr – Property Listing Platform</b></h1>

Settlr is a full-stack property listing application that allows property owners to list rental properties and manage them securely. Authentication is handled using Firebase, and data is stored in MongoDB.



<h2>🚀 Features </h2>

- Firebase Google Authentication

- Secure owner-only property management

- Multi-step property listing form

- Amenities, pricing & rules support

- Owner dashboard (view & delete properties)

- REST APIs with token verification

  

<h2>🧰 Tech Stack</h2>

<h4>Frontend</h4>

React + Vite

Tailwind CSS

Firebase Authentication

<h4>Backend</h4>

Node.js

Express.js

MongoDB + Mongoose

Firebase Admin SDK



<h2>🔐 Authentication Flow</h2>

User logs in using Google (Firebase)

Firebase ID token is generated

Token is sent to backend

Backend verifies token using Firebase Admin

Properties are linked to Firebase UID

