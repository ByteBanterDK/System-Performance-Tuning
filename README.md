<h1>PC Performance Optimisation</h1>
<h2>Description</h2>
This project focuses on optimising the performance of a Windows PC by employing various tools and techniques to clean up the system, disable unnecessary services, and enhance overall system efficiency. The project includes disk clean-up, disabling startup programs, managing system resources, and upgrading hardware components.
<h2>Key Objectives:</h2>
Disk Clean-Up: Utilising built-in tools to remove temporary files and free up disk space.
Disabling Unnecessary Services: Identifying and disabling services that are not needed to improve system performance.
Deleting Temporary Files: Using the Run dialog to delete temporary files (%temp%, temp) to reclaim storage space.
Managing Startup Programs: Using Task Manager to disable unnecessary startup applications that slow down the boot process.
Clearing RAM Cache: Using Sysinternals Suite to clear the RAM cache and free up memory resources.
Adjusting Performance Options: Turning off visual effects and other settings that are not essential to improve performance.
Configuring Power Options: Editing power settings to optimise performance, such as setting the system to high performance mode.
Defragment and Optimise Drives: Running the defragmentation tool to optimise the organisation of data on the disk.
Resource Monitoring: Checking system performance using Resource Monitor to identify and address bottlenecks.
Using CCleaner and Malwarebytes: Installing and using these tools to clean up the system and remove malware.
Hardware Upgrades: Considering hardware upgrades such as adding more RAM, upgrading the CPU, GPU, or SSD to improve system performance.
<h2>Languages and Utilities Used</h2>
Languages: Bash, Command Prompt (CMD)
Utilities: Disk Clean-Up, Task Manager, Sysinternals Suite, Resource Monitor, CCleaner, Malwarebytes
<h2>Environments Used</h2>
Operating Systems: Windows 10 Pro
Virtual Machines: N/A
Tools: CMD, PowerShell, Sysinternals Suite
<h2>Program walk-through:</h2>
<p align="center">
Search Services in the windows search bar: <br/>
<img src="https://i.imgur.com/1XQPBk0.png"/>
<br />
<br />
Disabling services that are not essential can free up system resources and improve overall performance. Here are some services that can be safely disabled:
<body> Starting off with AllJoyn Router Service</body>
<img src="https://i.imgur.com/myJwq56.png">
AllJoyn Router Service: Not commonly used. Disabling it can free up system resources.
<img src="https://i.imgur.com/SuFGYkP.png">
<h3>In the image below with the red arrows pointing those are the services that needing to be disabled.</h3>
<img src="https://i.imgur.com/D3i8jhM.png">
Bluetooth Support Service: If you do not use Bluetooth devices, disabling this service can improve performance.
<br>
BranchCache: Used in corporate environments. Disabling it can be beneficial for personal use.
<br>
Certificate Propagation: If you do not use smart cards, this service can be disabled
<br />
<br />
Geolocation Service: If you do not use location-based apps, disabling this service can enhance privacy and performance.
<img src="https://i.imgur.com/y4bI84m.png">
Offline Files: Disabling this service can save resources if you do not use offline files.
Print Spooler: If you do not have a printer, you can disable this service to improve system performance.
Remote Registry: Disabling this service can improve security by preventing remote access to the registry.
<img src="https://i.imgur.com/KDU6u1I.png">
Smart Card: If you do not use smart cards, disabling this service can save system resources.
SysMain: Disabling can improve performance on older systems by stopping prefetch and superfetch operations.
<img src="https://i.imgur.com/gk1dqxk.png">
Windows Biometric Service: If you do not use biometric devices, this service can be disabled.
Windows Search: Disabling this service can improve performance, especially on systems with limited resources. (Personal choice)
<img src="https://i.imgur.com/epWMcpQ.png">
Moving on click on your keyboard hold both keys Windows + R then search %temp% and temp:
<img src="https://i.imgur.com/0c08YDM.png"> <img src="https://i.imgur.com/B2MfHaP.png"> 
<img src="https://i.imgur.com/VToPoS1.png"> <img src="https://i.imgur.com/TJ404VZ.png">
If this warning pops up, just tick the box then click on skip:
<img src="https://i.imgur.com/kDWcBei.png">
Search Task Manager in your search bar:
<img src="https://i.imgur.com/EWxjOfq.png">
Go on to startup Disabling startup programs helps speed up boot times and improve system performancance:
<img src="https://i.imgur.com/eQJzIGG.png">
Now procced to download this application by Microsoft Sysinternals Suite as Sysinternals Suite: A collection of powerful system utilities by Microsoft for diagnosing and troubleshooting Windows-related issues efficiently.
<img src="https://i.imgur.com/Cm7v6vx.png"> <img src="https://i.imgur.com/eT0DuiX.png">
Click on floder when downloaded is completed, then search RAMMAP, pick RAMMap64.exe:
<img src="https://i.imgur.com/J19AbjW.png"> <img src="https://i.imgur.com/4uWsL22.png">
Now when on the tool, click on empty then choose Empty Standby List this is for the Ram Cache.
<img src="https://i.imgur.com/TniL6tI.png">
Before Clicking on Empty Standby List:
<img src="https://i.imgur.com/EX2dKZP.png">
After:
<img src="https://i.imgur.com/rLYsC9t.png">
Adjust Appearance: Reducing visual effects and animations can enhance performance, making Windows run faster and more efficiently.
<img src="https://i.imgur.com/w7q5Yyz.png"> <img src="https://i.imgur.com/SrDL6EF.png">
Search Edit Power Plan:
<img src="https://i.imgur.com/0jf4vSB.png">
Click on advanced power settings, firstly Turn off hard disk after: Setting to 0 minutes prevents the hard disk from powering down, ensuring quick access and reducing delays.
<img src="https://i.imgur.com/ArRXlaw.png">
PCI Express Link State Power Management: Setting to OFF ensures consistent performance by preventing power-saving features that can cause latency.
Processor Power Management:
Minimum processor state: Setting to 10% maintains efficient power use while keeping the processor active.
System cooling policy: Setting to active ensures the system stays cool by using active cooling methods.
Maximum processor state: Setting to 100% allows the processor to run at full performance when needed.
<img src="https://i.imgur.com/o9Rw3eS.png">
Go back to first page and click on power options then on the left side below control panel home "choose what the power buttons do":
<img src="https://i.imgur.com/moUgQ2J.png">
Power Plan Optimisation:
Turn off hard disk after: Setting to 0 minutes prevents the hard disk from powering down, ensuring quick access and reducing delays.
PCI Express Link State Power Management: Setting to OFF ensures consistent performance by preventing power-saving features that can cause latency.
Processor Power Management:
Minimum processor state: Setting to 10% maintains efficient power use while keeping the processor active.
System cooling policy: Setting to active ensures the system stays cool by using active cooling methods.
Maximum processor state: Setting to 100% allows the processor to run at full performance when needed.
Turn off fast startup: Disabling fast startup ensures a clean boot process, which can help resolve issues related to system updates and hardware changes.
<img src="https://i.imgur.com/nfvmY21.png">
Adjusting System Settings
Notifications:
Go to Settings > System > Notifications & actions.
<img src="https://i.imgur.com/2Ov4Mz3.png"> <img src="https://i.imgur.com/AoMkuHB.png">
Turn off "Show me the Windows welcome experience after updates," "Suggest ways I can finish setting up my device," and "Get tips, tricks, and suggestions as you use Windows."
<img src="https://i.imgur.com/rwxzzYJ.png">
Remote Desktop:
Go to Settings > System > Remote Desktop.
Turn off Remote Desktop.
<img src="https://i.imgur.com/cFUpLXv.png">
Personalisation:
Go to Settings > Personalisation > Start.
Turn off all options.
<img src="https://i.imgur.com/Rw2W4lx.png">
Taskbar:
Go to Settings > Personalisation > Taskbar.
Turn off all options.
<img src="https://i.imgur.com/rt5fcM0.png"> <img src="https://i.imgur.com/1wGXLQr.png">
Game Bar and Game Mode:
Go to Settings > Gaming > Game bar, and turn off Captures.
Turn off the game bar.
<img src="https://i.imgur.com/4wYmMV3.png"> <img src="https://i.imgur.com/kEC0ZSg.png">
Go to Settings > Gaming > Game Mode.
Turn off Game Mode.
<img src="https://i.imgur.com/LanhqVa.png">
Adjusting Privacy Settings
General:
Go to Settings > Privacy > General.
Turn off all options.
<img src="https://i.imgur.com/lZvl0o8.png">
Speech:
Go to Settings > Privacy > Speech.
Turn off online speech recognition.
<img src="https://i.imgur.com/vDPP6FX.png">
Inking and Typing Personalisation:
Go to Settings > Privacy > Inking & typing personalisation.
Turn off inking and typing personalisation.
<img src="https://i.imgur.com/XJujKvA.png">
Diagnostics & Feedback:
Go to Settings > Privacy > Diagnostics & feedback.
Turn off all options.
<img src="https://i.imgur.com/NqjJ2oM.png">
Activity History:
Go to Settings > Privacy > Activity history.
Turn off all options.
<img src="https://i.imgur.com/V5PU4Il.png">
Location:
Go to Settings > Privacy > Location.
Turn off location.
<img src="https://i.imgur.com/UK2cAIz.png">
Voice Activation:
Go to Settings > Privacy > Voice activation.
Turn off voice activation.
<img src="https://i.imgur.com/kTYTDeB.png">
App Diagnostics:
Go to Settings > Privacy > App diagnostics.
Turn off app diagnostics.
<img src="https://i.imgur.com/SoWyhE0.png">
Benefits
Improved Performance: Reduces boot times and increases system responsiveness.
Enhanced Security: Disabling unnecessary services and features reduces potential attack vectors.
Increased Privacy: Limits data sharing and background activity, enhancing user privacy.
Optimised Resource Usage: Frees up system resources for more critical tasks.
Software Updates
Regularly update Windows and graphics card drivers using tools like NVIDIA GeForce Experience to ensure optimal performance and security.
<img src="https://i.imgur.com/cRxWaA8.png"> <img src="https://i.imgur.com/GOU6cj5.png">
Search Everything in your preferred search engine:
Description: Everything is a lightweight and powerful search tool for Windows that indexes your files and folders, enabling instant search results.
<img src="https://i.imgur.com/i4arh8O.png">
Benefits:

