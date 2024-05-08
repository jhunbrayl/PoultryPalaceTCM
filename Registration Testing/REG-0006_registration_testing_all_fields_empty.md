## **REG-0006:** Registration testing - All Fields Empty

> **Summary:** Verify that error messages indicating all fields are required.  <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Leave the username field empty | Verify that the system detects the empty username field and displays an appropriate error message. |
| 2 | Leave the password field empty |  Verify that the system detects the empty username field and displays an appropriate error message |
| 3 | Click the "Let's Go" button | Verify that the login button is clickable and responds to the user's action. |
| 4 | Observe the error message | Verify that the system displays an error message indicating that the username cannot be empty. |

**Post-conditions:**

- The system should not allow the user to log in with an empty username and empty password.
- An appropriate error message should be displayed to the user when the username field and password field is left empty.
- The user should not be able to proceed with the login process if the username is empty.
