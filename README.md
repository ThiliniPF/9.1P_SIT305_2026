# 9.1P_SIT305_2026
This Android App, developed in Android Studio, helps users report, search and manage lost and found items efficiently through a simple and user-friendly interface.

Developed for SIT305 assessment by Thilini Fonseka

## Lost and Found App
The Lost and Found app is designed to connect lost items with their rightful owners using location-based technology and item management.

### Technology used
1. Java
2. Android Studio
3. XML
4. SQLite Database
5. Goggle Maps API
6. Android Location Services (GPS and Geocoder)

### App Features
1. Create a lost or found item advert
2. Upload an image of the item
3. Enter details about the applicant and 
4. View all posted adverts
5. Filter adverts based on category
6. Delete adverts
7. Display all adverts on Google Maps using markers
8. Radius based search only showing nearby lost/found items within a radius (5km)
9. Capture current GPS location of the user

### Data Persistence
1. Stored all event data locally SQLite Database
2. Data remains saved after app closure
3. GPS location retrieved using _FusedLocationProviderClient_
4. Distance between user and items is calculated using Android Location API

### Validation and Error Handling
1. Prevents empty data entry fields
2. Displays Toasts messages
3. Validated location data before storing
4. Handles null GPS locations safely in map view

## How to run the app
1. Clone the repository
   https://github.com/ThiliniPF/9.1P_SIT305_2026.git
2. Open the project in Android Studio
3. Allow Gradle to sync
4. Update Google Maps API key (if required)
5. Run the app using an emulator or a physical Android device
