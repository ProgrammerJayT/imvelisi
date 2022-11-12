# e-skhwama


#initial project setups
https://github.com/ProgrammerJayT/e-skhwama.git

echo "# e-skhwama" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ProgrammerJayT/e-skhwama.git
git push -u origin main




#installing firebase
npm install firebase


#Firebase configurations
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBU9UTYFbKe6U0qsL346KmfP7cAsaIDRQY",
  authDomain: "e-skhwama.firebaseapp.com",
  projectId: "e-skhwama",
  storageBucket: "e-skhwama.appspot.com",
  messagingSenderId: "163761623019",
  appId: "1:163761623019:web:8eb8733598b3b816b753ae",
  measurementId: "G-Z105R5P2YT"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
