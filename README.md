# Expo Android Build Failure: Android Gradle Plugin Version Conflict

This repository demonstrates a common error encountered when building Android apps with Expo CLI. The problem stems from incompatibility between the Android Gradle Plugin (AGP) version and project dependencies, often related to missing or conflicting AndroidX libraries.  The error messages are typically cryptic, making debugging challenging.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to run `expo build:android`.
4. Observe the build failure and the unclear error messages related to missing classes or version mismatch.

## Solution

The solution provided in `bugSolution.js` demonstrates how to resolve the issue by carefully reviewing the `android/app/build.gradle` file to ensure proper configuration of Android Gradle Plugin version, and dependencies. It might also involve checking for correct AndroidX library inclusion and resolving any conflicts. Detailed steps are included in the `bugSolution.js` file. 

This example highlights the importance of carefully managing dependencies and ensuring that your project configuration is compatible with the Expo and Android build system.