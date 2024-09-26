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

<h2>Additional Techniques</h2>
<ul>
  <li><strong>OCCT (OverClock Checking Tool)</strong>: A powerful monitoring tool that provides detailed information about your system's performance and stability. It allows you to run stress tests on your CPU, GPU, and power supply, and provides a certification report indicating system stability.</li>
    <li><strong>Browser Optimisation</strong>: Clear cached data and manage extensions to enhance browser performance and privacy.</li>
    <li><strong>Adjusting Virtual Memory Settings</strong>: Modifying the paging file size can optimise virtual memory usage, which is especially beneficial for systems with limited RAM.</li>
    <li><strong>Uninstalling Unused Programs</strong>: Removing programs that you no longer use can free up valuable disk space and system resources.</li>
    <li><strong>Windows Memory Diagnostic</strong>: Use this tool to check for memory-related issues that could affect system performance.</li>
    <li><strong>System Restore Point Management</strong>: Manage system restore points to free up disk space and ensure efficient system operation.</li>
    <li><strong>Advanced SystemCare</strong>: A comprehensive system optimisation tool that offers features like junk file cleanup, registry repair, and privacy protection.</li>
</ul>

<h2>Languages and Utilities Used</h2>
<ul>
    <li><strong>Languages</strong>: Bash, Command Prompt (CMD), PowerShell, Python, JavaScript</li>
    <li><strong>Utilities</strong>: Disk Clean-Up, Task Manager, Sysinternals Suite, Resource Monitor, CCleaner, Malwarebytes, OCCT, Advanced SystemCare</li>
</ul>

<h2>Environments Used</h2>
<ul>
    <li><strong>Operating Systems</strong>: Windows 10 Pro, Windows 11</li>
    <li><strong>Virtual Machines</strong>: VMware, VirtualBox</li>
    <li><strong>Tools</strong>: CMD, PowerShell, Sysinternals Suite, OCCT</li>
</ul>

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
<img src="https://github.com/user-attachments/assets/a99a6ade-9e06-4790-b37c-e3f671ea498b"> 

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
<img src="https://github.com/user-attachments/assets/eb16c147-a7d3-4312-a1ac-f1e0e06ce61b">

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

<h3>OCCT (OverClock Checking Tool)</h3>
<p>OCCT is a powerful monitoring tool that provides detailed information about your system's performance and stability. It is particularly useful for users who want to ensure their system is running optimally.</p>

<h4>Downloading OCCT</h4>
<ul>
    <li>Visit the official OCCT website:
<img src="https://github.com/user-attachments/assets/18585299-99c3-4b9a-963f-7129a0be46b7">
    <li>Click on the "Discover NOW" button on the homepage.</li>
<img src="https://github.com/user-attachments/assets/fc6746a3-36c2-4bde-a1ee-5d6fd5fb3102">
    <li>A new page will appear with four options: Personal, Pro, Enterprise, and Enterprise+. Select "Personal."</li>
<img src="https://github.com/user-attachments/assets/ade997a7-cd38-4ed3-bd5c-107951a7f656">
    <li>Click on the "Download" button that appears on the new page, indicated by a download logo with an arrow.</li>
<img src="https://github.com/user-attachments/assets/92b0bdcb-dbc5-44f1-abf7-17ca2508d08a"
    <li>Run the installer and follow the on-screen instructions to complete the installation.</li>
</ul>

<h4>Features of OCCT</h4>
<ul>
    <li><strong>Stability Test:</strong> OCCT allows you to run stress tests on your CPU, GPU, and power supply to ensure they can handle high loads without crashing.</li>
<img src="https://github.com/user-attachments/assets/6acc0dc9-c115-4af1-ae3a-c2d6e3e90015">
    <li><strong>Stability Certification Benchmark:</strong> After running tests, OCCT provides a certification report that indicates the stability of your system under stress.</li>