Speed: Provides almost instantaneous search results by indexing all files and folders.
Efficiency: Uses minimal system resources while running in the background.
User-Friendly: Simple interface with advanced search capabilities.
Accuracy: Displays real-time changes and updates, ensuring search results are always current.
Comprehensive Search: Allows searching by file name, location, size, date modified, and other attributes.
<img src="https://i.imgur.com/M2G6COF.png">
Search Disk Cleanup on windows search bar:
<img src="https://i.imgur.com/1XydzA4.png">
Tick everything in the box under files to delete:
- Frees Up Space: Removes temporary files, system cache, and other unnecessary data.
- Improves Performance: Reduces clutter on the hard drive, which can speed up the system.
- Maintains System Health: Regular use can help prevent issues caused by lack of storage space.
<img src="https://i.imgur.com/wNjQiLM.png"> <img src="https://i.imgur.com/120sBfJ.png">
Then search Defragment and Optimise Drives:
<img src="https://i.imgur.com/zR9waeb.png">
- Improves Access Speed: Reduces the time it takes for the system to read and write files.
- Enhances Overall Performance: Streamlines data storage for faster access and better performance.
- Scheduled Optimisation: Disabling this can prevent the system from slowing down during automatic maintenance.
<img src="https://i.imgur.com/2SROQiz.png">
Resource Monitor
- Identifies Resource Hogs: Helps identify processes that are consuming excessive CPU, memory, disk, or network resources.
- Boosts Performance: Allows you to terminate or manage resource-intensive processes to improve overall system performance.
<img src="https://i.imgur.com/80Q4wbe.png">
Search CCleaner on your preferred search engine:
- Frees Up Space: Removes unnecessary files and data.
- Improves Speed: Optimises the registry and system files for faster performance.
- Enhances Privacy: Cleans browsing history and cookies.
<img src="https://i.imgur.com/n2zH9lC.png">

Finally search Malwarebytes
- Protects Against Malware: Detects and removes various types of malware, including viruses, worms, and Trojans.
- Enhances Security: Provides real-time protection and scheduled scans to keep your system secure.
- Improves System Stability: Prevents malware from causing system slowdowns and crashes.
<img src="https://i.imgur.com/MouQucS.png">


