---
title: "Add Jira Integration"
chapter: true
weight: 1
---

# Add Jira Integration
----

{{< youtube Q9GYdAwI7XY >}}

### Connect to JIRA Cloud  

Note:You must be a Project Administrator to set up this integration between JIRA Cloud and qTest Manager.  
Follow these steps to set up a connection with JIRA Cloud:
<br>
- Install the free qTest for JIRA Test Management add-on from the [Atlassian Marketplace.] (https://marketplace.atlassian.com/apps/1211480/qtest-for-jira-test-management?hosting=cloud&tab=overview)  

![JIRA Integration](https://marketplace-cdn.atlassian.com/files/fa772096-2adc-4461-bffa-6db90877f0fc)

[Demo Video] (https://www.youtube.com/watch?v=0uhgHQRyvHs)

JIRA Cloud can be added with:  
- API Token  
- OAuth Token

-----------
### Create a New JIRA Cloud Connection  

1.Navigate to the **qTest project**, and select the gear icon in the toolbar.  
2.Select **Integration Settings**; the "Configure Integrations" page displays.  
3.Select **JIRA** in the External Systems panel; the "Configure Integration: JIRA" page displays  
4.Select **Add JIRA Connection**; the Add JIRA Connection page is displayed.   

Enter information in the fields as described below:  

* **Connection Name**: Enter a name that represents your JIRA instance.  
* **Server URL**: Enter the URL of your JIRA instance.  
* **Web URL**: This field is only needed when setting up the connection between qTest Manager and JIRA Server.
* **Username**: Enter a JIRA Global Adminusername in this field. A global administrator in JIRA is the same as a site administrator. For information on setting up JIRA administrator permissions,please see the JIRA article Manage JIRA Global Permissions.  
* **Password or Token**: A connection can be established usinga Jira Token.  
	* After entering the JIRA connection details, selectTest JIRA Connection.If the connection between qTest Manager and JIRA is successful, the following message is displayed:  
	"**Connected to the server successfully.**"  
	* Select Save and Configure.  
	
NOTE: If you receive an error message after clicking theSave and Configurebutton, see theCommon Roadblockssection near the end of this article.

### Tips  
----
**Optional**: For JIRA OAuth If you want to use your ownprivate key, you will need toupdate your JIRA configuration to account for the new private keyyou uploaded in theSecurity tabof Site Administration in qTest.  
<br>
**Existing OAuth users** will need to complete the following if moving to the private key option:  
* Delete the current Incoming Authentication configuration in Jira.    
* Re-enterthe Consumer Key, Consumer Name, and Public Key referenced above.  
* Save

