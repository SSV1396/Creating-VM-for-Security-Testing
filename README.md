# Creating-VM-for-Security-Testing
Configuring the Microsoft Windows Sandbox &amp; Creating VM of Windows 10 for Security Testing

Objective: Given a scenario, implement host or application security solutions.

Description: A sandbox is an isolated virtual machine: anything run within a sandbox will impact only the virtual machine and not the underlying computer. The Microsoft Windows Sandbox first became available in Windows 10 Version 1903 released in 2019, and additional features have been added with recent Windows 10 updates to provide even more control. 

1. First check if your system has virtualization turned on. right-click the taskbar (at the bottom of the screen) and select Task Manager.
2. Click the Performance tab.
3. Under Virtualization, it must say “enabled.” If it says “disabled,” you will need to reboot and enter your BIOS or UEFI and turn on virtualization.
4. Now enable Windows Sandbox. In the Windows search box on the taskbar, enter Windows Features to open the Windows Features window.
5. Click the Windows Sandbox check box to turn on this feature.
6. To launch Windows Sandbox, click Start, and scroll down to Windows Sandbox, and then click Windows Sandbox. A protected virtual machine sandbox that looks like another Windows instance will start, as shown in Figure 1-8.
7. Explore the settings and default applications that come with the Windows Sandbox.
8. You can download a program through the Microsoft edge application in Windows Sandbox. (edge is included within Windows Sandbox along with a handful of other Windows applications, including access to OneDrive.)
Open edge and go to www.google.com to download and install the google chrome browser in the Windows Sandbox.
9. After the installation is complete, close the Windows Sandbox.
10. Now relaunch the Windows Sandbox. What happened to google chrome? Why?
11. Close all windows.
    
As Observed and practiced manually in Lab and as unable to download and install Windows Sandbox on Operating system Windows 10, followed the lesson in class and aware of steps and process of downloading and running Windows Sandbox.

## Project 1-4: Create a Virtual machine of Windows 10 for Security testing—Part 1

 Objective: Given a scenario, implement host or application security solutions.
 
 Description: If you were unable to install the Windows Sandbox in Project 1-3, a different virtual machine can be created in which new applications can be installed or configuration settings changed without affecting the base computer. In a virtual machine environment, the “host” computer runs a “guest” operating system. Security programs and testing can be conducted within this guest operating system without affecting the regular host operating system. In this project, you create a virtual machine using oracle VirtualBox software.
1. Open a web browser and enter the URL www.virtualbox.org (If you are no longer able to access the site through this web address, use a search engine to search for “oracle VirtualBox download.”)
  <img width="468" height="164" alt="image" src="https://github.com/user-attachments/assets/a86c5e90-e3ff-4b84-ab4d-208a2b13a782" />


2. Click Downloads (or a similar link or button).
    <img width="399" height="244" alt="image" src="https://github.com/user-attachments/assets/e8cc426c-2878-49c3-b335-a06dbd9906b2" />
    

3. Under VirtualBox binaries, select the latest version of VirtualBox to download for your specific host operating system. For example, if you are running Windows, select the version for “Windows hosts.”
4. Under VirtualBox xxx oracle VM VirtualBox extension Pack, click All supported platforms to download the extension package.
 <img width="386" height="192" alt="image" src="https://github.com/user-attachments/assets/6a14e621-3288-4f69-b5e8-1c6e81d758ce" />
 

5.Navigate to the folder that contains the downloads and launch the VirtualBox installation program VirtualBox xxx-nnnnn-hhh.exe.
 <img width="466" height="231" alt="image" src="https://github.com/user-attachments/assets/5ce832a9-5f7e-40bf-9c1c-7622346514c2" />
 

6. Accept the default configurations from the installation wizard to install the program.
 <img width="449" height="199" alt="image" src="https://github.com/user-attachments/assets/f6759513-5b06-47cd-ad96-93be366a7ccb" />


7. If you are asked “Would you like to install this device software?” on one or more occasions, click Install.
 <img width="448" height="251" alt="image" src="https://github.com/user-attachments/assets/91135400-a0a1-4533-b094-2947a94b63f3" />
 


8. When completed, click Finish to launch VirtualBox.
 <img width="437" height="237" alt="image" src="https://github.com/user-attachments/assets/d24456bc-4390-4f1c-97a8-6aa60b2d5029" />
 


9. Now install the VirtualBox extensions. click File and then click Preferences.
 <img width="468" height="267" alt="image" src="https://github.com/user-attachments/assets/d114daa2-07f4-4730-9458-af74d5ec6d33" />
 

10. Click Extensions.
 <img width="468" height="267" alt="image" src="https://github.com/user-attachments/assets/4a0f625c-f394-46ce-afff-bea81368327f" />
 


11. Click the Add a package icon on the right side of the screen.
 <img width="468" height="126" alt="image" src="https://github.com/user-attachments/assets/a602c05c-0f8d-4777-8985-6b39846dd52f" />
 


12. Navigate to the folder that contains the extension pack downloaded earlier to select that file. click Open.
 <img width="468" height="292" alt="image" src="https://github.com/user-attachments/assets/5c8d5496-cbd4-4c31-83c0-328d45062a56" />
 


13. Click Install. Follow the necessary steps to complete the default installation.

<img width="390" height="175" alt="image" src="https://github.com/user-attachments/assets/fc723613-c56b-4949-8147-91fc74c55f6d" />


