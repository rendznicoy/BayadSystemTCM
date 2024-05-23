## **PAY-00013:** Payment Ledger Testing - Payment Page Refresh

> **Summary:** Verify that the payment ledger list stays the same or updates when refreshed. <br>

**Preconditions:**

- User must be connected to the internet
- User must be logged in
- Transaction must be done

Scenario 1

| \#  | Step                      | Expected Behavior                             |
| --- | ------------------------- | --------------------------------------------- |
| 1   | Vist the mobile app.      | Verify that the login page is shown.          |
| 2   | Click the Payment button. | Verify that the payment ledger page is shown. |
| 3   | Refresh the page          | Verify that the payment ledger page is shown. |

**Post-conditions:**

- The contents of the payment ledger stays the same, when there are no new transactions.
- The contents of the payment ledger changes or is updated.
