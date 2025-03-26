
<p align="center">
<img width="350" alt="Image" src="https://github.com/user-attachments/assets/3fe557c5-5494-4138-8b68-8537380a54c1" />

<h1>Creating a Windows 10 Virtual Machine (Azure)</h1>
This tutorial shows you how to create and use a basic Windows 10 virtual machine using Azure through remmote desktop .<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (Windows App for Mac)


<h2>Operating Systems Used </h2>


- Windows 10 Pro



<h2>Deployment and Configuration Steps</h2>

<p align="center">

**Step 1: Open up "www.portal.azure.com" and get logged in**
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/1e130839-098b-4251-b5d5-379f335668c4" />
</p>
<p>
Creating an account is simple if you do not already have one
</p>
<br /> 

**Step 2: From the home page click on Resource Groups then click on create, either on the top or bottom of the page**
<p>
<img width="700" alt="Image" src="https://github.com/user-attachments/assets/2f882d89-976d-49ea-a6eb-2ad4c0c60df4" />
  <img width="700" alt="Image" src="https://github.com/user-attachments/assets/0592b555-2539-4f4d-b6b3-6ab5903e3d81" /> 
</p>
<p>
Creating your own resource group is optional because one will autoatically be created if you do not already have one, but I find it easier to create your own when dealing with multiple Virtual machines or resource groups. 

  **Step 3: Back on the home screen click on Virtual machine and create** 
</p>
<br />

<p>
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/eb57943c-7d41-45da-a1e4-874cf4bb24fe" /></p>
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/1fbd054f-b409-4bee-88e8-c908f4eafa7d" />
<p>
  
  **Step 4: Change details of Virtual Machine** 
</p>
<br />
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/8b6617f3-502f-40bf-8e81-7d3e72b5ad36" />
<img width="800" alt="Image" src="https://github.com/user-attachments/assets/d844f5f8-9158-4989-8bfa-465457a8f32f" />

-Make sure "Resource group" is set to the one you just created

-Name your Virtual machine 

-Set your region as the same region you used for your resouce group 

-Change "Image" to Windows 10 Pro as this will be the operating system used

-Change size depending on what you'll be using the virtual machine for. (Size shown is recommended) 

-Set-up and username and password (You'll need this to log in to VM)

-Check licensing box

  **Step 5: Review and Create**

  <img width="800" alt="Image" src="https://github.com/user-attachments/assets/b98fbdc9-8536-4d0f-922c-1a828f7119eb" />
  
  Now that we have created a Resource group and a virtual machine within that resource group its time to use the virtual machine 

 **Step 6: Copy the public iP address of virtual machine and paste it on remote desktop (windows app for Mac)**  
 
 <img width="800" alt="Image" src="https://github.com/user-attachments/assets/1744e96c-d3ec-4010-b701-13c126865b8d" />

 <img width="500" alt="Image" src="https://github.com/user-attachments/assets/20593c9a-1333-4610-bb84-ff4282dda705" />

  **Step 7: Click on the VM you just created then enter username and password**
 <img width="1488" alt="Image" src="https://github.com/user-attachments/assets/11379a8a-5452-456d-9c69-ea3095108a82" />
Once the username and password are entered (same used when creating VM on Azure) you should be free to browse the Windows 10 Virtual machine as you please. 
