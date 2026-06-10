## **COLLECTION-0002:** Collection testing - Edit Collection

> **Summary:** Verify that user is able to edit the name of the collection.  <br>

**Preconditions:** User must be logged in this session .  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application.                                 | Verify that the home screen is shown. | 
 |  2 |  In the main page, click the profile icon in the upper right corner of the page.              | Verify that the user is redirected to the user-profile-page. |  
 |  3 | In the user-profile-page, below the component for the User Info, click the Pencil Icon next to `Collections`.              | Verify that the collection modal is rendered on click. |  
 |  4 | Click the pencil icon next to the `Collections` tag.              | Verify that the user is able to enable the modal and modify the existing list of collections. |  
 |  5 |  In the Collections modal, each entry in the list of collections has options for editing (Pencil Icon) and deletion (Garbage Icon). Click the pencil icon              | Verify that the user successfully renders another modal that allows the option for renaming the collection. |  
|  6 | Input new collection name of your choice in the modal's text box and click the check icon in the upper right corner of the modal.              | Verify that the user was successful in editing the Collection name. |  
 
 

**Post-conditions:**  

_None_