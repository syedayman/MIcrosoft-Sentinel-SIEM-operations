# Microsoft Sentinel SIEM Operations
This write-up follows my completion of the Microsoft Applied Skills credential - [Configuring SIEM Security Operations using Microsoft Sentinel](https://learn.microsoft.com/en-gb/credentials/applied-skills/configure-siem-security-operations-using-microsoft-sentinel/) to demonstrate the ability to set up and configure Microsoft Sentinel for various SIEM (Security Information & Event Management) and SOAR (Security Orchestration, Automation & Response) operations in Azure.

![image](https://github.com/user-attachments/assets/52c2d9ec-bbf0-4b17-a897-939fd245ac18)


## Assessment Objectives
- Create and configure a Microsoft Sentinel workspace
- Deploy a Microsoft Sentinel content hub solution
- Configure analytics rules in Microsoft Sentinel
- Configure automation in Microsoft Sentinel

## Learning Path Preparation
### Creating and Managing MS Sentinel workspaces
Custom deployed resource group and its corresponding resources for the exercise 

![Screenshot 2024-09-24 180520](https://github.com/user-attachments/assets/e13f5d65-c485-4a68-88b9-2cc432468058)
---

### Connecting Microsoft services and Windows hosts to Sentinel
Deploying data connector to detect Azure Activity by launching Azure Policy Assignment Wizard

![Screenshot 2024-09-24 180624](https://github.com/user-attachments/assets/6277cc3d-4223-4842-98a9-ea96de39986b)

Azure Activity Connector is now connected as seen by the green bar

![Screenshot 2024-09-24 200045](https://github.com/user-attachments/assets/3886b3c5-c1b2-43d4-9181-922983603176)
---

### Threat Detection with MS Sentinel Analytics
Create analytics rule to detect Azure VM deletion using given KQL rule query

![Screenshot 2024-09-24 203348](https://github.com/user-attachments/assets/fd87e7c0-d4bb-458a-9d8e-980eab31dec0)

Invoke incident by deleting the VM resource from the resource group

![Screenshot 2024-09-24 203611](https://github.com/user-attachments/assets/a405eedd-a0cb-4478-93fd-c1b96d72da5a)

New incident is created in the Incidents dashboard

![Screenshot 2024-09-24 204600](https://github.com/user-attachments/assets/ff96bcd4-b832-4ad7-9a51-2fea5172b5af)
---

### Automation in MS Sentinel 
Create automation rule to take the action of assigning an incident to an owner

![Screenshot 2024-09-24 231045](https://github.com/user-attachments/assets/609ac89e-ae5d-43a0-a19d-a6baaf0449d0)

