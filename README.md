<h1>PC Performance Optimisation</h1>

<h2>Description</h2>
<p>This project focuses on optimising the performance of a Windows PC by employing various tools and techniques to clean up the system, disable unnecessary services, and enhance overall system efficiency. The project includes disk clean-up, disabling startup programs, managing system resources, and upgrading hardware components.</p>

<h2>Ownership Statement</h2>
<p>This project and all associated files are the original work of ByteBanterDK. Should you utilise any part of this project, please ensure compliance with the relevant laws and regulations in your jurisdiction, including but not limited to copyright laws in the United Kingdom. For any inquiries or collaboration opportunities, please contact me at <a href="mailto:DenisKTechnology@protonmail.com">DenisKTechnology@protonmail.com</a>.</p>

<h2>Key Objectives</h2>
<ul>
    <li><strong>Disk Clean-Up:</strong> Utilising built-in tools to remove temporary files and free up disk space.</li>
    <li><strong>Disabling Unnecessary Services:</strong> Identifying and disabling services that are not needed to improve system performance.</li>
    <li><strong>Deleting Temporary Files:</strong> Using the Run dialog to delete temporary files (%temp%, temp) to reclaim storage space.</li>
    <li><strong>Managing Startup Programs:</strong> Using Task Manager to disable unnecessary startup applications that slow down the boot process.</li>
    <li><strong>Clearing RAM Cache:</strong> Using Sysinternals Suite to clear the RAM cache and free up memory resources.</li>
    <li><strong>Adjusting Performance Options:</strong> Turning off visual effects and other settings that are not essential to improve performance.</li>
    <li><strong>Configuring Power Options:</strong> Editing power settings to optimise performance, such as setting the system to high performance mode.</li>
    <li><strong>Defragment and Optimise Drives:</strong> Running the defragmentation tool to optimise the organisation of data on the disk.</li>
    <li><strong>Resource Monitoring:</strong> Checking system performance using Resource Monitor to identify and address bottlenecks.</li>
    <li><strong>Using CCleaner and Malwarebytes:</strong> Installing and using these tools to clean up the system and remove malware.</li>
    <li><strong>Hardware Upgrades:</strong> Considering hardware upgrades such as adding more RAM, upgrading the CPU, GPU, or SSD to improve system performance.</li>
</ul>

<h2>Languages and Utilities Used</h2>
<p><strong>Languages:</strong> Bash, Command Prompt (CMD)</p>
<p><strong>Utilities:</strong> Disk Clean-Up, Task Manager, Sysinternals Suite, Resource Monitor, CCleaner, Malwarebytes</p>

<h2>Environments Used</h2>
<p><strong>Operating Systems:</strong> Windows 10 Pro</p>
<p><strong>Virtual Machines:</strong> N/A</p>
<p><strong>Tools:</strong> CMD, PowerShell, Sysinternals Suite</p>

<h2>Program Walk-through</h2>
<p align="center">
    Search Services in the Windows search bar: <br/>
    <img src="https://i.imgur.com/1XQPBk0.png"/>
</p>

<p>Disabling services that are not essential can free up system resources and improve overall performance. Here are some services that can be safely disabled:</p>

<body>Starting off with AllJoyn Router Service</body>
<img src="https://i.imgur.com/myJwq56.png">
<p><strong>AllJoyn Router Service:</strong> Not commonly used. Disabling it can free up system resources.</p>
<img src="https://i.imgur.com/SuFGYkP.png">
<h3>In the image below, the red arrows point to the services that need to be disabled.</h3>
<img src="https://i.imgur.com/D3i8jhM.png">
<ul>
    <li><strong>Bluetooth Support Service:</strong> If you do not use Bluetooth devices, disabling this service can improve performance.</li>
    <li><strong>BranchCache:</strong> Used in corporate environments. Disabling it can be beneficial for personal use.</li>
    <li><strong>Certificate Propagation:</strong> If you do not use smart cards, this service can be disabled.</li>
    <li><strong>Geolocation Service:</strong> If you do not use location-based apps, disabling this service can enhance privacy and performance.</li>
    <li><strong>Offline Files:</strong> Disabling this service can save resources if you do not use offline files.</li>
    <li><strong>Print Spooler:</strong> If you do not have a printer, you can disable this service to improve system performance.</li>
    <li><strong>Remote Registry:</strong> Disabling this service can improve security by preventing remote access to the registry.</li>
    <li><strong>Smart Card:</strong> If you do not use smart cards, disabling this service can save system resources.</li>
    <li><strong>SysMain:</strong> Disabling can improve performance on older systems by stopping prefetch and superfetch operations.</li>
    <li><strong>Windows Biometric Service:</strong> If you do not use biometric devices, this service can be disabled.</li>
    <li><strong>Windows Search:</strong> Disabling this service can improve performance, especially on systems with limited resources. (Personal choice)</li>