<img src="https://github.com/user-attachments/assets/d7c6ef93-a68d-402a-8c4c-196eb32b5461">
    <li><strong>Benchmarking:</strong> OCCT includes benchmarking features that allow you to compare your system's performance against previous results or other systems.</li>
<img src="https://github.com/user-attachments/assets/7667438e-9ff7-4d25-b729-1dbc6b982e63">
    <li><strong>Monitoring:</strong> OCCT continuously monitors system parameters such as CPU temperature, voltage, and usage, providing real-time feedback on system health.</li>
<img src="https://github.com/user-attachments/assets/8bf8f1c8-bc64-48c1-b2c5-fc2e926d0994">
    <li><strong>System Info:</strong> The tool displays detailed information about your hardware, including CPU, GPU, RAM, and motherboard specifications.</li>
<img src="https://github.com/user-attachments/assets/8b5b4ac9-25af-4435-a298-38aa96505dcd">
    <li><strong>Settings Page:</strong> OCCT offers a customisable settings page where you can adjust test parameters, monitoring options, and alerts based on your preferences.</li>
</ul>
<img src="https://github.com/user-attachments/assets/c06e9c60-6d87-45bd-a29f-0e17c6fb9b28">

<h4>Using OCCT</h4>
<p>Once installed, launch OCCT and select the type of test you want to perform. You can choose from CPU, GPU, or power supply tests. After selecting a test, click "Start" to begin monitoring your system's performance. Review the results and make any necessary adjustments to optimise your system.</p>


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

<h2>Additional Performance Optimisation Techniques</h2>

<h3>Uninstall Unused Programs</h3>
<p>Removing programs that you no longer use can free up valuable disk space and system resources.</p>
<ul>
    <li><strong>How to Uninstall:</strong> Go to Control Panel</li>
    <div>
        <img src="https://github.com/user-attachments/assets/cb1b771d-9b8f-4538-8ad6-9dcef322fd50" alt="Control Panel">
    </div>
    <li>Click on "Programs"</li>
    <div>
        <img src="https://github.com/user-attachments/assets/d7496b89-b58a-4c17-b18b-b89a91207aa6" alt="Programs">
    </div>
    <li>Programs and Features, select the program you want to uninstall, and click "Uninstall."</li>
    <div>
        <img src="https://github.com/user-attachments/assets/cf340025-8478-4671-94e5-d476a65ced2d" alt="Uninstall">
    </div>
</ul>

<h3>Adjust Virtual Memory Settings</h3>
<p>Modifying the paging file size can optimise virtual memory usage, which is especially beneficial for systems with limited RAM.</p>
<ul>
    <li><strong>Reasons to Choose a Custom Size:</strong>
        <ul>
            <li><strong>Performance Optimisation:</strong> Prevents frequent resizing of the paging file, enhancing system performance.</li>
            <li><strong>Stability:</strong> Ensures that applications have enough virtual memory available, reducing the risk of crashes.</li>
            <li><strong>Control:</strong> Allows you to allocate more virtual memory based on your specific needs and usage patterns.</li>
        </ul>
    </li>
    <li><strong>Recommended Custom Sizes:</strong>
        <ul>
            <li><strong>1 GB of RAM:</strong> Set to 1.5 GB to 2 GB (1536 MB to 2048 MB)</li>
            <li><strong>4 GB of RAM:</strong> Set to 6 GB to 8 GB (6144 MB to 8192 MB)</li>
            <li><strong>8 GB of RAM:</strong> Set to 12 GB to 16 GB (12288 MB to 16384 MB)</li>
            <li><strong>16 GB of RAM or more:</strong> 16 GB to 32 GB (16384 MB to 32768 MB)</li>
        </ul>
    </li>
    <li><strong>How to Adjust:</strong> Go to Control Panel.
        <div>
            <img src="https://github.com/user-attachments/assets/cb1b771d-9b8f-4538-8ad6-9dcef322fd50" alt="Control Panel">
        </div>
        Then click on System, and select Advanced system settings.
        <div>
            <img src="https://github.com/user-attachments/assets/004af6c3-4047-45b8-b3d5-ac81fcb5d725" alt="System Settings">
        </div>
        <div>
            <img src="https://github.com/user-attachments/assets/f714296e-5986-4cf8-b983-cacb275c24ef" alt="Advanced System Settings">
        </div>
        Under Performance Settings, go to the Advanced tab.
        <div>
            <img src="https://github.com/user-attachments/assets/224a1054-b56b-4625-a5fc-5c27693eeb90" alt="Performance Settings">
        </div>
        <div>
            <img src="https://github.com/user-attachments/assets/f6d94fd7-3ea3-4b99-be5c-12f1e6f330ee" alt="Virtual Memory">
        </div>
        Click on Virtual memory. Uncheck "Automatically manage paging file size for all drives," select your drive, and set a custom size.
    </li>
