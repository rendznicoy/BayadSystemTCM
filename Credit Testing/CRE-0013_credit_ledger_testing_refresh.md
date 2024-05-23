## **CRE-0013:** Credit Ledger Testing - Credit Ledeger Page Refresh

> **Summary:** Verify that the credit ledger list stays the same or updates when refreshed. <br>

**Preconditions:**

- User must be connected to the internet
- User must be logged in
- Transaction must be done

Scenario 1

| \#  | Step                     | Expected Behavior                            |
| --- | ------------------------ | -------------------------------------------- |
| 1   | Vist the mobile app.     | Verify that the login page is shown.         |
| 2   | Click the Credit button. | Verify that the Credit ledger page is shown. |
| 3   | Refresh the page         | Verify that the Credit ledger page is shown. |

**Post-conditions:**

- The contents of the Credit ledger stays the same, when there are no new transactions.
- The contents of the Credit ledger changes or is updated.
