# Daymark Android project
The included GitHub Actions workflow builds a debug APK on every push to `main`, or manually from the Actions tab.
Download the `Daymark-APK` artifact and extract `app-debug.apk`.
The app loads `app/src/main/assets/index.html`; JavaScript and DOM storage are enabled for Daymark local task storage.
