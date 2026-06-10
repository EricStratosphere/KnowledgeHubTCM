## **CATA-0002:** Catalog testing - Approve or Reject Book (Admin)  

> **Summary:** Verify that book submitted by a user can be approved for publish by an admin.  <br>

**Preconditions:** _User must be authenticated and an admin. Another user must be a writer submitting a book for approval._  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application.                                 | Verify that the home screen is shown. | 
 |  2 | In the main page, click the plus icon on the upper right corner of the page.              | Verify that the user is redirected to the admin-page. |  
 |  3 | In the admin page, the right partition of the page showcases all the pending book requests.              | Verify that the user is able to view the list of pending requests for approval. |  
 |  4 | Click one of the entries in the list of pending requests.              | Verify that the user is redirected to the book-info-page and can access and read the book prior to approval or rejection. |  
 |  5 | Return to the admin page, in each entry are two buttons for approval and rejection, click either for their respective function.              | Verify that the user is able to approve or reject the writer's e-book. |  
**Post-conditions:**  
    _None_