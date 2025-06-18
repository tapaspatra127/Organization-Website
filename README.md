# Organization-Website
A full-stack web application built with React and Firebase, designed to reward users with points for downloading and providing proof of Android app installations. This system features distinct user and admin interfaces, secure authentication, and real-time data management.
✨ Features
User Authentication: Secure sign-up and login powered by Firebase Authentication (Email/Password).
Admin Dashboard:
Add New Apps: Administrators can easily add new Android applications, including their name, download URL, description, and the points awarded for completing the task.
View All Apps: Admins can see a comprehensive list of all apps available in the system.
User Dashboard:
Personal Profile: Users can view their current points total and personal details.
Available Tasks: Users can browse a list of Android apps available for download to earn points.
Screenshot Submission: Users can submit screenshots as proof of app installation via a drag-and-drop interface, which are then uploaded to Firebase Storage.
Task Completion Tracking: Completed tasks are recorded, and points are automatically updated in real-time.
Responsive UI: Built with Tailwind CSS for a modern, mobile-friendly, and adaptive user experience across devices.
Real-time Data: Leverages Firestore's real-time capabilities for instant updates on app lists and user profiles.
🛠️ Technologies Used
Frontend:
React.js: A JavaScript library for building user interfaces.
Tailwind CSS: A utility-first CSS framework for rapid UI development.
Backend & Database:
Firebase Authentication: For user sign-up, login, and session management.
Firestore Database: A flexible, scalable NoSQL cloud database for storing app details and user profiles.
Firebase Storage: For securely storing user-submitted screenshots.
