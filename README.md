# BOUTIQA

<h2>Team Details</h2>
<b>Team Number: </b> <p>24AACR04</p>
<b>Senior Mentor:</b><p> </p>
<b>Junior Mentor:</b><p> Venkat Vamshi</p>
<b>Team Member 1:</b><p> Devulapally Yashwanth</p>
<b>Team Member 2:</b><p> Samuel Oommen</p>
<b>Team Member 3:</b><p> Vyshnavi</p>
<b>Team Member 4:</b><p> Vaishnavi</p>
<b>Team Member 5:</b><p> Veda Alluri</p>

## Table of Contents
- [Introduction](#introduction) <br>
- [Requirements](#requirements) <br>
- [How to use](#How-to-use) <br>
- [Preview](#previews)
- [Contribution](#contribution)

<h2>Introduction</h2>
<p> 
It is a clothing app that connects users and designers, on a single platform.Users can browse, save and shop outfits while maintaining personalised profiles, designers can showcase collections, engage with followers, and sell directly.The app simplifies fashion delivery and shopping, creating an interactive and seamless experience.
</p>


<h2>Requirements</h2>

<pre> 
  Package                          Version
------------------------------  ----------
flutter                          3.7.0
dart                             3.7.0
firebase_core                    2.15.0
firebase_auth                     3.7.0
cloud_firestore                   4.5.0
firebase_database                 9.1.0
firebase_storage                  11.1.0
firebase_messaging                11.0.0
flutter_local_notifications       9.2.0
provider                         6.0.0
http                              0.14.0
flutter_bloc                      8.0.1
equatable                         2.0.3
cached_network_image              3.2.3
flutter_svg                       1.0.0
image_picker                      0.8.6
url_launcher                      6.0.20
google_fonts                      3.0.1
device_info_plus                  8.0.0
intl                              0.18.0
shared_preferences                2.0.8
get                              4.6.5
sqflite                           2.0.0
dio                              5.0.0
bloc                              8.1.1
logger                            1.0.0
</pre>


<h2>How-to-use</h2>
<p>Follow these steps to run the Boutiqa project:</p>

<p>Clone the repository:</p>
<pre>
  <code>
  git clone https://github.com/AAC-Open-Source-Pool/BOUTIQA
  </code>
</pre>


<p> <a href = "https://flutter.dev/docs/get-started/install">Install Flutter :</a></p>
  <pre>
  https://flutter.dev/docs/get-started/install
  </pre>



<p>Install the required dependencies (Flutter packages):</p>
<pre>
  <code>
  flutter pub get
  </code>
</pre>

<p>Configure Firebase:</p>
<ul>
  <li>Go to <a href="https://console.firebase.google.com/">Firebase Console</a> and create a new project or use an existing one.</li>
  <li>Follow the instructions to add Firebase to your Flutter project:
    <ul>
      <li>Enable Firebase Authentication (for login functionality).</li>
      <li>Set up Firestore, Firebase Storage, or any other services your app needs.</li>
      <li>Download the <code>google-services.json</code> for Android and/or <code>GoogleService-Info.plist</code> for iOS, and place them in the appropriate directories of your project.</li>
    </ul>
  </li>
</ul>

<p>Run the Boutiqa app:</p>
<pre>
  <code>
  flutter run
  </code>
</pre>

<p>Ensure Firebase is properly initialized in your Flutter app. Add this code in <code>main.dart</code>:</p>
<pre>
  <code>
  void main() async {
    WidgetsFlutterBinding.ensureInitialized();
    await Firebase.initializeApp(
      options: DefaultFirebaseOptions.currentPlatform, // Replace with your Firebase config
    );
    runApp(BoutiqaApp());
  }
  </code>
</pre>

<p>Note:</p>
<ul>
  <li>If you're using Firebase Authentication, set up the login UI (such as Email/Password, Google Sign-In, etc.).</li>
  <li>Verify your <code>pubspec.yaml</code> file includes the required Firebase libraries like <code>firebase_auth</code>, <code>cloud_firestore</code>, etc.</li>
  <li>Make sure your emulator or physical device is connected to the internet for Firebase to work properly.</li>
</ul>
<h2>Preview</h2>
<div style="display: flex; align-items: center;">
  <img src="">
</div>

<h2>Contribution</h2>
<p>We welcome contributions to improve the Project <br>
To contribute, follow these steps:

1.⁠ ⁠Understand the Project Philosophy: Read through the README.md file to familiarize yourself with the project's goals and structure.

2.⁠ ⁠Maintain Code Consistency: Use the same programming language and library versions as the original code.

3.⁠ ⁠Write Documentation: Explain the changes you're proposing, including identified problems, proposed solutions, and test cases.

4.⁠ ⁠Submit a Pull Request: Follow standard Git etiquette for submitting your contributions.</p>
