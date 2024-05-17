## **INV-0003:** Inventory Testing - Delete  Product

> **Summary:** Verify that admin user successfully deleted a product.  <br>

**Preconditions:** 
+ User must be logged in
+ A product must be present

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Vist the mobile app.     | Verify that the login page is shown.   | 
 |  2 | Login using your account.     | Verify that the landing page shows the navigation bar.   | 
 |  3 | In the footer navigation bar, click the products menu.     | Verify that the products page displays the product list.  |  
 |  4 | Select a product, swipe left     | Verify that the Delete button shows when swiped.  |  
 |  5 | Click the Delete Button       | Verify that the 'Delete Product' modal shows.   |  
 |  6 | Confirm to Delete product  | Verify that the 'Delete' button is displayed.   |  
 |  7 | Click the Delete Button  | Verify that the product is deleted on the list.   |  

**Post-conditions:**
+ The product is deleted and no longer displayed
