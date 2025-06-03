# Big Deal Investment Website

This is a simple investment website with Firebase authentication (email/password login). It uses JavaScript for authentication and is styled with Tailwind CSS.

## Setup Instructions

### 1. Firebase Setup
- Go to https://console.firebase.google.com
- Create a new project
- Enable Email/Password authentication (under Authentication > Sign-in Method)
- Add a Web App and get your Firebase config snippet

### 2. Add Firebase Config
- Open `js/firebase.js`
- Replace the placeholders in `firebaseConfig` with your Firebase project details

### 3. Running Locally
You can open the HTML files directly in a modern browser (Chrome, Firefox, Edge).

### 4. Deploying to GitHub + Vercel
- Create a GitHub repository and push this project
- Connect the repo to Vercel (https://vercel.com)
- Deploy!

## Project Structure
- `login.html` - Login page
- `signup.html` - Signup page
- `dashboard.html` - Protected dashboard page
- `js/firebase.js` - Firebase config and initialization
- `js/auth.js` - Authentication helper functions

## Notes
- Update Firebase config before deploying.
- This is a basic demo. Add your investment products in `dashboard.html`.
