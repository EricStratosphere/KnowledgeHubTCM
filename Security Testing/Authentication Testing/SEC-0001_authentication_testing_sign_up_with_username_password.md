## **SEC-0001:** Authentication testing - Sign Up with Username/Password  

> **Summary:** Verify user can sign up with username and password.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the user is redirected to the login page since authentication has not been confirmed yet   | 
 |  2 |   In the login page, at the very bottom of the modal, click the emboldened `Sign Up`.  | Verify that the user is redirected to the sign-up page.   | 
 |  3 |   Fill out the fields accordingly in the Sign Up modal. (`E-Mail Address, First Name, Last Name, Password`) and click the `Create Account`button.  | Verify that the user is successful in Signing Up their profile to the platform.  |  

**Post-conditions:**  

 - The user will be able to access authorized features based on their role (Reader, Writer, Admin). 
