# Deploying-Log-Analytics-Agent

# Goal is to connect Azure VM to Log Analytics Workspace
- Why? Microsoft Defender can better protect your resources if it knows what's going on within your resources. 
- Log Analytics Workspace is within Microsoft Defender and Defender uses that data collected.


# Create a Log Anaytics Workspace
- Go to Microsoft Defender for Cloud and enable auto provisioning for log analtics agent for Azure VMs.
- Connect the azure vm to the LAW that you created
- Now the LAW agent will be installed on the vm and collect data. 
- Then Microsoft Defender will take the data and look for threats based on data collected.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/176020740-548e653b-3673-4b95-b20b-75b96e918cbc.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>



# Use Cases: Create LAW and connect a VM to the LAW for Microsoft Defender to evaluate
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/176021100-4f3c52e9-9c3b-4cfe-b6b8-4364cbfce4d7.png" height="45%" width="45%" alt="Azure LAW"/>

<p/>


# Enable auto-provisioning for Azure Virtual Machines and connect the LAW 
- Microsoft Defender for Cloud > Environment Settings > Auto provisioning > enable Log analytics agent for Azure VMs 
- Connect the LAW that you want Azure VMs to link to
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/176021660-d295d79d-8cf4-44eb-a998-33c4cb55ad96.png" height="155%" width="155%" alt="Azure LAW"/>

<p/>

