THE ROOTS ACADEMY - build the Android APK

Install first (free): Node.js LTS (nodejs.org) and Android Studio (developer.android.com/studio).

1. Open a terminal in this folder and run:   npm install
2. Then run:                                  npx cap add android
3. Then run:                                  npx cap open android
4. In Android Studio wait for Gradle to finish, then:
   Build > Build Bundle(s) / APK(s) > Build APK(s)
5. Click "locate" in the pop-up. The file is app-debug.apk
   (android/app/build/outputs/apk/debug/app-debug.apk).
6. Copy it to your phone, allow "Install unknown apps", and install.

After you change www/index.html later, run:   npm run sync
then build the APK again.

Export: tapping an export button opens the phone's share sheet.
Choose Drive, Files or Sheets to save the Excel file.
