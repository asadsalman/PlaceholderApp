# PlaceholderApp
This is placeholder project for generating an APK that can be consumed by [Fladle](https://flank.github.io/flank/)

Android Library modules (`com.android.library`) do not need an app APK for running instrumentation tests. Firebase Test Lab (FTL), on the other hand, [requires a valid APK](https://firebase.google.com/docs/test-lab/android/command-line) to invoke tests, even though the APK will be unused. This project generates an app APK that Fladle can upload to FTL when testing library modules.
