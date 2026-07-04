# AndroidAppTemplate
Standard barebones app template for creating Jetpack Compose apps with Kotlin.

## Note for Termux/Linux ARM users:
If using the Gradle build system, ensure that you have set the `android.aapt2FromMavenOverride`
to a path leading to your own ARM AAPT2 binary as Gradle downloads and attempts to use an x86 binary
regardless of system architecture.
