# testing

Introduction to testing - CodeLabs

 https://developer.android.com/codelabs/advanced-android-kotlin-training-testing-test-doubles#0

 - Testing Examples
 https://github.com/android/testing-samples/tree/main/ui/espresso

 Create UI Tests Regularly:
Ensure your app's UI is functioning correctly.
Automate user interactions to save time and reduce errors.
Automate UI Tests:
Use frameworks like Espresso for Views or Jetpack Compose for Compose components.
Take advantage of automatic synchronization of test actions with the UI.
Track Background Operations:
Use Espresso Idling Resources to monitor asynchronous operations.
 https://developer.android.com/training/testing/espresso/idling-resource
Replace modules with testing versions that track idleness, like TestDispatcher for coroutines or RxIdler for RxJava.
Avoid Arbitrary Pauses:
Do not use sleep in tests as it can make tests slow and flaky.
Ensure tests are reliable across different environments.
Architecture and Testing Doubles:
Design your app architecture to allow for test doubles.
Use dependency injection (DI) frameworks like Hilt to facilitate replacing modules for testing.
Compatibility Testing:
Test your app on devices 
Test different screen and window sizes
	https://developer.android.com/training/testing/different-screens
Test tools for different screen sizes
 https://developer.android.com/training/testing/different-screens/tools

Accessibility tests
 https://developer.android.com/training/testing/espresso/accessibility-checking
Ensure compatibility across different devices (e.g., tablets, foldables).


Ensure Test Independence:
Make each test independent to avoid `dependencies that can cause flakiness.

