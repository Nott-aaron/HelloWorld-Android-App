# 📱 Experiment 1: Hello World Android Application

## Student Details

- **Name:** Spencer Fernandes
- **USN:** 25MCAR0123
- **Course:** Master of Computer Applications (MCA)
- **Subject:** Mobile Application Development
- **Experiment No.:** 1

---

# Aim

To develop and execute a simple Android application that displays the message **"Hello World!"** along with the student's name and USN using Android Studio and Kotlin.

---

# Objective

- To understand the Android Studio development environment.
- To learn the structure of an Android project.
- To create and execute a basic Android application.
- To understand the role of Activities and Jetpack Compose in Android application development.

---

# Concept / Technology

### Android Studio
Android Studio is the official Integrated Development Environment (IDE) developed by Google for Android application development. It provides tools for coding, debugging, testing, and deploying Android applications.

### Kotlin
Kotlin is Google's officially recommended programming language for Android development. It is modern, concise, and interoperable with Java.

### Jetpack Compose
Jetpack Compose is Android's modern UI toolkit for building native user interfaces using Kotlin code instead of XML layouts.

### Activity
An Activity represents a single screen in an Android application. Every Android application starts execution from the `MainActivity`.

---

# Scenario

A student wants to verify that Android Studio, the Android SDK, and the Android Emulator are installed and configured correctly. A simple "Hello World" application is created to ensure the Android development environment is working properly. The application also displays the student's name and USN for identification.

---

# Software Requirements

- Android Studio
- Kotlin
- Android SDK
- Android Emulator (Pixel 8)
- Windows 10/11

---

# Procedure

1. Install Android Studio.
2. Create a new project using the **Empty Activity** template.
3. Select **Kotlin** as the programming language.
4. Write the application code.
5. Create an Android Virtual Device (AVD).
6. Run the application on the emulator.
7. Verify that the application displays the required information.

---

# Folder Structure

```
HelloWorld/
│
├── app/
│   ├── manifests/
│   │     └── AndroidManifest.xml
│   │
│   ├── java/
│   │     └── com.example.helloworld
│   │           └── MainActivity.kt
│   │
│   ├── res/
│   │     ├── drawable/
│   │     ├── mipmap/
│   │     ├── values/
│   │     └── xml/
│   │
│   └── build.gradle.kts
│
├── gradle/
├── settings.gradle.kts
├── build.gradle.kts
├── gradlew
├── gradlew.bat
└── README.md
```

---

# Project Output

The application displays the following information on the emulator:

```
Hello World!

Spencer Fernandes

25MCAR0123
```

### Screenshot

Add your output screenshot here.

Example:

```
![Output](screenshots/output.png)
```

---

# Test Cases

## Test Case 1

### Test Case ID
TC-01

### Objective
Verify that the application launches successfully.

### Steps
1. Open Android Studio.
2. Run the application.

### Expected Result
Application launches without any errors.

### Actual Result
Application launched successfully.

### Status
✅ Pass

**Screenshot**

```
![Test Case 1](screenshots/testcase1.png)
```

---

## Test Case 2

### Test Case ID
TC-02

### Objective
Verify that the application displays the "Hello World!" message.

### Steps
1. Launch the application.
2. Observe the screen.

### Expected Result
"Hello World!" should be displayed.

### Actual Result
The application displayed "Hello World!".

### Status
✅ Pass

**Screenshot**

```
![Test Case 2](screenshots/testcase2.png)
```

---

## Test Case 3 (Mandatory)

### Test Case ID
TC-03

### Objective
Verify that the application displays the student's Name and USN.

### Steps
1. Launch the application.
2. Observe the screen.

### Expected Result

```
Hello World!

Spencer Fernandes

25MCAR0123
```

should appear.

### Actual Result

Name and USN displayed successfully.

### Status
✅ Pass

**Screenshot**

```
![Test Case 3](screenshots/testcase3.png)
```

---

# Result

The Android application was successfully developed, executed, and tested using Android Studio and Kotlin. The application correctly displayed the Hello World message along with the student's name and USN.

---

# Conclusion

The experiment helped in understanding the Android Studio environment, Android project structure, Activities, Kotlin programming, and Jetpack Compose. The application executed successfully and met all the specified requirements.
