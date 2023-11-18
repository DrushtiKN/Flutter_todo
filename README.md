**CROSS PLATFORM APPLICATION DEVELOPMENT**
Flutter App with Back4App Integration
Overview
This repository contains the source code for a Flutter application integrated with Back4App for backend services. The application is designed for task management, enabling users to create, view, edit, and delete tasks.

**Description**: The assignment involves creating a Flutter app that connects to the Back4App Backend-as-a-Service (BaaS) platform to manage tasks. The key steps include setting up the Back4App backend, creating the Flutter app, and implementing necessary functionalities to interact with the backend​​.

**Features**
Task Management: Users can create, view, edit, and delete tasks.
Task Details: Each task includes a title and description. Additional details like due dates and priorities can be added and edited​​.
Real-Time Updates: The app supports real-time data update across all connected clients using Back4App's real-time database functionalities​​.
Cross-Platform Compatibility: Built with Flutter, the app is compatible with iOS, Android, web, and desktop platforms​​.

**Prerequisites**
An account on Back4App.
Flutter (version 2.2.x or later).
Android Studio or VS Code with Dart and Flutter plugins installed​​.

Set Up and Run
Back4App Setup: Sign up and create a new app on Back4App. Define a class named Task with columns for title and description​​.
Flutter Setup: Create a new Flutter project and add the necessary dependencies for Parse in the pubspec.yaml file​​.
Running the App: Navigate to the project directory and use flutter run to start the application​​.

**Additional Information**
Import Statements: The app uses various Dart and Flutter libraries for functionality such as asynchronous programming and material design UI components​​.
Main Function: The main function initializes Flutter and the Parse SDK, setting up the necessary environment for the app​​.
Task List and Operations: FutureBuilder is used for fetching and displaying tasks, and ParseObject for CRUD operations on the server​​.

Bonus Features
Edit and Update Tasks: Ability to modify existing tasks including their completion status.
Task Deletion: Functionality to remove tasks from the list.


**Setup Instructions**
For detailed setup instructions, refer to the steps outlined in this document.

Contribution
Feel free to fork the repository and submit pull requests with enhancements or fixes.
