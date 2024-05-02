## **INV-0010:** Inventory testing - Add Stock Orders 

> **Summary:** Verify that stock orders is saved and displayed successfully.  <br>

**Preconditions:** _None_  

Scenario 1

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  The user clicks the 'Orders' navigation bar    | Verify that Stock Order form is displayed  | 
 |  1 |  The user clicks the Add "+" button    | Verify that Add Orders form is displayed  | 
 |  2 |  The user selects the Order Category    | Verify that input type radios can be clicked | 
 |  3 |  The user clicks the quantity input field   | Verify that input field can be clicked and numerical value can be added   | 
 |  3 |  The user clicks the total amount input field   | Verify that input field can be clicked and numerical value can be added   |  
 |  4 |  The user clicks the date input field   | Verify that input field can be clicked and calendar will be shown   |  
 |  5 |  The user press the Save button   | Verify that button is working and entry is added on the order's inventory page   |
 
**Post-conditions:**  

 * The data is being saved in the database
 * The entry can now be seen in the inventory page
