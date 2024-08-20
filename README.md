# MusicApp-UI

## Overview

MusicApp-UI is a music application built with Jetpack Compose for Android. This app features a modern UI with bottom and drawer navigation, allowing users to explore music content such as home, library, browse, and manage their account.

## Features

- **Bottom Navigation:** Easily switch between Home, Library, and Browse screens.
- **Drawer Navigation:** Access Account settings, Subscription details, and Add Account features.
- **Dynamic UI:** The user interface adapts dynamically based on navigation and user interactions.
- **State Management:** Manages the current screen and navigation state using ViewModel.

## Architecture

- **MainActivity:** The entry point of the application, setting up the UI using Jetpack Compose.
- **MainViewModel:** Manages the current screen state and handles navigation logic.
- **Screen:** Defines various screens for both bottom and drawer navigation, including titles, routes, and icons.
- **Lib:** Represents library items with corresponding icons and names.

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Milind-Ranjan/MusicApp-UI.git
2. Navigate to the project directory:
   ```bash
   cd MusicApp-UI
3.	Open the project in Android Studio:
	•	Import the project as a Gradle project.
4.	Build and run the application:
	•	Ensure that you have an Android emulator or a physical device connected.
	•	Click on the “Run” button in Android Studio.

## Dependencies
- Jetpack Compose
	- AndroidX libraries
	- Material3
	- Kotlin

## Code Explanation
- MainActivity.kt: Sets the content view using setContent and applies the MusicAppUITheme to wrap the MainView.
	- MainViewModel.kt: Provides state management for the current screen. Uses MutableState to update and observe screen changes.
	- Screen.kt: Defines screen configurations for bottom and drawer navigation, including titles, routes, and icons.
	- Lib.kt: Contains a data class for library items, used to represent different sections in the library.

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes. For any discussions, please reach out through the project’s issue tracker.

## Contact
- Created by: Milind Ranjan
	- Email: milindranjan1511@gmail.com
