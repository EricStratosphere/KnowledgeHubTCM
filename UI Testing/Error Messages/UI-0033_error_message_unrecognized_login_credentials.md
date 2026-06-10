## **UI-0033:** Error Message - Unrecognized E-Mail and Password.

> **Summary:** Verify that an error message is prompty received when a user tries to input invalid credentials on Log In.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the user is redirected to the login page since authentication has not been confirmed yet   | 
 |  2 |   In the login page, fill out the forms accordingly `E-Mail Address, Password` with invalid credentials and click `Sign In` button.  | Verify that the user has successfully failed to Log In their credentials.   | 

**Post-conditions:**  
_None_