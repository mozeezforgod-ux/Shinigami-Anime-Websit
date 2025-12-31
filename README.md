ShiniamiX – Anime Streaming Web App

ShiniamiX is a responsive web application for streaming anime videos directly from your website. It allows users to sign up, log in, and watch anime episodes. Admins can upload new anime and episodes directly through the admin panel. The app also supports dark/light mode and PWA features.

Features

User Authentication:

Sign Up and Login with Firebase Authentication

"Remember Me" option for persistent login

Anime Library:

Browse a list of anime with cover images

Click an anime to view and play its episodes

Episode Management (Admin):

Admins can add new anime titles with images

Admins can upload episodes (video files) linked to anime

Watch History:

Track the time progress of watched episodes

UI/UX Features:

Dark/Light mode toggle

Responsive design for mobile and desktop

Grid layout for anime and episodes

PWA Ready:

Service worker support for offline capabilities

Demo

Note: Replace this section with a link to your deployed site if available.

Technologies Used

HTML, CSS, JavaScript (ES6 Modules)

Firebase: Authentication, Firestore, Storage

Progressive Web App (PWA) support

CSS Grid for layout

Installation & Setup

Clone the repository

git clone https://github.com/YOUR_USERNAME/shinigamix.git
cd shinigamix


Set up Firebase

Create a Firebase project at https://firebase.google.com/

Enable Authentication (Email/Password)

Enable Firestore

Enable Storage

Replace YOUR_API_KEY and YOUR_APP_ID in the code with your Firebase credentials.

const firebaseConfig = { 
  apiKey: "YOUR_API_KEY", 
  authDomain: "shinigamix.firebaseapp.com", 
  projectId: "shinigamix", 
  storageBucket: "shinigamix.appspot.com", 
  appId: "YOUR_APP_ID"
};


Serve the app locally

You can use any local server, e.g., VS Code Live Server or Python HTTP server:

# Python 3
python -m http.server 8000


Then open http://localhost:8000 in your browser.

Admin Setup

In Firebase Firestore, create a users collection

Set your admin user with { role: "admin" }

Admin panel will appear for users with role "admin"

Usage

Login / Sign Up: Users can create accounts or log in

Browse Anime: Click an anime cover to load episodes

Watch Episodes: Play videos with progress tracked automatically

Admin Panel: Add new anime and upload episodes

Folder Structure
/ (root)
│   index.html       # Main HTML file
│   manifest.json    # PWA manifest
│   sw.js            # Service worker
└───/assets          # Optional folder for images/videos

Contributing

Contributions are welcome!

Fork the repository

Create a branch (git checkout -b feature-name)

Commit your changes (git commit -m "Add feature")

Push to the branch (git push origin feature-name)

Open a Pull Request

License

This project is MIT licensed – see the LICENSE
 file for details.

Contact

Developer: Abubakar Emmanuel

Email: your-email@example.com

GitHub: https://github.com/YOUR_USERNAME
