# Forever Special

Fresh Flutter Android project for the Forever Special app.

## Current first milestone
- Dark purple/pink Home Dashboard
- Navigation placeholders for Your Songs, Favorites, Wishes and Downloads
- Flutter project with Firebase packages prepared
- GitHub Actions workflow to build a debug APK

## Not connected yet
Google sign-in, Firestore, Firebase Storage, online music search, shared uploads and offline downloads need Firebase project configuration and implementation. This starter does not yet upload or play shared songs.

## Build
Push this repository to GitHub. Open Actions and run **Build Forever Special APK**. Download the `forever-special-debug-apk` artifact.

## Firebase setup required next
Create/configure a Firebase Android app with package ID `com.foreverspecial.birthday`, enable Google sign-in, and add the Android Firebase configuration. Then wire Firebase Auth, Firestore and Storage into the app.
