# experiment12_HTTPrequest

# Access Web Services Using HTTP Requests in Android

## Aim
To develop an Android application using Kotlin that accesses web services through HTTP GET requests and retrieves data from an online server.

## Technologies Used
- Android Studio
- Kotlin
- XML
- HTTPURLConnection
- JSON

## Software Requirements
- Android Studio
- Android Emulator or Android Mobile
- Internet Connection
- Online REST API

## Project Description
This application accesses an online web service using HTTP GET requests. It retrieves user information from a server in JSON format and displays the response on the Android screen.

## API Details
- API URL: https://jsonplaceholder.typicode.com/users
- Request Method: GET
- Response Format: JSON

## Project Structure
```text
HTTPRequests/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/httprequest/
│           │   └── MainActivity.kt
│           ├── res/layout/
│           │   └── activity_main.xml
│           └── AndroidManifest.xml
└── README.md
```

## Implementation Steps
1. Create a new project in Android Studio.
2. Select Empty Views Activity.
3. Choose Kotlin as the programming language.
4. Add Internet permission in AndroidManifest.xml.
5. Design the user interface using XML.
6. Add a button to fetch data.
7. Use HttpURLConnection to establish a connection with the server.
8. Send an HTTP GET request.
9. Receive the response from the server.
10. Display the retrieved data in a TextView.
11. Run the application.

## Working Principle
The application sends an HTTP GET request to an online server using HttpURLConnection. The server processes the request and returns user information in JSON format. The response is displayed on the application screen.

## Expected Output
A Fetch Data button is displayed. When the user clicks the button, user details are retrieved from the online server and displayed on the screen.

## Result
Successfully developed an Android application to access web services using HTTP GET requests in Kotlin.
