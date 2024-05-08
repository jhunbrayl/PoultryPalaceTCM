## **LOGN-0006:** Login testing - Invalid Credentials

> **Summary:** Verify that error message indicating invalid credentials.  <br>

**Preconditions:** The user must have be done registering an account.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter an incorrect username into the username field.    | Verify that username is entered successfully   |
 |  2 | Enter ain incirrect password into the password field.     | Verify that password is entered successfully   |
 |  3 | Click the "Let's Go" button.      | Verify that System displays an error message indicating invalid credentials  |

**Post-conditions:**

 - The user remains on the login page.
 - Error message should be displayed indicating invalid credentials
