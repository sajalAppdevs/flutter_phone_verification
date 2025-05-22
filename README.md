# Flutter Phone Verification

A Flutter application demonstrating phone number verification using Firebase Authentication. This app provides a simple and secure way to implement phone number verification with OTP (One-Time Password) in your Flutter projects.

## Features

- Phone number input with country code selection
- Firebase OTP verification
- Clean and intuitive user interface
- Error handling and validation
- Secure authentication flow

## Screenshots

<p float="left">
<img src="https://user-images.githubusercontent.com/12158468/116766599-267f1b00-aa4d-11eb-91ac-9e630ffc2019.jpg" alt="Phone Input Screen" width="200"/>
<img src="https://user-images.githubusercontent.com/12158468/116766643-61814e80-aa4d-11eb-95bd-314ad659bac5.jpg" alt="OTP Verification Screen" width="200"/>
<img src="https://user-images.githubusercontent.com/12158468/116766647-6514d580-aa4d-11eb-8abb-7db3f8ee6652.jpg" alt="Success Screen" width="200"/>
</p>

## Prerequisites

Before you begin, ensure you have:

- Flutter SDK installed on your machine
- Firebase project created in Firebase Console
- Android Studio/VS Code with Flutter plugins

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/flutter_phone_verification.git
   cd flutter_phone_verification
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Configure Firebase:
   - Create a new Firebase project in the Firebase Console
   - Add Android and iOS apps to your Firebase project
   - Download and add the configuration files:
     - Android: `google-services.json` to `android/app`
     - iOS: `GoogleService-Info.plist` to `ios/Runner`

4. Enable Phone Authentication in Firebase Console:
   - Go to Authentication > Sign-in methods
   - Enable Phone Number sign-in

5. Run the app:
   ```bash
   flutter run
   ```

## Configuration

Ensure your app's Firebase configuration is properly set up in:
- Android: `android/app/build.gradle`
- iOS: `ios/Runner/Info.plist`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Firebase Authentication
- Flutter Framework
- Contributors and maintainers
