# Lab0 - Flutter Environment Setup

**Student**: Mvone Obaing Yoctan Darlyn  
**Student ID**: 23047-2023  
**Course**: Advanced Mobile Application Development - Flutter

A Flutter project demonstrating proper environment setup and project initialization for Lab0.

## Project Overview

This project is created as part of Lab0 to verify Flutter development environment configuration and basic Flutter application structure setup. It includes a functional counter application with full multi-platform support and comprehensive testing setup.

## Features

- Multi-platform support (Android, iOS, Web, Windows, Linux, macOS)
- Flutter 3.41.1 SDK with Dart 3.11.0
- Material Design UI with counter application demonstrating state management
- Comprehensive widget testing with sample unit tests
- Linter configuration with flutter_lints for code quality
- Proper project structure following Flutter best practices

## Project Structure

```
lib/
  main.dart       # Main application entry point
test/
  widget_test.dart # Widget tests
```

## Getting Started

### Prerequisites

- Flutter SDK 3.11.0 or higher
- Dart SDK (included with Flutter)
- Android Studio / Xcode (for native development)

### Running the App

```bash
flutter pub get
flutter run
```

### Running Tests

```bash
flutter test
```

### Code Analysis

```bash
flutter analyze
```

## Troubleshooting

If you encounter any issues:

1. **Memory issues during build**: Clear cache with `flutter clean`
2. **Dependency issues**: Run `flutter pub get` again
3. **Platform-specific issues**: Check the platform-specific requirements in flutter.dev

## Submission

This project is submitted as part of Lab0 assignment for Advanced Mobile Application Development - Flutter course.
