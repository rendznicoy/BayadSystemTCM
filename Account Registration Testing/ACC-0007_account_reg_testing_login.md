## **ACC-0007:** Account Registration Testing - Login

> **Summary:** Verify that user successfully logs in with their account. <br>

**Preconditions:**

- The user must be connected to the internet
- Username must be registered

Scenario 1

| \#  | Step                    | Expected Behavior                                                         |
| --- | ----------------------- | ------------------------------------------------------------------------- |
| 1   | Vist the mobile app.    | Verify that the login page is shown.                                      |
| 2   | Input username.         | Verify that the password textbox is ready for input.                      |
| 3   | Input password.         | Verify that the login button is clickable.                                |
| 4   | Click the login button. | Verify that the user is logged in successfully or prompted with an error. |

**Post-conditions:**

- User must be logged in successfully if user credentials are correct.
- User will be prompted with an error if user credentials are incorrect.
