## Landmark Explorer
Landmark Explorer is an Android application that allows users to discover nearby landmarks, view their current location on a map, and get directions to selected landmarks. The app utilizes Firebase for authentication and Google Maps for displaying landmarks and navigation.

## Features
- User registration and login using Firebase Authentication
- View nearby landmarks on an embedded Google Map
- Display the user's current position on the map
- Select a landmark to get directions
- Calculate the best route between the user's location and the selected landmark
- Display estimated time and distance to the destination
- Visual representation of the route on the map

## Technologies Used
- **Android**: Development platform for the mobile app
- **Kotlin**: Programming language used for app development
- **Firebase Authentication**: For user authentication and management
- **Google Maps SDK**: For displaying maps and locations
- **Retrofit**: For making network requests to web services
---
## Getting Started
---
### Prerequisites
- Android Studio installed on your machine
- A valid Google Maps API key
- Firebase project set up for authentication
---
### Installation
1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/landmark-explorer.git
   cd landmark-explorer
2. Open the project in Android Studio.
3. Update the AndroidManifest.xml with your Google Maps API key:
    Copy code
      <meta-data
        android:name="com.google.android.geo.API_KEY"
        android:value="YOUR_API_KEY_HERE" />
4. Sync the Gradle files to install dependencies.
5. Run the app on an emulator or physical device.
---
## Usage
1. Launch the app and register or log in using your credentials.
2. Allow location permissions to view your current position on the map.
3. Explore nearby landmarks and select one to view directions.
4. Follow the displayed route to reach your destination.
 ---  
## Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.
---
## Acknowledgments
- Google Maps SDK
- Firebase Authentication
- Retrofit Library

