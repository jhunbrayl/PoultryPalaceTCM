## **REG-0004:** Registration Testing - Empty Username

> **Summary:** Verify that message shows up if Username field is empty.

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Leave the username field empty | Verify that the system detects the empty username field and displays an appropriate error message. |
| 2 | Enter a valid password | Verify that the password field is populated correctly. |
| 3 | Click the "Let's Go" button | Verify that the login button is clickable and responds to the user's action. |
| 4 | See the error message | Verify that the system displays an error message indicating that the username cannot be empty. |

**Post-conditions:**

- The system should not allow the user to log in with an empty username.
- An appropriate error message should be displayed to the user when the username field is left empty.
- The user should not be able to proceed with the login process if the username is empty.
