# Expo CLI Android Build Failure: AGP Version Mismatch

This repository demonstrates a common issue encountered when building Android apps using the Expo CLI: a mismatch in the Android Gradle Plugin (AGP) version.  This mismatch can lead to build failures and errors during the process.  This example shows how the issue arises and how to resolve it.

## Problem Description

The project is configured with an outdated or conflicting AGP version, causing incompatibilities with the Android SDK or dependent libraries. This often manifests as obscure error messages during the build process.

## Solution

The solution involves ensuring that all AGP versions involved are compatible. This may require updating the Expo project's configurations, modifying dependencies, or carefully managing AGP versions in different project modules.  The core approach is to find the conflicting version and upgrade/downgrade as needed to achieve compatibility.