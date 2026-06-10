## **CATA-0004:** Catalog testing - Request Publication

> **Summary:** Verify that non-admin users can successfully upload their own E-Books pending for approval by admins.  <br>

**Preconditions:** _User is authenticated and not an admin._  

Scenario 1 

| \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the main page is shown   | 
 |  2 |   On the upper right corner of the home page, click on the profile icon on the upper right corner of the page.   | Verify that the user is able to access the user-profile-page.   | 
 |  3 |   In the user-profile-page, below the component that displays the username and e-mail are two buttons. Click the right button that says `Become a Writer!` If the user is publishing for the first time, otherwise, click `Publish A Story`    | Verify that the user is able to render the modal for Publishing an E-Book.  |  
 |  4 |   Input data accordingly in the appropriate fields in the Publish Book Modal and click the check icon in the upper right corner.   | Verify that the user is able to successfully add a book pending for approval.  |  
   

**Post-conditions:**  

_The pending e-book will be visible in the admin's side to be approved or rejected for publication._ 
