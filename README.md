# SIEMmap
Used Azures resources such as VM, Log Analytics, and Sentinel (SIEM) to gather failed RDP attempts from Windows Event Log on the VM. The Powershell script in this repo is not made by me. Josh Madakor on youtube/LinkedIN published it to complete this lab to gain an  understanding of Azure and the resources. The script send the failed attacks IP addresses that are found in Windows Event Log to a 3rd party to get the GEO data so I can plot the info in our map within the Sentinel SIEM.   
More information as well as screenshots can be found on my project page wesbite. https://tylerutsinger.com/projects.html

3rd party API used ipgeolocation.io
Language used PowerShell to extract the logon logs. 
