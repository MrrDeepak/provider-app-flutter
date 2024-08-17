# Provider App

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Intro
Welcome to the Provider App! This Flutter project showcases how to use the provider package for state management. The app allows users to add and delete items while ensuring efficient state management without rebuilding the entire application.

# Features
* State Management with Provider: Demonstrates how to manage state efficiently using the provider package.
* Add Item: Users can add new items to the list.
* Delete Item: Users can remove items from the list.
* Efficient UI Updates: Only parts of the UI affected by state changes are rebuilt, improving performance and user experience.

# Getting Started
To get started with the Provider App, follow these steps:

## Prerequisites
Ensure you have the following installed:

* Flutter SDK: Installation Guide
* Dart SDK: Included with Flutter SDK
* An IDE such as Visual Studio Code or Android Studio

#Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/provider-app-flutter.git
```
2. Navigate to the Flutter project directory:
```
cd provider-app-flutter
```
3. Install dependencies:
```
flutter pub get
```
4. Run the application:
```
flutter run
```
This will launch the app on your connected device or emulator.

# Using Provider for State Management
The app uses the provider package to manage the state of the items list. Here’s a brief overview of how it works:
1. Provider Setup: The ChangeNotifierProvider is used to provide an instance of the state class (ItemProvider) to the widget tree.
2. State Class: The ItemProvider class extends ChangeNotifier and contains methods to add and delete items.
3. Consumer Widget: The Consumer widget listens to changes in the ItemProvider and rebuilds only the parts of the UI that are affected by the state changes.

# License
This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

# Screenshots
![Screenshot 2024-08-17 131121](https://github.com/user-attachments/assets/cc462911-1125-4081-9168-6d234f46d25e)
![Screenshot 2024-08-17 131157](https://github.com/user-attachments/assets/f8866e00-d4e6-4e80-9c4a-0fdaba40e314)





