MatCommand Team v36

For quick desktop testing:
1. Open OPEN_APP_HERE.html or run launch.bat.
2. The actual app files live inside /www because this package is Capacitor-ready.

For Android/Capacitor:
1. Open Command Prompt in this folder.
2. npm install
3. npx cap add android
4. npx cap sync android
5. npx cap open android

Important:
Do not move files out of /www for Capacitor. Capacitor expects the web app there.
