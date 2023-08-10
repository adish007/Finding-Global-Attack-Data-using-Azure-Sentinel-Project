# Finding-Global-Attack-Data-using-Azure-Sentinel-Project

Used Azure Sentinal, which is a SIEM(Security Information and Event Management) tool by Azure, to track global security incidents on reduced security Virtual Machine.
Then used a custom PowerShell script to extract data from Windows Event Viewer of the VM. In this data all of the failed login attempts are recorded. Forwarded this 
data to third party API to derive geolocation data about where the attacks were coming from. Then used Azure Sentinels workbook to display global attack data on 
world map according to physical location and magnitude of attacks. 
