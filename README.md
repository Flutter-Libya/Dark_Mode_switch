# Flutter Theme Switcher

This project is a simple implementation of a theme switcher for a Flutter application. The application uses the Riverpod package for state management. 

## Overview

The application consists of:

1. **MyApp**: The main widget, wrapped with Riverpod's `ProviderScope` to provide state management across the app.
2. **MyHomePage**: A page with a row containing a text widget and a `DarkModeSwitch` widget for switching the theme.
3. **DarkModeSwitch**: A switch that toggles the theme of the app based on its state.
4. **AppThemeState**: A Riverpod change notifier provider that manages the theme state (dark mode enabled/disabled). It notifies its listeners whenever the theme changes.
5. **AppTheme**: A class defining the light and dark themes for the application.

When the switch in the app is toggled, the `AppThemeState`'s state changes, and the entire app's theme updates accordingly.

## Preview

Below are the previews of the app in light mode and dark mode:

Light mode:
![Light mode](Simulator Screenshot - iPhone 14 Pro Max - 2023-08-04 at 18.44.06.png)

Dark mode:
![Dark mode](Simulator Screenshot - iPhone 14 Pro Max - 2023-08-04 at 18.44.10.png)
