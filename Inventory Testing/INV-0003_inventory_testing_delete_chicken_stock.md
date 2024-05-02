## **INV-0003:** Inventory testing - Delete Chicken Stock  

> **Summary:** Verify that Chicken Stock is deleted successfully.  <br>

**Preconditions:** There must be an existing chicken stock entry

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing chicken stock entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Delete button  | Verify that the button can be clicked and the Delete Chicken Stock confirmation pop up form is displayed  | 
 |  3 |   The user press the 'Yes, Delete' button   | Verify that the button works and the entry is now being deleted from the inventory page   |  

**Post-conditions:**  

* The entry is removed from the inventory page
  

Scenario 2

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing chicken stock entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Delete button  | Verify that the button can be clicked and the Delete Chicken Stock confirmation pop up form is displayed  | 
 |  3 |   The user press the 'Cancel' button   | Verify that the button works and the entry remains as it was on the inventory page  |  

**Post-conditions:**  

* The entry remains on the inventory page 
