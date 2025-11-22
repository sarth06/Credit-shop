# Credit Shop Manager (Firestore version)

This project stores customer records in Firebase Firestore (no authentication).
It's beginner-friendly and free with Firebase's Spark plan.

Setup steps:
1. In Firebase Console -> Build -> Firestore Database -> Create database.
   - Start in **Test mode** for initial testing.
2. Ensure your project config (firebaseConfig) matches the one in index.html.
3. Open index.html in a browser (hosting recommended for cross-device).

Important security note:
- Test mode opens your DB for anyone; for production, secure Firestore rules appropriately.
