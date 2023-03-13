# SynergyServicesWatcher




![1](https://user-images.githubusercontent.com/94911727/158199894-092228a9-f731-42d6-bef4-f6013be55ad3.jpg)


![2](https://user-images.githubusercontent.com/94911727/158199920-18ca86b0-0562-47b2-9ba7-7cf97810a3f6.jpg)



![3](https://user-images.githubusercontent.com/94911727/158199933-07a9eea6-8db6-46e8-93db-7b4e347aa9af.jpg)



![4](https://user-images.githubusercontent.com/94911727/158199940-b0c58a0f-b496-4070-a123-422cf3c91fee.jpg)


![5](https://user-images.githubusercontent.com/94911727/158199949-97ab049e-ae33-4af2-ac4f-660cee2ff429.jpg)



THE PROBLEM
Very often services running in a Windows Server stop fo various reasons.
For example Microsoft Exchange Server Services might stop due to lack of resources like memory.
In this specific case end users are not able to receive emails.


THE SOLUTION
We came across this issue multiple times.
Exchange, SQL Server, or other common services had to be manually started.
An engineer would have to remote to a server check which service was down and then try to start it.
During late hours it was impossible to know the status of services.
So we create a tool specific for our needs that we are sure will also help other follow engineers.
This free application will restart any stopped service which is marked as automatic.
It will also create daily logs of services automatically restarted so you can further check for issues. 


HOW TO USE THIS FREE TOOL

Download the file and unzip to a permanent folder under Program Files.
Start a command prompt as Administrator and run the batch: “_Install Service – RunAsAdmin.bat”

After setup open the “Configuration.exe” using Notepad for fine tuning if needed.
Don’t forget to add your own Services to ignore.

Go to Services and make sure Service “SynergyServicesWatcher” is set to Automatic..or Delayed.
Feel free to contact us for any further assistance.

SynergyServicesWatcher was checked by VirusTotal visit the link bellow for further details https://www.virustotal.com/gui/file/a33590b18af711e25a628f9cfdfce0b0694acdfe5c43a4458d373d495d884b46?nocache=1


Visit our website for more free tools and other helpful products: https://synergy-usa-llc.com
