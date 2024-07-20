# Battery Level Tutorial

This repository contains the source code for the tutorial on how to use Platform Channels in Flutter to get the battery level of a device. The full tutorial can be found in the article [How to Use Platform Channels in Flutter](https://harishkunchala.com/how-to-use-platform-channels-in-flutter).

## Overview

In this tutorial, you will learn how to:
- Understand what Platform Channels are and their importance in Flutter development.
- Implement Platform Channels to communicate between Flutter and native code.
- Retrieve the battery level from both Android and iOS devices using custom platform-specific code.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Flutter SDK
- Android Studio or Xcode
- A basic understanding of Flutter and Dart

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/khkred/battery_level_tutorial.git
    cd battery_level_tutorial
    ```

2. Install the dependencies:
    ```bash
    flutter pub get
    ```

3. Run the app:
    ```bash
    flutter run
    ```

## Project Structure

The project is structured as follows:
- `lib/`: Contains the main Flutter code.
  - `main.dart`: The entry point of the Flutter application.
- `android/`: Contains the Android-specific code.
  - `MainActivity.kt`: Implements the platform channel for Android.
- `ios/`: Contains the iOS-specific code.
  - `AppDelegate.swift`: Implements the platform channel for iOS.

## Platform Channel Implementation

### Android

In `MainActivity.kt`, the battery level is retrieved using the `BatteryManager` class.

### iOS

In `AppDelegate.swift`, the battery level is retrieved using the `UIDevice` class.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, feel free to reach out via the comments section of the article or open an issue on this repository.