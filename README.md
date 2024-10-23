# Secure Login Application

## Project Description

This is a Java-based desktop application that provides a secure login and registration system using Swing. It enables users to register with a unique username and password, log in to their accounts, and view their information upon successful authentication.

## Features

- **User Registration**: New users can sign up by entering a username and password.
- **User Login**: Existing users can log in with their registered credentials.
- **User Information Display**: After logging in, users can see their welcome message and registration number.

## Structure

- **Main Class**: The starting point of the application that initializes the login interface.
- **LoginFrame Class**: Handles the login process and user validation.
- **SignupFrame Class**: Manages user registration and checks for existing usernames.
- **UserManager Class**: Stores user credentials and handles registration and authentication logic.
- **UserInfoFrame Class**: Displays user-specific information post-login.

## Getting Started

1. **Clone the Repository**: Download or clone this project to your local machine.
2. **Set Up the Environment**: Ensure you have JDK 8 or later installed.
3. **Compile the Application**: Use an IDE such as IntelliJ IDEA or Eclipse to compile the project.
4. **Run the Application**: Execute the `Main` class to launch the application.

## System Requirements

- **Java JDK**: Version 8 or higher is required.
- **GIF Resource**: Make sure the `resources` directory contains the necessary GIF for the UI.

## User Credentials

- **Registration Number (also used as a password)**: `h230766g`
- **Username**: You can choose any unique username during the registration process.

## Author Information

- **Name**: Rufaro

## Important Notes

- The application currently stores user data in memory, meaning any registered users will be lost when the application closes.
- For production use, consider implementing a more secure way to handle passwords and user data, such as encryption and a database system. This example serves as a basic demonstration of user authentication principles
