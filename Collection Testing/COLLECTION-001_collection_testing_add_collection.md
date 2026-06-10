## **COLLECTION-0001:** Collection testing - Adding new Collection

> **Summary:** Verify that user is able to create collections of E-Books under a specific common quality.  <br>

**Preconditions:** User must be logged in this session and the Book information page must be accessible.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application.                                 | Verify that the home screen is shown. | 
 |  2 |  In the main page, click any of the book cards among the showcased in the dashboard.              | Verify that the user is redirected to the book-info-page. |  
 |  3 | In the book-info-page, below the component for the Book Title and the Author are two icons, click the icon of the open book next to the star.              | Verify that the user is able to see the modal for adding to collections. |  
 |  4 | Click the pencil icon next to the `Collections` tag.              | Verify that the user is able to enable the modal and modify the existing list of collections. |  
 |  5 | In the Collections Modal, click the `+` icon on the upper right corner of the modal              | Verify that the add new collection modal is rendered. |  
|  6 | Input Collection name in the text box and press the `+` icon again in the upper right corner.              | Verify that the user is successfully able to create a new collection and that the book has been added automatically to that specific collection. |  
 
 

**Post-conditions:**  

 - The user will have appended a new book to the newly added collection.