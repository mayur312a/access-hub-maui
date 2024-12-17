# access-hub-maui

# SimpleAuthApp

## Overview
SimpleAuthApp is a basic cross-platform authentication app built using .NET MAUI. It demonstrates how to implement login functionality using:

1. **Email and Password Authentication**
2. **Google Login**
3. **Facebook Login**

This app is ideal for developers looking to learn the fundamentals of authentication in mobile applications.

---

## Features

### 1. Email and Password Authentication
- Users can log in with a sample username and password.
- Built-in validation ensures credentials are properly checked.

### 2. Google Login
- Implements Google OAuth for easy login with a Google account.
- Demonstrates the integration of third-party authentication providers.

### 3. Facebook Login
- Uses Facebook SDK to authenticate users via their Facebook accounts.

---

## Project Structure

```
/SimpleAuthApp
├── /Views
│   ├── LoginPage.xaml (UI for the login page)
│   ├── HomePage.xaml (UI for the home page after login)
├── /ViewModels
│   ├── LoginViewModel.cs (Handles login logic)
├── /Services
│   ├── AuthService.cs (Handles authentication for email/password, Google, and Facebook)
├── App.xaml (App initialization)
├── MainPage.xaml (Main entry point)
└── README.md
```

---

## Prerequisites

- Visual Studio 2022 with .NET MAUI workload installed.
- Google API credentials for OAuth integration.
- Facebook App ID for Facebook Login.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/simpleauthapp.git
cd simpleauthapp
```

### 2. Configure Google Login
- Go to the [Google Cloud Console](https://console.cloud.google.com/).
- Create a new project and configure OAuth credentials.
- Download the `google-services.json` file and add it to the Android project.

### 3. Configure Facebook Login
- Visit [Facebook Developers](https://developers.facebook.com/).
- Set up a new app and retrieve the App ID.
- Add the Facebook SDK to the project.

### 4. Run the App
- Open the project in Rider.
- Build and run the app on Android or iOS.

---

## How to Use

### Login with Username/Password
1. Enter the following credentials:
   - **Username**: ``
   - **Password**: ``
2. Tap on the "Login" button.

### Login with Google
1. Tap on the "Login with Google" button.
2. Follow the Google account selection process.

### Login with Facebook
1. Tap on the "Login with Facebook" button.
2. Log in using your Facebook credentials.

---

## Screenshots

### Login Page



### Home Page


---

## Future Enhancements
- Add password recovery functionality.
- Implement JWT token-based authentication.
- Support for Apple Login.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author
Developed by **Mayur Deshpande**.
