Flutter Project README<br><br>
Project Overview<br><br>
This Flutter project is a mobile application designed to showcase various features including authentication with Firebase, dynamic data fetching using APIs, and navigation between different screens. It is structured to provide a seamless user experience with a clean and intuitive interface.<br><br>

Key Features Implemented<br><br>
Authentication with Firebase<br><br>
The project integrates Firebase Authentication to allow users to sign in using their Google accounts. Upon successful authentication, users are redirected to the home screen where they can explore different functionalities.<br><br>

Dynamic Category and Product Display<br><br>
The home screen (HomeUi) fetches categories and products dynamically from APIs using FetchListOfCategory and FetchProduct controllers. Categories are displayed horizontally, while products are shown in a grid format. Tapping on a product navigates to its detailed view (ProductDetailUi).<br><br>

Profile Management<br><br>
The ProfileUi screen displays user information retrieved from Firebase Authentication, including username and email. It also includes a logout button that signs the user out and clears the stored user session.<br><br>

Navigation with GetX<br><br>
Navigation throughout the application is managed using the GetX package, providing a simple and efficient state management solution along with route management.<br><br>

Setting Up the Project<br><br>
Prerequisites<br><br>
Install Flutter SDK. Flutter Installation Guide<br>
Set up an IDE (e.g., Android Studio, Visual Studio Code) with Flutter and Dart plugins.<br><br>
Getting Started<br><br>
Clone the repository to your local machine:<br>

git clone <repository-url><br>

Navigate to the project directory:<br>

bash<br>
cd <project-directory><br>

Install dependencies:<br>

bash<br>
flutter pub get<br>

Set up Firebase for Authentication:<br><br>

Create a new project on Firebase Console.<br>
Add Android/iOS app to your Firebase project (follow Firebase documentation for detailed instructions).<br>
Download google-services.json (for Android) or GoogleService-Info.plist (for iOS) and place it in the appropriate directory (android/app for Android, ios/Runner for iOS).<br><br>
Run the app:<br>

bash<br>

flutter run<br><br>


Additional Notes<br><br>

Customize the UI, colors, and themes in myUills.dart to match app's branding.<br>
Implementd error handling and data validation based on application requirements.<br>
