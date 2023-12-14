---
layout: default
title: Scheduled Alerts
nav_order: 13
---

The Scheduled Alerts section in Ace Shield allows you to configure and manage scheduled alerts for specific events or conditions. It provides an overview of all the alerts you have created. The Scheduled Alerts section displays the following fields:

| Field       | Description                                                                                                          |
|-------------|----------------------------------------------------------------------------------------------------------------------|
| Name        | Name of the scheduled alert.                                                                                          |
| Recipients  | Email addresses of the recipients who will receive the alert.                                                         |
| Actions     | Allows you to delete the alert. Please note that deleting an alert will remove it from the system.                    |

**Create New Alert**

To create a new scheduled alert: 

-Click on the "Add Alert" button. 

-Provide the required details for the alert:
| Field                | Description                                                                                       |
|----------------------|---------------------------------------------------------------------------------------------------|
| Alert Name           | Enter a descriptive name for the alert.                                                           |
| Field                | Select the field to be monitored for triggering the alert.                                        |
| Operator             | Choose the operator to compare the field value.                                                   |
| Value                | Enter the value against which the field will be compared.                                         |
| Add Filter (Optional) | Click on the "Add Filter" button to add additional filters for the alert.                        |
| Destination          | Provide the email addresses where you want to send the alerts.                                    |
-Click on the Submit button to create the alert. 


Once created, the alert will be scheduled and triggered based on the specified conditions. The recipients specified in the destination field will receive the alert notifications via email. Please note that deleting an alert will remove it from the system. The specific alert configuration and its impact may vary based on the field, operator, and value settings chosen.