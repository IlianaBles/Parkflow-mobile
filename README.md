🚗 PARKFLOW: Parking Management Mobile App
Real-Time Availability & Duration Tracking for Sta. Lucia East Grand Mall


📌 About the Project
PARKFLOW is a mobile application designed to help drivers find available parking slots and track parking durations in real-time. The app integrates sensor-based monitoring and a 2D digital map for efficient parking management.

🔧 Tech Stack
Programming Language: Kotlin / Java
Backend: Flask (Python)
Database: Firebase Realtime Database
Cloud Storage: Firebase Storage
Real-Time Updates: Socket.IO
Hardware Integration: Arduino (for sensor data)
📲 Features
✅ View available parking slots in real-time
✅ Navigate parking facilities with a 2D digital map
✅ Track parking duration & automate fee calculations
✅ Digital ticketing system for easy entry/exit
✅ Parking history for users & lot owners

🚀 Installation Guide
1. Clone the Repository
git clone (https://github.com/IlianaBles/Parkflow-mobile).git
cd parkflow-mobile

3. Open in Android Studio
Make sure you have Android Studio installed.
Open the project and sync Gradle.

5. Configure Firebase
Add your google-services.json file in the app/ folder.
Ensure Firebase Authentication & Realtime Database are enabled.

7. Run the App
Connect an Android device or use an emulator.
Click Run ▶️ in Android Studio.

🔗 Backend API Endpoints
The app communicates with the Flask backend. API endpoints include:

Endpoint	Method	Description
/get_parking_slots	GET	Fetch all available slots
/update_slot_status	POST	Update slot occupancy
/get_parking_duration	GET	Retrieve parked time


🤝 Contributors
Trisha Iliana Bles Raya 
