* This project is a GUI-based password generator built using Python's tkinter library. It allows users to create secure passwords with customizable criteria and evaluates their strength. The application provides user-friendly features like a strength meter, dark mode, and password display options.

* Features:
  1. Password Generation:
     a. Customizable Criteria-Length of the password-Inclusion of uppercase letters-Inclusion of digits-Inclusion of special 
        characters.
     b. Secure Generation-Uses the secrets module for cryptographically secure random password generation.

  2. Password Strength Evaluation:
     a. Categorizes passwords as Weak, Medium, or Strong based on:
     b. Length
     c. Inclusion of diverse character types (uppercase, digits, special characters).
     d. Provides suggestions to improve password strength.

  3. Password Display Options-Users can choose to display either the plain password or its hashed version (SHA-256 with a 
      random salt).

  4. Strength Meter- A graphical progress bar displays the password's complexity level on a scale from Weak to Strong.

  5. Dark Mode- Toggleable dark mode to improve usability in low-light conditions.

  6. Output Display and Clear Functionality:
     a. Generated passwords and suggestions are displayed in a text box.
     b. A button is available to clear the output.
     

*Usage:
1. Launch the application.
2. Enter the desired password length.
3. Select options to include uppercase letters, digits, and/or special characters.
4. Choose whether to display the plain password or its hashed version.
5. Click Generate Password to create a new password.
6. View the password's strength and suggestions for improvement in the output box.
7. Use Clear Output to reset the output.
8. Toggle Dark Mode for a better visual experience

*Code Structure:
 1. generate_password- Generates a random password and its hashed version using a secure salt.
 2. password_strength- Evaluates the password's strength based on length and character diversity.
 3. password_complexity- Calculates a numeric complexity score for updating the strength meter.
 4. update_strength_meter- Updates the progress bar and strength label based on the password's complexity.
 5. toggle_dark_mode- Toggles between light and dark UI themes.
 6. on_generate_click- Handles password generation and displays results in the output box.
 7. clear_output- Clears the text output.



