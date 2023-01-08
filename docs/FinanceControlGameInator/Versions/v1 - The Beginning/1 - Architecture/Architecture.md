## Overview
- This versions is very simple, so this architecture doc is going to be very simple too

## Client-side

- Flutter will be the framework we're going to use to build the client-side app
- Since we use flutter, the software language we're going to use is Dart
- It is expected that all the business rules are going to be tested using some flutter test library. 
	- At this moment, we expect only unit tests to be created
- Since now we expect creation of components to be reused in the future, like cards, buttons and popups

<img src="https://user-images.githubusercontent.com/38296002/211224309-ee72d7f3-7194-4348-b0ba-9a069039b89d.png"/>

## Data storage and management
- This version will hold all the data in memory in the client-side

## Server-side
- There is no server side at this moment, check it in the next versions

## Q&A
- Why not use the local storage?
	- Use the local storage implies control the state of the application, it means that the app should enable the player to restart the game, otherwise the game will never end. Thus, since this version want to be as simple as possible and state control implies in complexity, this feature has been postponed.

## References
- [Dart](https://dart.dev)
- [Flutter](https://flutter.dev)
- [Flutter local storage](https://pub.dev/packages/localstorage)
- [Flutter Test Library](https://api.flutter.dev/flutter/flutter_test/flutter_test-library.html)
- [Flutter Test Types](https://docs.flutter.dev/testing)
- [Why I don't set up a code coverage percentage](https://stackoverflow.com/questions/90002/what-is-a-reasonable-code-coverage-for-unit-tests-and-why)