## **ACC-0008:** Account Registration Testing - Google Login

> **Summary:** Verify that user successfully logs in with their google account. <br>

**Preconditions:**

- The user must be connected to the internet
- Google account must be registered

Scenario 1

| \#  | Step                                | Expected Behavior                                                         |
| --- | ----------------------------------- | ------------------------------------------------------------------------- |
| 1   | Vist the mobile app.                | Verify that the login page is shown.                                      |
| 2   | Click the login with google button. | Verify that the user is logged in successfully or prompted with an error. |

**Post-conditions:**

- User must be logged in successfully if google account is already registered.
- User will be prompted with an error if google account is still not registered.
