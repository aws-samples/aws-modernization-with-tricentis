---
title: "Create Parameters"
chapter: true
weight: 2
---

# Create Parameters
----

{{< youtube 4PU68ZmBDZo >}}

#### Objective
By the end of this exercise, you will be able to create and use Parameters in qTest Manager and assign them to the Project.

#### Why is this important?
Often, when new features are added to an application, they will create multiple variables for our tests.   
Creating separate Test Cases for each of these variables would be time consuming and repetitive.   
Parameters help save time and reduce the number of manually created Test Cases.


#### Project Perspective
In our Web Shop, 6 different books were added.   
Instead of creating 6 different Test Cases, we will create a Parameter to include all 6 books.    

#### Instructions
Create a Parameter called **"Books"** using the following details:   

| Parameter Name | Description | Value |
| ---- | ---- | ---- |
| Books | These are the books available in the Web Shop application | Computing and Internet |
|   |   | Copy of Computing and Internet EX |
|   |   | Fiction |
|   |   | Fiction EX |
|   |   | Health |
|   |   | Science |   

Assign the Parameter to your Project   

For the Test Case **“Order Book”** ,change Test Step 2 to match the following:

| Test Case | Step# | Step Description | Expected Result |
| ----| ----| ----| ----|
| Order Books | 2 | Add **@Books** to the Cart by clicking on the "Add to Cart" button | User is able to click on the "Add to Cart" button for the chosen Book |   

Save your work

**Hints**
- A Parameter will be assigned to all your Projects by default if not specified otherwise.

