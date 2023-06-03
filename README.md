# VPN-setup-via-Proton-VPN
This repository will reflect not only the significance of a VPN (Virtual Private Network), but it will also display how to install and utilize a VPN


<h2> Envirnoments used in this project consist of: <h2>

- Microsoft Azure (Virtual Machines)

- Remote Desktop
  
  
<h2> Operating Systems Used in this project: <h2>
    
- Windows 10 Pro(21H2)

  
<h2> Configuration Steps: <h2>
    
- Log in to Microsoft Azure
    
- Create a Virtual Machine 
    
- Connect to Windows 10 Pro using Remote Desktop
    
- Download ProtonVPN
    
- Setup VPN connection
    
- Test VPN

  
<h2> Environment Creation <h2>
  
- In this project we will be creating a virtual machine in Microsoft Azure running Windows 10 Pro. If you would like to follow along as I demomstrate, you can use this link to access the signup page: https://azure.microsoft.com/en-us/free/. Click “Start free” and create your account. Once you have an account go to the Azure homepage: https://portal.azure.com/.
  
- On Microsoft Azure homepage under the "azure services", create a resource group. After you've created the resource group click "Virtual Machines", now you will assign the virtual machine to the resource group you have created. While assigning the virtual machine to the resource group, you will select the name, region and operating systme image of the virtual machine (Windows 10 Pro). 
  
- Now select the size of the virtual machine. This is how much processing power we will give our machine. 2 vcpus and 16 GiB memory is recommended for this lab as the virtual machine will run much smoother when we log into it later on. 
  
- Set a username and password. Next, check the box at the bottom for “I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights. Last, click the Review + Create button. It will take a few minutes to deploy your virtual machine.  
  
  
<h2> Connect to the Virtual Machine <h2> 
  
- After creating the virtual machine, we will connect to it using Remote Desktop. If using Mac OS click command + spacebar, then type in " Microsoft Remote Desktop". If using Widnows search, type in "rdp" and launch Remote Desktop. Type in the Public IP address from our virtual machine. To find it, go to Azure > Home > Virtual Machines. Select the virtual machine we created. The Public IP address should be in the overview under Essentials or you can find it under the Networking section.

- You will be prompted with a login. Log in with the credentials you created for your virtual machine. On the first sign-in, you will need to choose your privacy settings. You can select no for all of them, and continue to sign in.
  
<h2> Set up ProtonVPN <h2> 
