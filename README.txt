AI Stock Signal Android project (demo wrapper)

This is an Android Studio project that wraps the included HTML prototype in a WebView. It is source code, NOT a compiled APK.

IMPORTANT: The app currently uses simulated stock prices and illustrative BUY/SELL/WAIT rules. It is not connected to live NSE/BSE data, has not been validated for profitability, and does not place trades.

Build an APK:
1. Install Android Studio on a computer.
2. Open this folder (AIStockSignalAndroid) in Android Studio.
3. Allow Gradle sync and install any requested Android SDK components (compile SDK 35).
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the debug APK at app/build/outputs/apk/debug/app-debug.apk.
6. Transfer it to your Android phone and install it. Android may ask you to allow installation from that source.

No API keys or broker credentials are included. Live NSE/BSE prices require a licensed provider and a secure backend; do not put secret API keys in the app.
