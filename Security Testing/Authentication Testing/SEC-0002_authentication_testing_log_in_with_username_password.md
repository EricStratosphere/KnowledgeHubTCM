## **SEC-0002:** Authentication testing - Log in with Username/Password  

> **Summary:** Verify user can log in with username and password.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the user is redirected to the login page since authentication has not been confirmed yet   | 
 |  2 |   In the login page, fill out the forms accordingly `E-Mail Address, Password` and click `Sign In` button.  | Verify that the user is successfully authenticated and redirected to the main-page.   | 

**Post-conditions:**  

 - The user will be able to access authorized features based on their role (Reader, Writer, Admin). 
