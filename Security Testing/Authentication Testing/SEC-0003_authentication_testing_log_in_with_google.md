## **SEC-0004:** Authentication testing - Log in with Google  

> **Summary:** Verify user can log in with GSI.  <br>

**Preconditions:** _None_  

Scenario 1 

| \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the user is redirected to the login page since authentication has not been confirmed yet   | 
 |  2 |   In the login-page, below the Sign In button is another button labelled `Sign In With E-Mail`, prompty click it.  | Verify that the user is successfully redirected to the Google Oauth Account Selection for Authentication.   | 
 |  3 |   Among the authenticated E-Mail accounts, select one.  | Verify that the user is successfully authenticated and redirected to the main page.   | 

**Post-conditions:**  

 - The user will be able to access authorized features based on their role (Reader, Writer, Admin). 
