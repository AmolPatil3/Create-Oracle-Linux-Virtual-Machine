# Oracle-Linux-Virtual-Machine

This project provides a comprehensive setup for creating and managing an Oracle Linux virtual machine. It includes pre-configured scripts and guidelines to simplify deployment, ensuring a seamless experience for developers and system administrators. Perfect for learning, testing, or deploying Oracle Linux environments.

**1. Installation of Oracle Virtual Box**
===================

**Step 1:** Download VirtualBox

Go to the official Oracle VirtualBox website https://www.virtualbox.org/ . Click on the "Downloads" link in the menu. Under "VirtualBox platform packages", click on the link for Windows hosts to download the installer.

**Step 2:** Run the Installer

Navigate to the folder where the installer file (e.g., VirtualBox-x.x.x-xxxxx-Win.exe) was downloaded. Double-click the installer to run it.

![image](https://github.com/user-attachments/assets/e80aa607-5194-45b1-bb14-81fdb60a8089)


**Step 3**: Follow the Installation Wizard

Welcome Screen: Click Next to begin the installation.

  Custom Setup:
  Choose the components you want to install. The default options are typically sufficient. Select the installation path if you want to change it, or leave it as default.

  ![image](https://github.com/user-attachments/assets/bbd949be-6aa3-44b8-b377-2f7b133d432f)


  Click Next.
  Shortcut Options: Check or uncheck options like creating a desktop shortcut and registering file associations as per your preference.

  ![image](https://github.com/user-attachments/assets/a1438589-d7e8-41d3-805a-9cab55da86e0)


  Click Next.
  Network Warning: A warning about resetting your network connection may appear. This is normal as VirtualBox installs virtual networking drivers.

  ![image](https://github.com/user-attachments/assets/2647e8ec-9b73-4278-bb04-ed49552ec758)


  Click Yes to proceed.
  Install: Click Install to begin the installation process. If prompted by User Account Control (UAC), click Yes to allow the installation.

  ![image](https://github.com/user-attachments/assets/05064318-83db-4c76-8ddf-7fad9c5ff647)


**Step 4:** Complete the Installation

Once the installation is complete, ensure the Start Oracle VM VirtualBox after installation box is checked. Click Finish to launch VirtualBox.

![image](https://github.com/user-attachments/assets/043eb5fc-d003-48b0-892a-927686e1251d)


**Step 5:** Verify Installation

Open Oracle VM VirtualBox Manager. Confirm that the application launches correctly and that no errors are shown. You are now ready to create and manage virtual machines!

![image](https://github.com/user-attachments/assets/28b998f7-4122-4edf-ae67-6cba6415d236)

**2. Installation of Oracle Linux 7.8 Virtual Machine**
===========================================

Step 1: Download Oracle Linux ISO

Visit the Oracle Linux Downloads page https://yum.oracle.com/oracle-linux-downloads.html?er=221886 
Download the Oracle Linux 7 ISO file (choose the latest release of Oracle Linux 7).

Step 2: Create a New Virtual Machine in VirtualBox

Open VirtualBox. Click on New in the toolbar. Name and Operating System: Name your VM (e.g., "Oracle Linux 7"). Set Type to Linux. Set Version to Oracle (64-bit).

![image](https://github.com/user-attachments/assets/7bebc619-97ef-4e1a-9aa0-e68e7de3f0cc)

Click Next.

Memory Size: Allocate at least 2 GB (2048 MB) of RAM. For better performance, 4 GB or more is recommended.

![image](https://github.com/user-attachments/assets/894e274b-d50c-4cfb-b847-3a70a25e5e8b)

Click Next.

Hard Disk: Select Create a virtual hard disk now. Click Create.

![image](https://github.com/user-attachments/assets/c8eb6007-2d43-40b1-b637-25394ae56cc8)

Hard Disk File Type: Choose VDI (VirtualBox Disk Image).

![image](https://github.com/user-attachments/assets/9f5cd79d-5d0c-461a-8975-4830525e4b7e)

Click Next.

Storage on Physical Hard Disk: Select Dynamically allocated for flexible disk space usage.

Click Next.

File Location and Size: Set the size of the virtual disk (at least 20 GB for Oracle Linux 7).

![image](https://github.com/user-attachments/assets/abbd4d3b-4c9c-44b6-8080-e4fc10b50d57)

Click Create.






















