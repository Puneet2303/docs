---
layout: default
title: Real-Time Alerts
nav_order: 14
---

The Real-Time Alerts section in Ace Shield allows you to configure and manage real-time alerts for immediate response to security incidents, anomalies, or critical events. It provides an overview of all the alerts you have created. The Real-Time Alerts section displays the following fields:

| Field            | Description                                                                                                   |
|------------------|---------------------------------------------------------------------------------------------------------------|
| Alert Name       | Name of the alert.                                                                                            |
| Description      | Description or summary of the alert.                                                                           |
| Schedule         | The schedule or triggering mechanism for the alert.                                                            |
| Runs Every       | Specifies the frequency or interval at which the alert is triggered.                                          |
| Alert Start Date | The date and time when the alert becomes active.                                                              |
| Destination      | The email addresses or URLs where the alert notifications will be sent.                                       |
| Status           | Indicates the current status of the alert.                                                                    |
| Actions          | Allows you to delete the particular alert. Please note that deleting an alert will remove it from the system. |

**Create New Alert**

To create a new real-time alert: 
  

-Click on the "Add Alert" button. 

-Provide the required details for the alert:
| Field                | Description                                                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------|
| Alert Name           | Enter a descriptive name for the alert.                                                                     |
| Description          | Provide a brief description or summary of the alert.                                                        |
| Message              | Enter the message or details to be included in the alert notification.                                      |
| Condition            | Specify the condition or criteria that triggers the alert.                                                  |
| Operator             | Choose the operator to compare the field or value in the condition.                                         |
| Value                | Enter the value against which the field in the condition will be compared.                                  |
| Add Filter (Optional) | Click on the "Add Filter" button to add additional filters for the alert.                                   |
| Destination          | Provide the email addresses or URLs where you want to send the alerts                                       |

-Click on the Submit button to create the alert. 

Once created, the real-time alert will be triggered immediately based on the specified conditions. The recipients specified in the destination field will receive the alert notifications via email or through the provided URLs.  

Please note that deleting an alert will remove it from the system. The specific alert configuration and its impact may vary based on the conditions, operators, and values chosen.