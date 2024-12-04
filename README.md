# Expo Android Build Hang/Failure

This repository demonstrates a bug encountered when building an Android app using the Expo CLI. The build process hangs indefinitely or fails without providing a clear error message. The project builds successfully on iOS.

## Steps to Reproduce

1. Clone this repository.
2. Run `expo prebuild`.
3. Attempt to build the Android app using `expo build:android`. 

## Expected Behavior

The Android app should build successfully.

## Actual Behavior

The build process hangs or fails without a clear error message.

## Solution (expoBugSolution.js)

The solution involves updating the necessary Android configurations and dependencies. Refer to expoBugSolution.js for detailed steps.

## Note

The specific cause of this error can vary. This repository provides one example.  Additional troubleshooting may be required depending on the project's dependencies and configurations.