</ul>
<div>
    <img src="https://github.com/user-attachments/assets/99b31012-4029-4160-baf3-e92fe829c1c8" alt="Virtual Memory Settings">
</div>

<h3>Browser Optimisation</h3>
<p>Optimising your web browser can improve performance and reduce resource usage. Here are some tips specifically for Microsoft Edge:</p>

<ul>
    <li><strong>Improved Performance:</strong> Over time, cached data can accumulate and slow down your browser. Clearing it can help speed up loading times and improve overall responsiveness.</li>
    <li><strong>Enhanced Privacy:</strong> Clearing cookies and browsing history helps protect your personal information and prevents tracking by websites.</li>
    <li><strong>Free Up Space:</strong> Regularly clearing cached data can free up storage space on your device, which is especially beneficial for devices with limited storage capacity.</li>
    <li><strong>Resolve Issues:</strong> If you encounter problems with websites, clearing the cache can often resolve issues related to outdated or corrupted files.</li>
</ul>

<p>This process can be performed on various platforms, including:</p>
<ul>
    <li>Google Chrome</li>
    <li>Mozilla Firefox</li>
    <li>Brave</li>
    <li>DuckDuckGo</li>
    <li>Microsoft Edge</li>
    <li>Opera GX</li>
</ul>

<p>Here are specific steps for clearing browsing data in Microsoft Edge:</p>

<ul>
    <li><strong>How to Clear Browsing Data in Microsoft Edge:</strong>

  <li>Open Microsoft Edge and click on the three dots in the upper right corner.</li>
            <li>Select <strong>Settings</strong>.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/9182f22b-1aad-4c4d-8b0d-a122f22ba060" alt="Settings">
            </div>
            <li>In the left sidebar, click on <strong>Privacy, search, and services</strong>.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/825a1a24-8734-466d-be62-c5ca8fbaf0f1" alt="Privacy Settings">
            </div>
            <li>Scroll down to the <strong>Clear browsing data</strong> section and click on <strong>Choose what to clear</strong>.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/2f6b5824-632d-49ce-b2ca-5f13f8d90196" alt="Clear Browsing Data">
            </div>
            <li>Select the data types you want to clear (e.g., Cached images and files, Cookies and other site data, Browsing history).</li>
            <div>
                <img src="https://github.com/user-attachments/assets/416db57e-b363-4afa-afd3-dec419836e21" alt="Data Types">
            </div>
         Click on <strong>Clear now</strong>.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/18e8c294-c1fa-4e95-8ecd-99678fe5c389" alt="Clear Now">
            </div>
      
    </li>
</ul>

<ul>
    <li><strong>Clear SSL State:</strong> To clear the SSL state in Windows:
       
