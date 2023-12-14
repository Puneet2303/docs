---
layout: default
title: Active Response
nav_order: 12
---

The Active Response section in the SIEM portal allows you to manage and configure active trigger actions for your devices. It provides an overview of all the active responses you have created. The Active Response section displays the following fields:

| Field         | Description                                                                                                           |
|---------------|-----------------------------------------------------------------------------------------------------------------------|
| Name          | Name of the active response.                                                                                           |
| Command Name  | Name of the command associated with the active response.                                                               |
| OS            | Operating system compatibility for the active response.                                                                |
| Timeout       | Timeout duration for the active response.                                                                              |
| Actions       | Provides options to delete the particular active response. Please note that deleting an active response will remove it from the system. |

To create a new active response: 

-Click on the "Add Active Response" button. 

-Provide the required details for the active response: 
| Field          | Description                                                                                                 |
|----------------|-------------------------------------------------------------------------------------------------------------|
| Name           | Enter a descriptive name for the active response.                                                           |
| OS             | Select the compatible operating system for the active response.                                             |
| Command Name   | Specify the name of the command associated with the active response.                                        |
| Devices        | Select the devices on which the active response will be executed.                                           |
| Assigned Rules | Assign rules to the active response by providing the rule ID and rule level.                                |
| Timeout        | Set the duration after which the active response will time out.                                             |
| Status         | Specify the initial status of the active response.                                                          |

-Click on the Submit button to create the active response. 


Please note that deleting an active response will remove it from the system. The active response configuration and its impact on devices may vary based on the specific rules and actions assigned to it. 