</ul>

<p>Moving on, click on your keyboard, hold both keys Windows + R, then search %temp% and temp:</p>
<img src="https://i.imgur.com/0c08YDM.png"> 
<img src="https://i.imgur.com/B2MfHaP.png"> 
<img src="https://i.imgur.com/VToPoS1.png"> 
<img src="https://i.imgur.com/TJ404VZ.png"> 
<p>If this warning pops up, just tick the box then click on skip:</p>
<img src="https://i.imgur.com/kDWcBei.png">

<p>Search Task Manager in your search bar:</p>
<img src="https://i.imgur.com/EWxjOfq.png">
<p>Go on to startup. Disabling startup programs helps speed up boot times and improve system performance:</p>
<img src="https://i.imgur.com/eQJzIGG.png">

<p>Now proceed to download this application by Microsoft, Sysinternals Suite:</p>
<img src="https://i.imgur.com/cm7v6vx.png"> 
<img src="https://i.imgur.com/eT0DuiX.png">

<p>Click on the folder when the download is completed, then search RAMMAP, pick RAMMap64.exe:</p>
<img src="https://i.imgur.com/J19AbjW.png"> 
<img src="https://i.imgur.com/4uWsL22.png">

<p>Now when on the tool, click on empty then choose Empty Standby List. This is for the RAM Cache:</p>
<img src="https://i.imgur.com/TniL6tI.png">
<p>Before Clicking on Empty Standby List:</p>
<img src="https://i.imgur.com/EX2dKZP.png">
<p>After:</p>
<img src="https://i.imgur.com/rLYsC9t.png">

<p>Adjust Appearance: Reducing visual effects and animations can enhance performance, making Windows run faster and more efficiently.</p>
<img src="https://i.imgur.com/w7q5Yyz.png"> 
<img src="https://i.imgur.com/SrDL6EF.png">

<p>Search Edit Power Plan:</p>
<img src="https://i.imgur.com/0jf4vSB.png">
<p>Click on advanced power settings. Firstly, turn off hard disk after: Setting to 0 minutes prevents the hard disk from powering down, ensuring quick access and reducing delays.</p>
<img src="https://i.imgur.com/ArRXlaw.png">

<p><strong>PCI Express Link State Power Management:</strong> Setting to OFF ensures consistent performance by preventing power-saving features that can cause latency.</p>
<p><strong>Processor Power Management:</strong></p>
<ul>
    <li>Minimum processor state: Setting to 10% maintains efficient power use while keeping the processor active.</li>
    <li>System cooling policy: Setting to active ensures the system stays cool by using active cooling methods.</li>
    <li>Maximum processor state: Setting to 100% allows the processor to run at full performance when needed.</li>
</ul>
<img src="https://i.imgur.com/o9Rw3eS.png">

<p>Go back to the first page and click on power options, then on the left side below control panel home "choose what the power buttons do":</p>
<img src="https://i.imgur.com/moUgQ2J.png">

<p><strong>Power Plan Optimisation:</strong></p>
<ul>
    <li>Turn off hard disk after: Setting to 0 minutes prevents the hard disk from powering down, ensuring quick access and reducing delays.</li>
    <li>PCI Express Link State Power Management: Setting to OFF ensures consistent performance by preventing power-saving features that can cause latency.</li>
    <li>Processor Power Management:</li>
    <ul>
        <li>Minimum processor state: Setting to 10% maintains efficient power use while keeping the processor active.</li>
        <li>System cooling policy: Setting to active ensures the system stays cool by using active cooling methods.</li>
        <li>Maximum processor state: Setting to 100% allows the processor to run at full performance when needed.</li>
    </ul>
    <li>Turn off fast startup: Disabling fast startup ensures a clean boot process, which can help resolve issues related to system updates and hardware changes.</li>