<li>Open the <strong>Control Panel</strong> by searching for it in the Start menu.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/cb1b771d-9b8f-4538-8ad6-9dcef322fd50" alt="Control Panel">
            </div>
            <li>Click on <strong>Network and Internet</strong>, then select <strong>Internet Options</strong>.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/42377da3-7f47-48e2-8aa6-25da8e6f8ba5" alt="Network and Internet">
            </div>
            <div>
                <img src="https://github.com/user-attachments/assets/fb526323-99a6-420d-b19b-6b2a9e6ee62b" alt="Internet Options">
            </div>
            <li>In the Internet Properties window, go to the <strong>Content</strong> tab.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/956d1a60-1b91-4d5c-81f1-bc0c3b57e5be" alt="Content Tab">
            </div>
            <li>Click on the <strong>Clear SSL state</strong> button.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/3daa7c32-bb5e-4a92-8636-989f8078856c" alt="Clear SSL State">
            </div>
      
    </li>
</ul>

<ul>
    <li><strong>Disable Unused Extensions:</strong> Remove or disable browser extensions that you do not use frequently to improve performance.

  <li>Click on the three dots in the upper right corner of Microsoft Edge.</li> 
            <li>Select <strong>Extensions</strong>.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/71920b03-a200-4365-b991-6be9ac8dfda4" alt="Extensions">
            </div>
            <li>Review your installed extensions and click on <strong>Remove</strong> or toggle off any that you do not use.</li>
            <div>
                <img src="https://github.com/user-attachments/assets/b9ec8d0c-7e75-47dd-9bc9-3ffd4e20fa42" alt="Remove Extensions">
            </div>
    </li>
</ul>

<h3>Check for Malware</h3>
<p>Regularly scanning for malware is crucial for maintaining system performance and security.</p>

<ul>
    <li>
        <strong>Windows Security Scan:</strong> 
        Use Windows Security to perform a full system scan. Go to Settings, then Update & Security, and select Windows Security. 
        Click on Virus & threat protection. For more detailed information, check out my other repository on 
        <a href="https://github.com/ByteBanterDK/WinFullScan">Windows Security Scan</a>.
    </li>
</ul>
<div>
    <img src="https://camo.githubusercontent.com/a7dcc2b008808918904e4824370571828c82683ef79f7c2af72bf71ba4376c52/68747470733a2f2f692e696d6775722e636f6d2f52424148666a512e706e67" alt="Windows Security Scan">
</div>

<ul>
    <li>
        <strong>Malicious Software Removal Tool (MRT):</strong> 
        Run MRT by searching for "MRT" in the Start menu and following the prompts to scan for malware. 
        For more information, visit my GitHub repository on <a href="https://github.com/ByteBanterDK/SecureScanM">MRT</a>.
    </li>
</ul>
<div>
    <img src="https://github.com/user-attachments/assets/c5befb1a-6d86-4c16-a211-35545cfbd4f4" alt="Malicious Software Removal Tool">
</div>
<ul>
    <li>
        <strong>Malwarebytes:</strong> 
        Install and run Malwarebytes to perform a thorough scan for malware and other threats.
    </li>
</ul>
<div>
    <img src="https://i.imgur.com/MouQucS.png" alt="Malwarebytes">
</div>

<ul>
    <li>
        <strong>Additional Checks:</strong> 
        Consider using tools like AdwCleaner to remove adware and potentially unwanted programmes (PUPs).
    </li>
</ul>
<div>
    <img src="https://github.com/user-attachments/assets/9a66c1f0-e69d-4deb-bdd0-e2e0c90bdc0e" alt="AdwCleaner">
</div>

<h3>Windows Memory Diagnostic</h3>
<p>The Windows Memory Diagnostic tool helps identify memory-related issues that could affect system performance.</p>
<ul>
    <li><strong>How to Use:</strong> Search for "Windows Memory Diagnostic" 
    <div>
        <img src="https://github.com/user-attachments/assets/25fdd7c2-cba9-4d67-a366-fdfae75e320f" alt="Windows Memory Diagnostic">
    </div>
    in the Start menu, select "Restart now and check for problems," and follow the prompts to check your system's RAM for errors.</li>
    <div>
        <img src="https://github.com/user-attachments/assets/95ff836c-dc96-488a-8d08-79fac121bd34" alt="Memory Diagnostic Results">
    </div>
    
