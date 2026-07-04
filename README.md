# AndroidAppTemplate
Standard barebones app template for creating Jetpack Compose apps with Kotlin.

## Note for Termux/Linux ARM users:
If using the Gradle build system, ensure that you have set the `android.aapt2FromMavenOverride`
to a path leading to your own ARM AAPT2 binary as Gradle downloads and attempts to use an x86 binary
regardless of system architecture.

## Features
* Modular:
  MainScreen.kt is only an entry point. App screens go in `com.application.myapplicatin/ui/screens` and
  screen components go in `com.application.myapplication/ui/components`.
* Kotlin Based:
  Set up for Kotlin and Jetpack Compose by default.

  ## Changing the app package name and package structure
  To change the template package name, you will modify  the app-level `build.gradle.kts`
  parameters to your desired package name as seen in the image below.
  ![Package Name Changing](packagename.jpeg)
