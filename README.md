
#  Rushi Android App

This repository contains the source code for a simple Android application that displays a modern login screen UI. The user interface is built using XML, and the MainActivity.java file provides the basic setup for the app's entry point.

Note: As indicated in the source code, this is a non-functional UI only. The app displays the login layout but does not contain any logic to handle user input, button clicks, or form validation.

---

## Project Structure

```
rushi/
├── build.gradle.kts        # Project-level build script
├── gradle.properties       # Gradle configuration
├── settings.gradle.kts     # Module settings
├── gradlew / gradlew.bat   # Gradle wrapper
├── .gradle/                # Gradle cache (auto-generated)
├── src/                    # Source code (currently empty or not uploaded)
```

---
## Features
The user interface includes the following elements, defined in activity_main.xml:

A main heading "Log in to your account".

An email input field with an icon.

A password input field with a password toggle icon.

A "Forgot Password" link.

A primary "Login" button.

A horizontal divider with the text "or".

A button to "Continue with Google" with a Google icon.

A "Don't have an account?" link with a "Sign Up" option.

Technology Stack
Language: Java

Layout: Android XML

UI Components: androidx.appcompat, com.google.android.material


---

##  Getting Started

### Prerequisites

- Android Studio Flamingo or newer
- Android SDK 33+
- Kotlin 1.9+
- Gradle 8.x

### Clone and Build

```bash
git clone <repo-url>
cd rushi
./gradlew build
```

Or open the project in **Android Studio** directly.

Ensure your project dependencies are correctly configured in build.gradle (if not, Android Studio will prompt you).

---

## Configuration

You can configure local settings via the `local.properties` file:

```properties
sdk.dir=/path/to/your/Android/sdk
```

---


