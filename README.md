Flutter Project README
Project Overview
This Flutter project is a mobile application designed to showcase various features including authentication with Firebase, dynamic data fetching using APIs, and navigation between different screens. It is structured to provide a seamless user experience with a clean and intuitive interface.

Key Features Implemented
Authentication with Firebase
The project integrates Firebase Authentication to allow users to sign in using their Google accounts. Upon successful authentication, users are redirected to the home screen where they can explore different functionalities.

Dynamic Category and Product Display
The home screen (HomeUi) fetches categories and products dynamically from APIs using FetchListOfCategory and FetchProduct controllers. Categories are displayed horizontally, while products are shown in a grid format. Tapping on a product navigates to its detailed view (ProductDetailUi).

Profile Management
The ProfileUi screen displays user information retrieved from Firebase Authentication, including username and email. It also includes a logout button that signs the user out and clears the stored user session.

Navigation with GetX
Navigation throughout the application is managed using the GetX package, providing a simple and efficient state management solution along with route management.

Setting Up the Project
Follow these steps to set up and run the Flutter project on your local development environment:

Prerequisites
Install Flutter SDK. Flutter Installation Guide
Set up an IDE (e.g., Android Studio, Visual Studio Code) with Flutter and Dart plugins.
Getting Started
Clone the repository to your local machine:

bash
Copy code
git clone <repository-url>
Navigate to the project directory:

bash
Copy code
cd <project-directory>
Install dependencies:

bash
Copy code
flutter pub get
Set up Firebase for Authentication:

Create a new project on Firebase Console.
Add Android/iOS app to your Firebase project (follow Firebase documentation for detailed instructions).
Download google-services.json (for Android) or GoogleService-Info.plist (for iOS) and place it in the appropriate directory (android/app for Android, ios/Runner for iOS).
Run the app:

bash
Copy code
flutter run
Additional Notes
Customize the UI, colors, and themes in myUills.dart to match your app's branding.
Implement error handling and data validation based on your application requirements.
Ensure all necessary permissions and API keys (if applicable) are configured properly.
