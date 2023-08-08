# MapSearch
This project showcases iOS 17 MapKit New Features and it is Written in SwiftUI.

## 📱 Demo Video

https://github.com/ceciliachenguo/MapSearch/assets/121702916/a0ec049a-4253-4742-831c-d22ad2aed1ac

## 🌟 Features
### 1. Customizable Map Display
   - **Navigation**: Navigate to a predefined region using `cameraPosition`.
   - **Controls Overlay**: Provides additional map controls like the compass, user location button, and pitch button.
   - **Zoom Feature**: Ability to zoom into a selected route.
   - **Search Result Markers**: Dynamically displays markers for the search results.

### 2. Search Capability
   - **Search Bar**: Enables users to search for places.
   - **Results on Map**: Displays search results as distinct markers on the map.
   - **Detail Sheet**: Provides a 'Details' sheet which gives information about a selected location.
   - **LookAround Preview**: Offers a LookAround preview for a selected map item (if available) with an option to fetch directions.

### 3. Dynamic Route Display
   - **Route Request**: Users can request a route to their selected location.
   - **Route Visualization**: The route gets visualized on the map using a green polyline.
   - **End Route Button**: A convenient button to end the displayed route and return to the default view.

### 4. Interactive UI
   - **Snappy Animations**: Features dynamic UI changes with snappy animations.
   - **Search Exit**: Automatically clears out search results when exiting the search mode.
   - **End Route UI**: Provides a button to end the displayed route, changing the map to display the entire route.

### 5. Async Functions for Efficient Data Fetch
   - **Async/Await Pattern**: Uses Swift's new async/await pattern to fetch data efficiently without blocking the UI.
