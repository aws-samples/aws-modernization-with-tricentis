---
title: "Scenario"
chapter: true
weight: 1
---


# Scenario   
----

{{< youtube D3Z2b2BvDG0 >}}

#### Objective
By the end of this exercise, you will be able to create an end-to-end testing scenario for the login process using several different user accounts in qTest Manager. You will also be able to create and use Data Sets.

#### Why is this important?
This Scenario will give you the opportunity to practice the concepts learned during the training.   
This environment and set of instructions mimic more closely the project environment and tasks distribution.   
Additionally, Data Sets are very important when our goal is to generate a high number of combinations with a given set of variables for our tests

#### Project Perspective
Your manager is asking you to test the login process for our Web Shop.   
To do so, you will be using 4 different valid sets of usernames and passwords.   

#### Instructions   

Create a new Release   

| Field | Value |
| ---- | ---- |
| Name | New Account |
| Status | In Progress |
| Start Date | Today |
| End Date | 15 days from Today |
| Description | Testing of the login functionality added to the Web Shop |
| Release Note | The login functionality will be tested using a valid set using valid usernames and passwords|   

Create a new Requirement under the **"New Account"** Release.   

| Field | Value |
| ---- | ---- |
| Name | User Login |
| Status | New |
| Priority | Must Have |
| Type | Functional | 
| Assigned to | Yourself |
| Description | As a user I should be able to log into the application, using a valid username and password|   

Create a new Test Case to cover for the Requirement **"User Login"**.   

| Field | Value |
| ---- | ---- |
| Name | New User Login |
| Description | Test the login functionality of the Web Shop using valid usernames and passwords |
| Type | Manual |
| Precondition | Navigate to the login page of the application.  Username and Password used must be correct |   

Add the following Test Steps to the Test Case:   

| Test Case | Test Step # | Step Description | Expected Result |
| ---- | ---- | ---- | ---- |
| New User Login | 1 | Open the Web Shop application using the URL: http://demowebshop.tricentis.com/ | A user can open the Web Shop using the URL provided |
|   | 2 | Click on login | A user is able to navigate to the Login session of the Web Shop |
|   | 3 | Enter Username | A user is able to enter the Username for the Login |
|   | 4 | Enter Password | A user is able to enter the Password for the Login |
|   | 5 | Click on "Login" button | A user is able to click on the "Login" button and successfully login to the account. |   

Create 2 separate Parameters, 1 for **"LoginUsernames"** and 1 for **"LoginPasswords"**   

| Parameter Name | Description | Value |
| ---- | ---- | ---- |
| Login Usernames | These are the Usernames for the registered accounts in the Web Shop. | User1@sample.test |
|   |   | User2@sample.test |
|   |   | User3@sample.test |
|   |   | User4@sample.test |
| Login Passwords | These are the Passwords for the registered accounts in the Web Shop. | Password 1 |
|   |   | Password 2 |
|   |   | Password 3 |
|   |   | Password 4 |   

Create a Data Set using the **"LoginUsernames"** and **"LoginPasswords"** Parameters   

| Name | Description | Combination Type |
|---- | ---- | ---- |
| Login Credentials | Set of Valid Usernames and Passwords | Generate Unique Combinations |   

Generate Test Runs for the Test Case *"New User Login"*   
Execute the Test Runs and log any Defect if found.
