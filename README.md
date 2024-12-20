# Android Banking Application

This is a simple banking application for Android built with Java. It features user registration, financial data entry, and local data storage using SQLite. The application allows users to manage income, expenses, and card information effectively.

## Features

- **User Registration and Login**: 
  - Create a new account with email and password.
  - Prevents duplicate account registration.

- **Financial Management**:
  - Input and manage financial details including income, expenses, bills, and miscellaneous costs.
  - Real-time calculations for remaining balance after expenses.

- **Card Information**:
  - Supports input of card numbers with formatted validation.
  - Displays formatted card number and account details dynamically.

- **Local Data Storage**:
  - Stores user data, income, and expenses in a local SQLite database.
  - Saves a backup of user details in a `.txt` file on external storage.

## Technologies Used

- **Java**: Core language for Android development.
- **Android SDK**: To design layouts and manage Android-specific features.
- **SQLite**: For storing user and financial data locally.
- **TextWatcher and InputFilter**: For input validation and dynamic formatting.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/houssemft/Android-Banking-Application
2.Open the project in Android Studio.

3.Build and run the app on an emulator or a physical device.

4.Grant the app storage permissions to allow file saving.
