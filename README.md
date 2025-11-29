# OES-Application-
Martha No. 7 Application 
Martha Chapter #7 - OES Membership Application
This is a single-page web application designed for Martha Chapter #7 of the Order of the Eastern Star (O.E.S.) to securely collect membership applications and allow administrators to review them in a real-time panel.
The application uses HTML, Tailwind CSS, and pure JavaScript with Google Firestore for persistent data storage.
Key Features
• Responsive Design: Optimized for mobile and desktop viewing.
• Secure Storage: Applications are saved instantly to a Firebase Firestore database.
• Admin Panel: A dedicated, password-protected view for reviewing all submitted applications in real-time.
🔒 Administrator Access
To access the panel and view submitted applications, click the "Admin Login: Review Applications" button on the main page and enter the following secret code:
Admin Code: STARADMIN123
🛠️ Installation and Setup (For Developers/Admins)
Since this application relies on Firebase for data storage and authentication, it requires a Canvas/Sandbox environment to provide the necessary configuration variables (__app_id, __firebase_config, __initial_auth_token).
If running in a local GitHub repository, you will need to replace the Canvas variables with your actual Firebase Project keys and configuration.
Data Structure
Applications are stored in your Firebase Firestore under the public collection path:
artifacts/{__app_id}/public/data/oes_applications
File Structure
The entire application (HTML, CSS, JavaScript, and Firestore logic) is contained within the single index.html file, adhering to modern web application standards for single-file deployment.
