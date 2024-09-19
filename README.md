# DevOps-Project-Multi-Tier-Bank-Application-Azure

![image](https://github.com/user-attachments/assets/98ff55b0-21d9-4adf-88d0-2353087a7da5)

Before running the Jenkins Job do the changes for parameters in application.properties file as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/672b2256-4fa4-4972-9423-59a626d54c56)

Create the service connection for Docker Registry, Maven Artifacts Feed and SonarQube. Then run the Azure DevOps Pipeline.

After running the Azure DevOps Pipeline the screenshot for SonarQube, Azure Artifacts Feed and the entry for Azure DNS Zone is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/8420eab7-b386-4d89-92ce-40291b69ba66)
![image](https://github.com/user-attachments/assets/a329f9eb-d050-43b3-94d5-80d31867cf50)
![image](https://github.com/user-attachments/assets/e91b7c92-00b7-4a30-a085-75326d442758)

Bank Application Pod, Service and Deployment will be created as shown in the screenshot attached below. The entry in MySQL database after registering the user is as as shown below.
![image](https://github.com/user-attachments/assets/da8d53c6-a344-49dd-8807-3cf321ae2e4e)

The ingress rule will be created as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/5574b9ac-45ef-42d3-98e2-3a75a50f834a)

Finally you can access the Bank Application as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/10b48acd-8379-4d2a-900b-51905b25ca4d)
![image](https://github.com/user-attachments/assets/c466ea26-0fd1-48cf-910a-df6107b37e95)

```
The bankapp-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry bankapp-auth --docker-server=https://bankappcontainer24registry.azurecr.io --docker-username=bankappcontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXOJ7eXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXMtTc -n bankapp
```
<br><br/>
<br><br/>
```
OpenJDK Docker Image is depricated so in this project eclipse-temurin docker image has been used as a base image in the Dockerfile. 
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:-  https://github.com/singhritesh85/Bank-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://github.com/Goldencat98/Bank-App.git
```
