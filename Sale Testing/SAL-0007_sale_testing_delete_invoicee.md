## **SAL-0007:** Sale testing - Delete Invoice

> **Summary:** Verify that invoice entry is deleted successfully.  <br>

**Preconditions:** There must be an existing invoice entry

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing invoice entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Delete button  | Verify that the button can be clicked and the Delete Invoice Entry confirmation pop up form is displayed  | 
 |  3 |   The user press the 'Yes, Delete' button   | Verify that the button works and the entry is now being deleted from the invoice page   |  

**Post-conditions:**  

* The entry is removed from the invoice page
  

Scenario 2

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing invoice entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Delete button  | Verify that the button can be clicked and the Delete Invoice Entry confirmation pop up form is displayed  | 
 |  3 |   The user press the 'Cancel' button   | Verify that the button works and the entry remains as it was on the invoice page  |  

**Post-conditions:**  

* The entry remains on the invoice page 