14. Remain in VirtualBox for the next project to configure VirtualBox and install the guest operating system.
 <img width="459" height="192" alt="image" src="https://github.com/user-attachments/assets/0f8c2d32-f105-4477-9957-d85afafaeb54" />
 


## Project 1-5: Create a Virtual machine of Windows 10 for Security testing—Part 2

## Objective: given a scenario, implement host or application security solutions.
## Description: After installing VirtualBox, the next step is to create the guest operating system. For this project, Windows 10 will be installed. different options are available for obtaining a copy of Windows:
● A retail version of the software can be purchased.
● If you or your school is a member of the Microsoft azure dev Tools for Teaching program, the operating system software and a license can be downloaded. See your instructor or lab supervisor for more information.
● A 90-day evaluation copy can be downloaded and installed from the Microsoft Technet evaluation center(www.microsoft.com/en-uS/evalcenter/evaluate-windows-10-enterprise).
1. Obtain the ISO image of Windows 10 using one of the preceding options and save it on the hard drive of the computer.
2. Launch VirtualBox.
   <img width="459" height="246" alt="image" src="https://github.com/user-attachments/assets/d0ce9fda-1416-46d9-b353-a7993fc66734" />
 
3. Click New.
   <img width="460" height="246" alt="image" src="https://github.com/user-attachments/assets/e7bd7f48-8843-492f-9309-3a41857024cb" />
   

5. In the name: box, enter Windows 10 as the name of the virtual machine.
 <img width="465" height="249" alt="image" src="https://github.com/user-attachments/assets/846e2d19-a465-4ac0-8db4-be9e8e05fceb" />

6. Be sure that the Type: box displays Microsoft Windows and the Version: box changes to Windows 10 (xx-bit).
Click Next.
 <img width="450" height="236" alt="image" src="https://github.com/user-attachments/assets/e21f71d3-39e6-444e-85c0-c72447b73d0f" />

7. Under Memory size, accept the recommended size or increase the allocation if you have sufficient RAM on your computer. Click Next.
 <img width="464" height="249" alt="image" src="https://github.com/user-attachments/assets/8e260fcb-8406-43de-9af1-85d9282ebaf1" />

8. Under hard disk, accept Create a virtual hard drive now. Click Create.
 <img width="459" height="246" alt="image" src="https://github.com/user-attachments/assets/b2830246-bc0d-43de-9da4-e1a000e4d493" />

9. Under hard drive file type, accept the default VId (VirtualBox disk Image). Click Next.
 <img width="464" height="246" alt="image" src="https://github.com/user-attachments/assets/ab7c5bc6-fd2f-4b8b-b324-893e209ebd50" />

10. Under Storage on physical hard drive, accept the default Dynamically allocated. Click Next.
 <img width="456" height="246" alt="image" src="https://github.com/user-attachments/assets/7e6c8a5b-5752-4b06-b333-0e25a8c302d5" />

11. Under File location and size, accept Windows 10. Click Create.
12. Now the configuration settings for the virtual machine are set. next you will load the Windows 10 ISO image. Click Settings.
 <img width="463" height="243" alt="image" src="https://github.com/user-attachments/assets/cf928aad-c6aa-4447-8dfd-a6fbd86acabf" />

13. In the left pane, click Storage.
 <img width="459" height="270" alt="image" src="https://github.com/user-attachments/assets/fd970ff9-c9ba-43d2-8ac2-b507357319a8" />

14. Under Controller: click Empty.
 <img width="460" height="322" alt="image" src="https://github.com/user-attachments/assets/f505a915-b22d-4536-9487-d6d0a7908cb7" />

15. In the right page under attributes, click the icon of the optical disc. 
 <img width="464" height="299" alt="image" src="https://github.com/user-attachments/assets/d6dcade9-0c22-42ea-b78c-466e9d62c2b7" />

16. Click Choose Virtual optical disk File.
 <img width="462" height="260" alt="image" src="https://github.com/user-attachments/assets/9b22d7c2-6ceb-4008-b4ec-950112b6334f" />

17. Navigate to the location of the Windows 10 ISO file and click Open. 
 <img width="445" height="223" alt="image" src="https://github.com/user-attachments/assets/265dd819-fad7-42d6-9f3b-74da4622458f" />

18. Click OK.
 <img width="430" height="219" alt="image" src="https://github.com/user-attachments/assets/b707137b-1260-49bf-b0a6-394de96e0068" />

19. Click Start to launch the Windows 10 ISo.
 <img width="429" height="219" alt="image" src="https://github.com/user-attachments/assets/d8e53d6a-188a-4391-a4b7-6d1d161112be" />

20. Follow the Windows 10 installation wizard to complete the installation.
 
<img width="460" height="374" alt="image" src="https://github.com/user-attachments/assets/a8583d6a-9e92-4a99-9aa6-6fb3a4d307bc" />

 <img width="457" height="314" alt="image" src="https://github.com/user-attachments/assets/8a0a76ff-7ac0-4ae3-914a-50871867702d" />
<img width="468" height="263" alt="image" src="https://github.com/user-attachments/assets/674421cf-98c8-4e27-b712-57b790890e9b" />

 <img width="468" height="263" alt="image" src="https://github.com/user-attachments/assets/63917b32-3431-4f35-bd19-b287cebf7aba" />

21. To close the Windows 10 guest operating system in VirtualBox, click File and then click Exit. 
21.Close all windows.
