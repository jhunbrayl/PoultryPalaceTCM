## **LOGN-0005:** Login testing - Empty Password

> **Summary:** Verify that error message indicating empty password field.  <br>

**Preconditions:** The user must be done registering an account.


Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 | Enter a valid username into the username field.     | Verify that username is entered successfully   |
 |  2 | Leave the password field empty.     | Verify that password field remains empty   |
 |  3 | Click the "Let's Go" button.     | Verify that system displays an error message indicating empty password field   |

**Post-conditions:**

 - The user remains on the login page.
