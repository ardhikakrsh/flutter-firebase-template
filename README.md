# flutter_firebase_template

A new Flutter project.

## How to use

1. Clone this repository
2. `npm install -g firebase-tools`
3. `firebase login`
4. Create firebase project
   - Go to the Firebase Console.
   - Click on "Add project"
   - Select default account for firebase
5. Setup Firebase Auth
   - Go to authentication
   - Click get started
   - Select email/password method
   - Enable email/password
6. `flutter pub global activate flutterfire_cli`
7. `flutterfire configure`

   - Select your project that you've been create before in firebase
   - Select platforms you needed

8. `flutter pub add firebase_core`
9. `flutter pub add firebase_auth`
