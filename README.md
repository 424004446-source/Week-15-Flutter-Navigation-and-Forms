# Week-15-Flutter-Navigation-and-Forms

# PC16 Week 15: Flutter Navigation and Forms

**Student Name:** Alquin Ferrer  
**Course:** PC16 - Mobile Development with Lab
**School:** National Teachers College  

## Overview
A two-screen Flutter laboratory activity demonstrating form input validation, named route navigation (`Navigator.pushNamed` and `Navigator.pop`), and passing route arguments between screens.

## Features
* **Registration Form Screen (`/`):** Collects Full Name and Email Address using `TextFormField` and `TextEditingController`.
* **Form Validation:** Uses `GlobalKey<FormState>` to block empty fields and malformed email addresses with specific error messages.
* **Confirmation Screen (`/confirmation`):** Receives and displays the submitted user details via route arguments, with a Back button returning to the form.

## How to Run
1. Clone this repository or download the project files.
2. Open the project folder in VS Code or Android Studio.
3. Run `flutter pub get` in the terminal to install dependencies.
4. Run `flutter run` to launch the app on a browser, emulator, or physical device.
