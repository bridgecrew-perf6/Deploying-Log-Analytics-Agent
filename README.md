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
