## **SAL-0006:** Sale testing - Edit Invoice

> **Summary:** Verify that invoice entry is modified and displayed successfully.  <br>

**Preconditions:** There must be an existing invoice entry  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   The user clicks the existing invoice entry   | Verify that the entry is clickable and Edit/Delete pop up can be seen on the screen   | 
 |  2 |   The user choose the Edit button  | Verify that the button can be clicked and the Add Sale form is displayed  | 
 |  3 |   The user alters the existing data entry with new one   | Verify that the input fields can be navigated and new entries can be accepted   |  
 |  4 |   The user clicks the Save button   | Verify that the button is working and the edited entry will be displayed in the invoice page   |  

**Post-conditions:**  

* The data is being saved in the database
* The entry can now be seen in the invoice page 
