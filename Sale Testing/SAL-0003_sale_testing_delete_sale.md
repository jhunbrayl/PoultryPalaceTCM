## **SAL-0003:** Sale testing - Delete Sale

> **Summary:** Verify that sale entry is deleted successfully.  <br>

**Preconditions:** There must be an existing sale entry

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing sale entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Delete button  | Verify that the button can be clicked and the Delete Sale Entry confirmation pop up form is displayed  | 
 |  3 |   The user press the 'Yes, Delete' button   | Verify that the button works and the entry is now being deleted from the sales page   |  

**Post-conditions:**  

* The entry is removed from the sales page
  

Scenario 2

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing sale entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Delete button  | Verify that the button can be clicked and the Delete Sale Entry confirmation pop up form is displayed  | 
 |  3 |   The user press the 'Cancel' button   | Verify that the button works and the entry remains as it was on the sales page  |  

**Post-conditions:**  

* The entry remains on the sales page 