<p>When you restart your computer, the Windows Memory Diagnostic tool will run a series of tests on your system's RAM. It will check for any errors or issues that could be causing performance problems. The results will be displayed after the tests are complete, allowing you to take appropriate action if any issues are found.</p>

<div>
    <img src="" alt="Memory Diagnostic">
</div>

<h3>System Restore Point Management</h3>
<p>Managing system restore points can help free up disk space and ensure that your system is running efficiently.</p>

<ul>
    <li>
        <strong>How to Manage:</strong> 
        Go to Control Panel, then System.
        <div>
            <img src="https://github.com/user-attachments/assets/9c06adc2-eca7-41c4-a00c-319d2f28fa69" alt="System">
        </div>
        <div>
            <img src="https://github.com/user-attachments/assets/579948c5-0a56-44d7-8894-250371fa44b9" alt="System Protection">
        </div>
        select System Protection. Here, you can create, delete, or configure restore points.
        <div>
            <img src="https://github.com/user-attachments/assets/4e5166a6-0065-454d-b40b-f2e73db97d24" alt="Create Restore Point">
        </div>
        <div>
            <img src="https://github.com/user-attachments/assets/3aba71ef-134d-4dc3-80df-ca583f872c1d" alt="Configure Restore Points">
        </div>
    </li>
</ul>

<p>By managing your system restore points, you can remove older restore points that are no longer needed, which can help free up valuable disk space. Additionally, regularly creating restore points before making significant changes to your system can provide a safety net, allowing you to revert to a previous state if something goes wrong.</p>



<h3>Advanced SystemCare</h3>
<p>Advanced SystemCare is a comprehensive system optimisation tool that can help improve performance and clean up your PC.</p>

<ul>
    <li>
        <strong>Features:</strong> 
        It offers features like junk file cleanup, registry repair, privacy protection, and system optimisation. 
        Additionally, it includes an AI mode that intelligently scans your system for issues and recommends optimisations based on your usage patterns.
    </li>
</ul>
<ul>
    <li>
        <strong>How to Use:</strong> 
        Download and install Advanced SystemCare from the official website, then run the programme and follow the prompts to optimise your system. 
<img src="https://github.com/user-attachments/assets/fa3e9f4d-88d7-45d6-8c9a-2fd6fcd8f5c8">
You can choose between AI mode for automated scanning and manual scanning mode for a more hands-on approach.
<img src="https://github.com/user-attachments/assets/b101528b-bdc8-451c-be59-f4e881a2a626">
 <strong>Scan Options:</strong> 
        The scanning process includes various checks such as:
        <ul>
            <li>Privacy Sweep</li>
            <li>Junk File Clean</li>
            <li>Shortcut Fix</li>
            <li>Registry Clean</li>
            <li>System Optimisation</li>
            <li>Internet Boost</li>
            <li>Registry Defrag</li>
            <li>Disk Optimisation</li>
            <li>Anti-Virus Protection</li>
            <li>Firewall</li>
            <li>Hardware Health</li>
            <li>Software Health</li>
            <li>Spyware Removal</li>
            <li>Security Reinforcement</li>
            <li>Vulnerability Fix</li>
            <li>Disk Check</li>
<img src="https://github.com/user-attachments/assets/b21f977a-d617-4335-ac60-65d8becc7137">
 </ul>
    </li>
    <li>
        <strong>Auto-Fix Options:</strong> 
        During the scanning process, you can enable auto-fix options, which will automatically resolve detected issues. You can also untick the box to manually fix issues one by one. The auto-fix options include:
        <ul>
            <li>Auto Fix</li>
            <li>Auto Fix and Shut Down PC</li>
            <li>Auto Fix and Restart PC</li>
            <li>Auto Fix and Hibernate PC</li>
            <li>Auto Fix and Sleep PC</li>
        </ul>
