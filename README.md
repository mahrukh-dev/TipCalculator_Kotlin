`# Tip Calculator Android App (Kotlin)
This is a simple Android app written in Kotlin that allows users to calculate the tip amount based on the cost of service and the quality of service. The app uses Material Design components to provide an intuitive and user-friendly interface.

# Features
- **Material Design Edit Text:**
Users can enter the cost of the service using a Material Design Edit Text, which provides a modern and visually appealing input field.
- **Radio Group and Radio Button:**
To select the quality of service, the app uses a Radio Group with Radio Buttons, enabling users to choose from various service options easily.
- **Material Design Switch Button:**
  The app includes a Material Design Switch Button that allows users to opt for rounding up the calculated tip amount, providing a convenient way to adjust the tip to the nearest whole number.
- **Calculate Button:`**
  Users can trigger the tip calculation by pressing the "Calculate" button, which executes the calculateTip() function to determine the tip based on the user's selections.
- **calculateTip() Function:**
  The core logic of the app resides in the calculateTip() function, which takes into account the cost of service and the selected quality of service to calculate the tip amount. After the calculation, the function calls the displayTip() function to show the result.
- **displayTip() Function:**
  The displayTip() function is responsible for showing the calculated tip amount in a text field to the user.
- **handleKeyEvent() Function:**
  To enhance user experience, the app includes a handleKeyEvent() function that detects when the Enter key is pressed and hides the keyboard accordingly.

# Difference in Light Theme and Dark Theme
The app supports both light and dark themes. Users can choose their preferred theme from the device settings, and the app will automatically adapt to the selected theme. The light theme provides a clean and bright appearance, while the dark theme offers a sleek and modern look that is easier on the eyes in low-light environments.

# Better Coding using style.xml File
To ensure consistency and reusability of styles across the app, the app leverages the style.xml file. It defines custom styles for various UI elements, such as buttons, text fields, and backgrounds. By centralizing the style definitions, the codebase becomes more organized and maintainable. Additionally, using styles helps maintain a consistent visual language throughout the app, adhering to Material Design guidelines.

# Use of Scrollbar in UI to Support Screen Rotation
The UI layout of the app is designed to support screen rotation. When the user rotates the screen, the app will adjust the layout dynamically to fit the new orientation. To handle longer content that might not fit on the screen, the app incorporates a scrollbar, enabling users to scroll through the content and access all elements conveniently, regardless of the device's orientation.

# Instrumented Tests
The app includes instrumented tests to verify the accuracy of tip calculations for different percentages. The tests are written using Android's Espresso testing framework and can be found in the TipCalculatorInstrumentedTest class.

To run these tests, follow these steps:
- Open Android Studio.
- Connect your Android device or start an emulator.
- In Android Studio's "Project" view, navigate to the androidTest folder and open the TipCalculatorInstrumentedTest.kt file.
- Right-click inside the test class or on a specific test function.
- Select "Run 'CalculatorTests'".

Test Cases
1. Calculate 20 Percent Tip
   This test verifies whether the app correctly calculates a 20 percent tip for a given cost of service.
2. Calculate 18 Percent Tip
   This test verifies whether the app correctly calculates an 18 percent tip for a given cost of service
3. Calculate 15 Percent Tip
   This test verifies whether the app correctly calculates an 15 percent tip for a given cost of service

# How to Use
- Launch the app on your Android device.
- Enter the cost of the service in the provided Material Design Edit Text field.
- Select the quality of service from the Radio Buttons available in the Radio Group.
- Optionally, use the Material Design Switch Button to enable or disable rounding up the tip amount.
- Press the "Calculate" button to calculate the tip based on your selections.
- The calculated tip amount will be displayed in a text field on the screen.
- If you need to recalculate, make any necessary changes and press the "Calculate" button again.

# Compatibility
The app is compatible with Android devices running on Android OS version 27 and above.

# Acknowledgments
The development of this app was inspired by the desire to create a simple, efficient, and visually appealing tip calculator for Android users. The usage of Material Design components enhances the overall user experience and ensures a consistent and modern look across different devices.

# Credits
This app was created and developed by Mah Rukh as part of a Kotlin Android project.

# Contributions
Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
