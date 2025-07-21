# Task5
flutter
 Flutter Screens (home - Login - OTP)

This Flutter project includes three main authentication screens for logging in using a phone number, with a simple and clean UI.
✅ Screens:
1. home Screen

    A welcoming screen.
    Contains a "Let's Get Started" button.
    Navigates the user to the Login screen.

Navigator.pushNamed(context, '/login');

2. Login Screen

    Input for phone number and password.
    Login button that navigates to the OTP screen.
    Link to navigate to the Sign Up screen.

Navigator.pushNamed(context, '/otp');

3. OTP Screen (Verification)

    Input for the verification code sent to the phone.
    Displays the entered phone number.
    Can be extended to send/verify OTP using Firebase or another provider.

Files:

    home_screen.dart
    login_screen.dart
    otp_screen.dart

 Navigation Between Screens:

routes: {
  '/': (context) => const HomeScreen(),
  '/login': (context) => const LoginScreen(),
  '/otp': (context) => const OTPScreen(),
  '/signup': (context) => const SignUpScreen(),
}

 Future Notes:

    Integra![WhatsApp Image 2025-07-21 at 05 12 49_b3d8b799](https://github.com/user-attachments/assets/f1cf3185-1ffc-48d3-81b3-600ada2589c6)
te Firebase Authentication.
    Add phone number validation.

 ![WhatsApp Image 2025-07-21 at 05 12 49_b3d8b799](https://github.com/user-attachments/assets/a5a486ab-7ccd-413f-adeb-2caf53d9e89f)

![WhatsApp Image 2025-07-21 at 05 11 30_ad30bf85](https://github.com/user-attachments/assets/e81d312c-6fff-4fe0-b0c3-51151ebe29f5)
![WhatsApp Image 2025-07-21 at 05 10 57_67147bf1](https://github.com/user-attachments/assets/52e3ffa5-8aeb-4054-86fa-b8dfd2812500)
