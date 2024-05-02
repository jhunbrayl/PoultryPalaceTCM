## **SAL-0005:** Sale Testing - Add Invoice

> **Summary:** Verify that invoice entry is saved and displayed successfully.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------|
 |  1 |  The user clicks the Invoice navigation bar    | Verify that Invoice form page is displayed on the screen  | 
 |  2 |  The user clicks the Add "+" button    | Verify that Add Invoice form is displayed  | 
 |  3 |  The user clicks the Customer Name input field    | Verify that input field can be clicked and string value can be added  | 
 |  4 |  The user clicks the Invoice Number input field   | Verify that input field can be clicked and numerical value can be added   |
 |  5 |  The user clicks the Total Amount input field   | Verify that input field can be clicked and numerical value can be added   |  
 |  6 |  The user clicks the Due Date of Payment input field   | Verify that input field can be clicked and calendar will be shown   |  
 |  5 |  The user press the Save button   | Verify that button is working and entry is added on the sales page   | 
 
**Post-conditions:**  

 * The data is being saved in the database
 * The entry can now be seen in the invoice page