</ul>
<img src="https://i.imgur.com/nfvmY21.png">

<p><strong>Adjusting System Settings:</strong></p>
<ul>
    <li><strong>Notifications:</strong> Go to Settings > System > Notifications & actions.</li>
    <img src="https://i.imgur.com/2Ov4Mz3.png"> 
    <img src="https://i.imgur.com/AoMkuHB.png">
    <li>Turn off "Show me the Windows welcome experience after updates," "Suggest ways I can finish setting up my device," and "Get tips, tricks, and suggestions as you use Windows."</li>
</ul>

<p><strong>Remote Desktop:</strong> Go to Settings > System > Remote Desktop. Turn off Remote Desktop.</p>
<img src="https://i.imgur.com/cFUpLXv.png">

<p><strong>Personalisation:</strong> Go to Settings > Personalisation > Start. Turn off all options.</p>
<img src="https://i.imgur.com/Rw2W4lx.png">

<p><strong>Taskbar:</strong> Go to Settings > Personalisation > Taskbar. Turn off all options.</p>
<img src="https://i.imgur.com/rt5fcM0.png"> 
<img src="https://i.imgur.com/1wGXLQr.png">

<p><strong>Game Bar and Game Mode:</strong> Go to Settings > Gaming > Game bar, and turn off Captures. Turn off the game bar.</p>
<img src="https://i.imgur.com/4wYmMV3.png"> 
<img src="https://i.imgur.com/kEC0ZSg.png">

<p>Go to Settings > Gaming > Game Mode. Turn off Game Mode.</p>
<img src="https://i.imgur.com/LanhqVa.png">

<p><strong>Adjusting Privacy Settings:</strong></p>
<ul>
    <li><strong>General:</strong> Go to Settings > Privacy > General. Turn off all options.</li>
    <img src="https://i.imgur.com/lZvl0o8.png">
    <li><strong>Speech:</strong> Go to Settings > Privacy > Speech. Turn off online speech recognition.</li>
    <img src="https://i.imgur.com/vDPP6FX.png">
    <li><strong>Inking and Typing Personalisation:</strong> Go to Settings > Privacy > Inking & typing personalisation. Turn off inking and typing personalisation.</li>
    <img src="https://i.imgur.com/XJujKvA.png">
    <li><strong>Diagnostics & Feedback:</strong> Go to Settings > Privacy > Diagnostics & feedback. Turn off all options.</li>
    <img src="https://i.imgur.com/NqjJ2oM.png">
    <li><strong>Activity History:</strong> Go to Settings > Privacy > Activity history. Turn off all options.</li>
    <img src="https://i.imgur.com/V5PU4Il.png">
    <li><strong>Location:</strong> Go to Settings > Privacy > Location. Turn off location.</li>
    <img src="https://i.imgur.com/UK2cAIz.png">
    <li><strong>Voice Activation:</strong> Go to Settings > Privacy > Voice activation. Turn off voice activation.</li>
    <img src="https://i.imgur.com/kTYTDeB.png">
    <li><strong>App Diagnostics:</strong> Go to Settings > Privacy > App diagnostics. Turn off app diagnostics.</li>
    <img src="https://i.imgur.com/SoWyhE0.png">
</ul>

<h2>Benefits</h2>
<ul>
    <li><strong>Improved Performance:</strong> Reduces boot times and increases system responsiveness.</li>
    <li><strong>Enhanced Security:</strong> Disabling unnecessary services and features reduces potential attack vectors.</li>
    <li><strong>Increased Privacy:</strong> Limits data sharing and background activity, enhancing user privacy.</li>
    <li><strong>Optimised Resource Usage:</strong> Frees up system resources for more critical tasks.</li>
</ul>

<h2>Software Updates</h2>
<p>Regularly update Windows and graphics card drivers using tools like NVIDIA GeForce Experience to ensure optimal performance and security.</p>
<img src="https://i.imgur.com/cRxWaA8.png"> 
<img src="https://i.imgur.com/GOU6cj5.png">

<h2>Search Everything</h2>
<p>Description: Everything is a lightweight and powerful search tool for Windows that indexes your files and folders, enabling instant search results.</p>
<img src="https://i.imgur.com/i4arh8O.png">

