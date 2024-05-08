## **INV-0014:** Inventory Testing - Empty Fields

> **Summary:** Verifies that an error message is displayed when required fields are left empty.  <br>

**Preconditions:** User is logged in and on the sale record page.

Scenario 1

 | \# | Step | Expected Behavior |
 |----|------|-------------------|
 |  1 |  Leave one or more fields empty.    | Verify that nothing happens   |
 |  2 |  Click on the Save button.    | Verify that an error message is displayed indicating that required fields are empty.   |

**Post-conditions:**

 - Sale is not recorded.
 - Error message is displayed indicating that required fields are empty
