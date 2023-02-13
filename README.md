<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

This Flutter package provides a set of custom transition animations for navigating 
between screens in your app. The animations can be used to provide a smooth and 
visually appealing experience for your users.

## Features

1. Smooth page transitions with multiple animation types
2. Create custom transitions with custom animation effects
3. Animate multiple elements at the same time
4. Transition between screens with ease
5. Support for multiple platforms (iOS and Android)
6. Automatic back navigation
7. Modular design for easy customization and extensibility
8. Optimized performance with minimal battery usage

## Getting started

Prerequisites: 
1. Familiarity with Dart language 
2. Knowledge of the Flutter framework 
3. Understanding of page routing and navigation within Flutter

Instructions:
1. Create a new Flutter project using your preferred IDE.
2. Install the flutter package for screen transitions - https://pub.dev/packages/custom_route_transitions
3. Import the custom_route_transitions package into your project.
4. Set up your navigation system within your app to use the custom_route_transitions package.
5. Add the transitions you would like to use for each navigation within your app.
6. Test the transitions by running your app in either an emulator or physical device.
7. Refine and customize the transitions to suit your needs.

## Usage

Example 1:

// To enable screen transitions
Navigator.push(context, FadeRoute(page: MyPage()));

// To disable screen transitions
Navigator.push(context, MaterialPageRoute(page: MyPage()));

Example 2:

// To enable screen transitions with a custom animation
Navigator.push(context, SlideRoute(page: MyPage(), transition: TransitionType.slideLeft));

// To enable screen transitions with a custom duration
Navigator.push(context, FadeRoute(page: MyPage(), duration: Duration(milliseconds: 500)));

## Additional information

More information about the flutter_screen_transitions package can be found on the package's pub.dev page - https://github.com/system1k/route_transition.git. 

To contribute to the package, users should fork the repository and submit a pull request - https://github.com/system1k/route_transition.git. 

For issues, users should file an issue on the package's GitHub page - https://github.com/system1k/route_transition.git. 

The package authors typically respond to issues within 24 hours.