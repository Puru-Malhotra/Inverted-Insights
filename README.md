# Inverted-Insights

Link to website


https://invertedinsights-46b56.web.app/



Use the following access keys and codes for firebase:


# NPM
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyAvPWFGp1cjfZh8s9xSktdiL7tqXbgte60",
  authDomain: "invertedinsights-46b56.firebaseapp.com",
  projectId: "invertedinsights-46b56",
  storageBucket: "invertedinsights-46b56.appspot.com",
  messagingSenderId: "1012100634877",
  appId: "1:1012100634877:web:c8929a3b45c012cba10694",
  measurementId: "G-ZBC341J47L"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);



# Script tag in HTML
<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.9.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.9.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyAvPWFGp1cjfZh8s9xSktdiL7tqXbgte60",
    authDomain: "invertedinsights-46b56.firebaseapp.com",
    projectId: "invertedinsights-46b56",
    storageBucket: "invertedinsights-46b56.appspot.com",
    messagingSenderId: "1012100634877",
    appId: "1:1012100634877:web:c8929a3b45c012cba10694",
    measurementId: "G-ZBC341J47L"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