<h2>Benefits:</h2>
<ul>
    <li><strong>Speed:</strong> Provides almost instantaneous search results by indexing all files and folders.</li>
    <li><strong>Efficiency:</strong> Uses minimal system resources while running in the background.</li>
    <li><strong>User-Friendly:</strong> Simple interface with advanced search capabilities.</li>
    <li><strong>Accuracy:</strong> Displays real-time changes and updates, ensuring search results are always current.</li>
    <li><strong>Comprehensive Search:</strong> Allows searching by file name, location, size, date modified, and other attributes.</li>
</ul>
<img src="https://i.imgur.com/M2G6COF.png">

<h2>Disk Cleanup</h2>
<p>Search Disk Cleanup on the Windows search bar:</p>
<img src="https://i.imgur.com/1XydzA4.png">
<p>Tick everything in the box under files to delete:</p>
<ul>
    <li><strong>Frees Up Space:</strong> Removes temporary files, system cache, and other unnecessary data.</li>
    <li><strong>Improves Performance:</strong> Reduces clutter on the hard drive, which can speed up the system.</li>
    <li><strong>Maintains System Health:</strong> Regular use can help prevent issues caused by lack of storage space.</li>
</ul>
<img src="https://i.imgur.com/wNjQiLM.png"> 
<img src="https://i.imgur.com/120sBfJ.png">

<p>Then search Defragment and Optimise Drives:</p>
<img src="https://i.imgur.com/zR9waeb.png">
<ul>
    <li><strong>Improves Access Speed:</strong> Reduces the time it takes for the system to read and write files.</li>
    <li><strong>Enhances Overall Performance:</strong> Streamlines data storage for faster access and better performance.</li>
    <li><strong>Scheduled Optimisation:</strong> Disabling this can prevent the system from slowing down during automatic maintenance.</li>
</ul>
<img src="https://i.imgur.com/2SROQiz.png">

<h2>Resource Monitor</h2>
<ul>
    <li><strong>Identifies Resource Hogs:</strong> Helps identify processes that are consuming excessive CPU, memory, disk, or network resources.</li>
    <li><strong>Boosts Performance:</strong> Allows you to terminate or manage resource-intensive processes to improve overall system performance.</li>
</ul>
<img src="https://i.imgur.com/80Q4wbe.png">

<h2>Search CCleaner</h2>
<ul>
    <li><strong>Frees Up Space:</strong> Removes unnecessary files and data.</li>
    <li><strong>Improves Speed:</strong> Optimises the registry and system files for faster performance.</li>
    <li><strong>Enhances Privacy:</strong> Cleans browsing history and cookies.</li>
</ul>
<img src="https://i.imgur.com/n2zH9lC.png">

<h2>Search Malwarebytes</h2>
<ul>
    <li><strong>Protects Against Malware:</strong> Detects and removes various types of malware, including viruses, worms, and Trojans.</li>
    <li><strong>Enhances Security:</strong> Provides real-time protection and scheduled scans to keep your system secure.</li>
    <li><strong>Improves System Stability:</strong> Prevents malware from causing system slowdowns and crashes.</li>
</ul>
<img src="https://i.imgur.com/MouQucS.png">

<h2>Conclusion</h2>
<p>In this project, we successfully implemented various techniques to optimise the performance of a Windows PC. By cleaning up the system, disabling unnecessary services, and managing resources effectively, we achieved significant improvements in speed and efficiency.</p>

<h2>Lessons Learned</h2>
<p>Throughout this project, I learned the importance of regular maintenance and the impact of system settings on performance. Additionally, I gained hands-on experience with various tools that can enhance system efficiency.</p>

<h2>Future Work</h2>
<p>Moving forward, I plan to explore more advanced optimisation techniques and keep abreast of new tools that can further enhance system performance. I will also document any new findings and share them with the community.</p>

<h2>Get in Touch</h2>
<p>If you have any questions about this project or would like to collaborate on future endeavours, feel free to reach out to me at!</p>
<p>
    <img align="left" alt="ByteBanterDK | Gmail" width="22px" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn-1.webcatalog.io%2Fcatalog%2Fprotonmail%2Fprotonmail-icon.png&f=1&nofb=1&ipt=6df4d08d62fc42ad07c8ae70905a4a6c79ce00471af3644e6281517111e85d03&ipo=images"/> 
    <a href="mailto:DenisKTechnology@protonmail.com">DenisKTechnology@protonmail.com</a>
</p>