<Img src="https://github.com/user-attachments/assets/31766abb-01ca-4d8c-981a-3297f81410a4">


<h3>Cache Management in DuckDuckGo</h3>
<p>When you browse the internet, your browser stores various types of data to improve your browsing experience. This data can include cached images, cookies, and browsing history. While this can speed up loading times and help websites remember your preferences, it can also raise privacy concerns. DuckDuckGo offers features to help you manage this data effectively.</p>

<h4>Clear Tabs</h4>
<p>The "Clear Tabs" feature in DuckDuckGo allows you to quickly close all open tabs in your browser. This is particularly useful for maintaining privacy and decluttering your browsing session. When you clear your tabs:</p>
<ul>
    <li><strong>Privacy Enhancement:</strong> Closing all tabs ensures that no one else can see your browsing activity if they access your device.</li>
    <li><strong>Resource Management:</strong> Having too many tabs open can consume system resources, leading to slower performance.</li>
    <li><strong>Focus:</strong> By clearing tabs, you can reduce distractions and focus on the tasks at hand.</li>
</ul>

<h4>Clear Data</h4>
<p>The "Clear Data" feature is a more comprehensive tool that allows you to delete various types of stored data from your browser. This can include:</p>
<ul>
    <li><strong>Cached Images and Files:</strong> These are stored copies of web pages and images that help load sites faster on subsequent visits.</li>
    <li><strong>Cookies:</strong> Small files that websites use to remember your preferences and login information.</li>
    <li><strong>Browsing History:</strong> A record of the websites you have visited.</li>
    <li><strong>Site Data:</strong> Additional data stored by websites, such as local storage or session storage.</li>
</ul>

<h4>Benefits of Clearing Data</h4>
<ul>
    <li><strong>Enhanced Privacy:</strong> Regularly clearing your data helps protect your personal information and browsing habits.</li>
    <li><strong>Improved Performance:</strong> Cached data can accumulate and slow down your browser.</li>
    <li><strong>Troubleshooting:</strong> Clearing cached data and cookies can often resolve issues related to outdated or corrupted files.</li>
</ul>

<h4>How to Use These Features</h4>
<p>To use the "Clear Tabs" and "Clear Data" features in DuckDuckGo:</p>
<ol>
    <li><strong>Open DuckDuckGo:</strong> Launch the DuckDuckGo browser or app.</li>
    <li><strong>Access Settings:</strong> Navigate to the top of the page, usually represented by a fire logo  or similar.</li>
    <li><strong>Select Clear Tabs or Clear Data:</strong> Choose the appropriate option based on your needs.</li>
    <li><strong>Confirm Action:</strong> Follow any prompts to confirm that you want to clear your tabs or data.</li>
<img src="https://github.com/user-attachments/assets/2e7b8e6c-6fdf-4d27-8e62-afa001229e68">
</ol>

<h2>Conclusion</h2>
<p>This project successfully implemented various techniques to optimise Windows PC performance. By cleaning the system, disabling unnecessary services, and effectively managing resources, we achieved significant improvements in speed and efficiency.</p>

<h2>Lessons Learned</h2>
<p>I learned the importance of regular maintenance and the impact of system settings on performance. Additionally, I gained hands-on experience with various tools that can enhance system efficiency.</p>

<h2>Future Work</h2>
<p>I plan to explore more advanced optimisation techniques and stay updated on new tools that can further enhance system performance. I will document any new findings and share them with the community.</p>

<h2>Get in Touch</h2>
<p>If you have any questions about this project or would like to collaborate on future endeavours, feel free to reach out to me at <a href="mailto:DenisKTechnology@protonmail.com">DenisKTechnology@protonmail.com</a>.</p>
    <a href="mailto:DenisKTechnology@protonmail.com">DenisKTechnology@protonmail.com</a>
</p>
