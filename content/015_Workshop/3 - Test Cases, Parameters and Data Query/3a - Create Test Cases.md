---
title: "Create Test Cases"
chapter: true
weight: 1

---


# Create Test Cases 
----

{{< youtube UohGKF7xRkE >}}

#### Objective
By the end of this exercise, you will be able to create Test Cases to cover the Requirements created earlier.   

#### Why is this important?
Test Cases are needed to define the steps to take during the tests in order to cover the set Requirements.Test Cases define how to test a specific area of an application in order to meet the quality objectives and detail the exact steps involved.   

#### Project Perspective
The 3 Requirements you created in the previous exercise will need to be covered by dedicated Test Cases. Your Test Cases will need to define the steps for:   
 • The Login process   
 • The ordering process of the item "books"   
• The final verification of the Shopping Cart content

#### Instructions
To cover the Requirement **"Login"**, create the following Test Case:   

| Field | Value |
| ---- | ---- |
| Name | Login | 
| Descripton | Login to the Web Shop using your own login credentials | 
| Type | Manual | 
| Precondition | User must have a valid registered profile on the Web Shop |   

To cover the Requirement **"Order Books"**, create the following Test Case:
   
| Field | Value |
| ---- | ---- | 
| Name | Order Book | 
| Descripton | Navigate to the "Books" section of the Web Shop and order a book by adding it to the Shopping Cart | 
| Type | Manual | 
| Precondition | User must be Logged to Web Shop |   

To cover the Requirement **"Verify content of the Shopping Cart"**, create the following Test Case:   

| Field | Value |
| ---- | ---- |
| Name | Verify Shopping Cart content |
| Descripton | Navigate to the Shopping Cart and verify that the items you added earlier are present |
| Type | Manual |
| Precondition | User must be Logged in to Web Shop and at least one item has to have been added to the Shopping Cart |

Add the following Test Steps to the Test Cases:

| Test Case | Step# | Step Description | Expected Result |
| ---- | ----| ----| ---- |
| Login | 1 | Open the Web Shop application using the URL - http://demowebshop.tricentis.com/ | User is able to open the Web Shop using the mentioned URL |
|   | 2 | Login to the Web Shop using your own credentials | User is able to login to the Web Shop using  their own credentials |
| Order Book | 1 | Navigate to the "Books" section of the Web Shop | User is able to navigate to the "Books" section of Web Shop |
|   | 2 | Add a book to the Cart by clicking on the "Add to Cart" button | User is able to click on the "Add to Cart" button of the selcted Book |
| Verify content of the Shopping Cart | 1 | Navigate to the Shopping Cart of the Web Shop | User is able to Navigate to the Shopping Cart of the Web Shop |
|   | 2 | Verify that the Book you added earlier is present | User is able to get the Book which was added earlier|    

**Hints**   
- It is recommended to create Test Cases directly from Requirements to ensure that they will be automatically linked   
- If you created your Test Cases from the Test Design section of qTest Manager, remember to link them to the appropriate Requirements manually