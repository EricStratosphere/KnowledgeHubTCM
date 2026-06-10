## **SEC-0010:** Authentication testing - Forgot Password  

> **Summary:** Verify user can recover lost account.  <br>

**Preconditions:** _None_  

Scenario 1 

| \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the user is redirected to the login page since authentication has not been confirmed yet   | 
 |  2 |   In the login-page, below the Fields for E-Mail and Password is another button labelled `Forgot Password?`, prompty click it.  | Verify that the user is successfully redirected to the /forgot-password page.   | 
 |  3 |   In this page, the user is greeted by a modal asking for the E-Mail address of the user, promptly fill in your credentials and click the `Send Reset Link` button below it.  | Verify that the user successfully receives an E-Mail for confirmation to Reset Password. |
 |  4 |   Upon checking E-Mail, the user is required to click the redirect URL provided by the E-Mail.  | Verify that the user is redirected to the /reset-password page. |
 |  5 |   In this page,  the user is required to fill out two fields `New Password` and `Confirm Password`, fill out promptly and click `Update Password` button below the input boxes.  | Verify that the user successfully receives confirmation for the updated password and is redirected back to the login page . | 


**Post-conditions:**  

 - The user will be able to access authorized features based on their role (Reader, Writer, Admin). 