
1i1
A comprehensive tournament management platform with bracket generation, participant tracking, and public sharing features.

© 2025 1i1. All Rights Reserved.

Features
Supports up to 128 participants with flexible tournament configurations
Random pairing and advanced match scheduling
Responsive design for desktop and mobile platforms
User authentication system
Email notifications for participants
Public tournament viewing via shortcut links
Progressive round revelation to hide future matches
Arabic language support
Getting Started
Prerequisites
Node.js 18+ and npm
Android Studio (for Android builds)
Xcode (for iOS builds, Mac only)
Web Application
To run the web application:

# Install dependencies
npm install
# Start the development server
npm run dev
The application will be available at http://localhost:5000

Mobile Application
This project uses Capacitor to build native mobile applications from the web app.

Android Setup
Build the web application:
npm run build
Add Android platform:
npx cap add android
Copy web assets to Android:
npx cap copy android
Open in Android Studio:
npx cap open android
In Android Studio, click "Run" to build and run the app on an emulator or connected device.
iOS Setup (Mac only)
Build the web application:
npm run build
Add iOS platform:
npx cap add ios
Copy web assets to iOS:
npx cap copy ios
Open in Xcode:
npx cap open ios
In Xcode, select a device or simulator and click "Run".
Deploying
Web Application
The web application can be deployed on any Node.js hosting platform. For Replit deployment:

Fork the repository on Replit
Run npm install to install dependencies
Set up environment variables if needed
Click "Run" to start the application
Use the "Deploy" button to make it available publicly
Mobile Application
To build the mobile application for distribution:

Follow the setup steps above
For Android, in Android Studio:
Build → Generate Signed Bundle/APK
Follow the wizard to create a signed APK or App Bundle
For iOS, in Xcode:
Product → Archive
Use the Organizer to distribute the app
Environment Variables
JWT_SECRET: Secret key for JWT token generation
SMTP_HOST: SMTP server for email notifications
SMTP_PORT: SMTP port
SMTP_USER: SMTP username
SMTP_PASS: SMTP password
EMAIL_FROM: Email address for sending notifications
Copyright and License
© 2025 1i1. All Rights Reserved. This software is proprietary and may not be reproduced, distributed, or used to create derivative works without explicit written permission from 1i1.

See the LICENSE file for complete copyright and proprietary rights information
