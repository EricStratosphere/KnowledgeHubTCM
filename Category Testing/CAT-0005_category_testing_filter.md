## **CAT-0005:** Category testing - Filter  

> **Summary:** Verify that the main page filters books by genre successfully.  <br>

**Preconditions:** _User must be authenticated and admin or writer must have published a book under a specific genre._  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch application   | Verify that the home screen is shown   | 
 |  2 |   Request publication for an E-Book under a specific genre `Details in Catalog Testing/CATA-0004_catalog_testing_request_publish.md.md`   | Verify that the user has successfully submitted an E-Book for review.   | 
 |  3 |   Once approved by an admin, return to the main page and search for the new E-Book under the Genre   | Verify that Filter system by Genre is successful.    |  

**Post-conditions:**  

 _None._ 
