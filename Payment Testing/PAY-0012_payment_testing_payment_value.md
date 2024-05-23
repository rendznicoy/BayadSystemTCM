## **PAY-0012:** Payment Ledger Testing - Payable Input Value

> **Summary:** Verify that the add payable modal successfully takes input from users. <br>

**Preconditions:**

- User must be connected to the internet
- User must be logged in
- Transaction must be done

Scenario 1

| \#  | Step                                        | Expected Behavior                                   |
| --- | ------------------------------------------- | --------------------------------------------------- |
| 1   | Vist the mobile app.                        | Verify that the login page is shown.                |
| 2   | Click the Payment button.                   | Verify that the payment ledger page is shown.       |
| 3   | Click the Add Payable button.               | Verify that the add payable modal is shown.         |
| 4   | Enter an input on the Payable Name textbox. | Verify that the balance textbox is active.          |
| 5   | Enter an input on the Balance textbox.      | Verify that the due date textbox is active.         |
| 6   | Enter an input on the Due Date textbox.     | Verify that the add button is active.               |
| 7   | Click the Add button.                       | Verify that the payable entry is shown on the list. |

**Post-conditions:**

- The new payable entry is displayed on the payable list.
