# BENATA Android APK (loads the online app)

No installs needed. GitHub builds the APK for you.

1. Put the BENATA server online first (Render). Note its address, e.g. https://benata-xxxx.onrender.com
2. Create a new GitHub repository called benata-android and upload everything in this folder
   (keep the .github folder, it contains the build recipe).
3. In the repository, open app/build.gradle, click the pencil icon, and replace
   https://YOUR-BENATA-ADDRESS.onrender.com with your real address. Commit.
4. Open the Actions tab. The "Build APK" run starts by itself (or click Run workflow).
5. When it shows a green tick, open the run and download "benata-apk" at the bottom.
6. Unzip it, send app-debug.apk to a phone, open it and allow "install unknown apps".

This is a test APK. Play Store needs a signed bundle (see the Play Store guide).
