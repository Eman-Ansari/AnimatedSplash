# AnimatedSplash
# Android Splash Screen

A simple Android application that demonstrates the implementation of a splash screen with animations and text.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Android app displays a splash screen with animations and text to create an engaging introductory screen for your app. It demonstrates how to use XML layout and Java code to create a visually appealing splash screen.

## Features

- Displays a splash screen with an image and text.
- Uses animations to enhance the visual appeal.
- Demonstrates best practices for creating splash screens in Android apps.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Android Studio and an Android development environment set up.
- Basic knowledge of Android app development.

## Installation

1. Clone the repository to your local machine:
2. Open the project in Android Studio.
3. Build and run the app on your Android device or emulator.

## Usage

Upon launching the app, you will see the splash screen with the following elements:

- An image (`@drawable/splash`) displayed at the center of the screen.
- Text "DINE IN" with a custom font and styling.
- Subtitle text "Taste, Smile, Happy" with custom styling.

The splash screen is displayed for a defined duration (2500 milliseconds by default) before automatically transitioning to the next screen (e.g., the app's main activity).

## Customization

You can customize the splash screen by modifying the following elements:

- Image: Replace `@drawable/splash` with your desired image.
- Text: Change the text content, font, styling, and colors in the XML layout (`activity_main.xml`) as needed.
- Duration: Adjust the `SPLASH_SCREEN` variable in the Java code (`MainActivity.java`) to change the duration of the splash screen.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
