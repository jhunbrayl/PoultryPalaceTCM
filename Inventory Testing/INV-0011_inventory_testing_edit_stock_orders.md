## **INV-0011:** Inventory testing - Edit Stock Orders

> **Summary:** Verify that stock orders is modified and displayed successfully.  <br>

**Preconditions:** There must be an existing stock orders entry  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing stock orders entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Edit button  | Verify that the button can be clicked and the Chicken Stock form is displayed  | 
 |  3 |   The user alters the existing data entry with new one   | Verify that the input fields can be navigated and new entries can be accepted   |  
 |  4 |   The user clicks the Save button   | Verify that the button is working and the edited entry will be displayed in the inventory page   |  

**Post-conditions:**  

* The data is being saved in the database
* The entry can now be seen in the inventory page 
