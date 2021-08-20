---
title: "Generate and Execute Test Runs"
chapter: true
weight: 1
---
# Generate and Execute Test Runs
----

{{< youtube CCp1ia5Tom0 >}}

#### Objective
By the end of this exercise, you will be able to generate Test Runs from previously created Test Cases and execute them.   

#### Why is this important?
We need to ensure is that all possible combinations from our Test Cases are tested. We therefore need to generate the same number of Test Runs. Please note, one Test Run is created per combination.   

#### Project Perspective
Now that our Test Cases have been approved, we are ready to generate the Test Runs. This means we will generate a Test Run for each possible combination covering the specified Requirements      

#### Instructions
Create a new test cycle   

| Name | Description |
| ---- | ----|
| Ordering Books | Testing the ordering of the available Books by adding them to the Shopping Cart |   

Under the newly create Test Cycle, create a new Test Suite.   
  
| Name | Description |
| ---- | ---- |
| Order Books | Browser TestTesting the ordering of the available Books by adding them to the Shopping Cart. |   

Generate the Test Run for the Test Case **"Login"**.   
Generate the Test Run for the Test Case **"Order Book"** with the following settings:   
  
| Test Case | Test Run Naming Convention | Create Run Data | Randomly select Parameter Values | Number of Data Combinations |
| ---- | ---- | ---- | ---- | ---- |
| Order Book | System Default | Randomize Data | Unique Values Only | 6 |   

Generate the Test Run for the Test Case **"Verify content of the Shopping Cart"**.