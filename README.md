# Tip Calculator Android App (Kotlin)
This is a simple Android app written in Kotlin that allows users to calculate the tip amount based on the cost of service and the quality of service. The app uses Material Design components to provide an intuitive and user-friendly interface.

# Features
- Material Design Edit Text:
Users can enter the cost of the service using a Material Design Edit Text, which provides a modern and visually appealing input field.
- Radio Group and Radio Button:
To select the quality of service, the app uses a Radio Group with Radio Buttons, enabling users to choose from various service options easily.
- Material Design Switch Button:
  The app includes a Material Design Switch Button that allows users to opt for rounding up the calculated tip amount, providing a convenient way to adjust the tip to the nearest whole number.
- Calculate Button:
  Users can trigger the tip calculation by pressing the "Calculate" button, which executes the calculateTip() function to determine the tip based on the user's selections.
- calculateTip() Function:
  The core logic of the app resides in the calculateTip() function, which takes into account the cost of service and the selected quality of service to calculate the tip amount. After the calculation, the function calls the displayTip() function to show the result.
- displayTip() Function:
  The displayTip() function is responsible for showing the calculated tip amount in a text field to the user.
- handleKeyEvent() Function:
  To enhance user experience, the app includes a handleKeyEvent() function that detects when the Enter key is pressed and hides the keyboard accordingly.

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
