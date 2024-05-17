## **ACC-00014:** Account Registration Testing - Registration Account Creation

> **Summary:** Verify that user account is created. <br>

**Preconditions:**

- The user must be connected to the internet

Scenario 1

| \#  | Step                      | Expected Behavior                                                       |
| --- | ------------------------- | ----------------------------------------------------------------------- |
| 1   | Vist the mobile app.      | Verify that the login page is shown.                                    |
| 2   | Click the sign up button. | Verify that the registration page is displayed.                         |
| 3   | Input Name.               | Verify that the name is following the right format.                     |
| 4   | Input Mobile Number.      | Verify that the mobile number is following the right format.            |
| 5   | Input Username.           | Verify that the password textbox is active and ready for input.         |
| 6   | Input Password.           | Verify that the confirm password textbox is active and ready for input. |
| 7   | Input Confirm Password.   | Verify that the sign up button is active.                               |
| 8   | Click Sign Up Button.     | Verify that the user account is created or an error is prompted.        |

**Post-conditions:**

- Account creation is successful if input formats are valid.
- A prompt will be displayed if input formats are invalid.
