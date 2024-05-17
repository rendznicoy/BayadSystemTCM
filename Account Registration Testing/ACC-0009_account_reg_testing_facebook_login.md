## **ACC-0009:** Account Registration Testing - Facebook Login

> **Summary:** Verify that user successfully logs in with their facebook account. <br>

**Preconditions:**

- The user must be connected to the internet
- Facebook account must be registered

Scenario 1

| \#  | Step                                  | Expected Behavior                                                         |
| --- | ------------------------------------- | ------------------------------------------------------------------------- |
| 1   | Vist the mobile app.                  | Verify that the login page is shown.                                      |
| 2   | Click the login with facebook button. | Verify that the user is logged in successfully or prompted with an error. |

**Post-conditions:**

- User must be logged in successfully if facebook account is already registered.
- User will be prompted with an error if facebook account is still not registered.
