# KEngine Mobile

Android-first landscape 3D editor prototype with a native Vulkan viewport, procedural sky and grid shaders, and touch-friendly editor panels.

## Status

This is an early prototype, not a complete Vulkan 1.3 engine. Swapchain recreation, depth buffering, full camera matrices, Vulkan 1.3 feature negotiation, and an editable scene graph remain follow-up work. Vulkan 1.3 support depends on the Android device and GPU driver.

## Build requirements

- JDK 17
- Android SDK platform 35 and Build Tools 35
- Android NDK 27.2.12479018
- CMake 3.22.1
- Gradle 8.9
- glslc shader compiler

The intended GitHub Actions workflow builds app/build/outputs/apk/debug/app-debug.apk and uploads it as a KEngine-debug-apk artifact.