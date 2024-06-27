# BMI Calculator 💪

## Introduction

Welcome to the BMI Calculator! This application helps users calculate their Body Mass Index (BMI) in a fun and engaging way. The design is inspired by the beautiful work of Ruben Vaalt, providing a seamless and intuitive user experience. 

## Features

- **Multi-Screen App**: The app features a multi-screen interface, allowing users to navigate easily through different pages.
- **Custom Styling**: The app showcases beautiful and customized UI components.
- **Interactive Elements**: Users can interact with various elements, including input sliders and buttons.
- **Real-Time Calculation**: BMI is calculated in real-time as users adjust their inputs.

## Screens

![Finished App](https://github.com/londonappbrewery/Images/blob/master/bmi-calc-demo.gif)

### Calculator Page

- This page features input sliders for weight and height.
- Users can select their gender.
- A calculate button processes the inputs and displays the BMI result.

### Result Page

- Displays the calculated BMI.
- Provides a textual interpretation of the BMI (e.g., Underweight, Normal, Overweight, Obese).

## Technical Details

### Theming

- Utilizes Flutter themes to create a cohesive and branded user experience.
- Custom color palettes using hex codes.

### Navigation

- Implements multi-page navigation using Flutter Routes and Navigator.

### Widgets

- Extensive use of custom Flutter Widgets.
- GestureDetector Widget for detecting user interactions beyond basic taps.

### Code Architecture

- Refactored and modularized code for better maintainability.
- Composition over inheritance approach for building custom UI components.

### Performance

- Efficient state management ensuring smooth and responsive UI.

## Future Plans

- **Detailed Analysis**: Adding a feature for detailed analysis of BMI results over time.
- **User Authentication**: Implementing user authentication to save and retrieve user data.
- **Enhanced UI**: Further refinement of UI components for an even better user experience.

## Setting up the project in your local environment💻

1. Clone this repository.
2. After Cloning, open the project in android studio
3. Create a new project on [Firebase Console](https://console.firebase.google.com/)
4. Activate Email SignIn in Firebase auth, and activate Firebase Firestore and Firebase Storage in **test mode**.
5. Integrate firebase using the tutorial mentioned above to use your own database (Necessary step else the app wont work)
6. Run `flutter pub get` to get the dependencies.
7. Finally, run the app:

```
flutter run
```
7. To build the apk of the app, you can use the following command
```
flutter build apk --release
```
You can find the apk in build/app/outputs/flutter-apk folder
You can refer the following video for more [details](https://youtu.be/TOgfbyw6-Mw)

