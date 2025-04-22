<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>
Welcome to my first in-depth tutorial. In this guide, we will begin by creating a virtual machine (VM) using Microsoft Azure via the Azure Portal.

Virtual machines are essentially remote computers that allow us to run and test software in a controlled environment. This helps protect our physical machines from potential issues or malfunctions during setup or experimentation.
![vm](https://github.com/user-attachments/assets/5bff25ab-7706-41a1-9ddd-c5a30ff319bd)


<p>
Once your virtual machine has been successfully deployed, the next step is to connect to it using Remote Desktop Protocol (RDP). This allows you to interact with the virtual machine just like you would with a local computer.
</p>
<br />

![image alt](https://github.com/XanthquanM/osticket-prereqs/blob/878d8c759ebcf1847f69cd26700cee87486b64e1/Screenshot%202025-04-22%20103634.png)

Now that you have successfully connected to your virtual machine, the next step is to enable Internet Information Services (IIS), which will allow the VM to serve web content. This is an essential step in preparing the environment for applications such as osTicket.

To Enable IIS with CGI:
On your virtual machine, open the Control Panel.

Click on Programs.

Under Programs and Features, select Turn Windows features on or off (located in the left sidebar).

In the Windows Features dialog that appears:

Check the box next to Internet Information Services.

Expand the Internet Information Services section.

Under Web Management Tools and World Wide Web Services, ensure that necessary subcomponents are also selected.

Specifically, expand Application Development Features and check CGI.

Click OK to apply the changes.

Windows will now install and enable IIS with CGI support. Once completed, your virtual machine will be ready to host web applications.
</p>
<br />

![image alt]()

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
