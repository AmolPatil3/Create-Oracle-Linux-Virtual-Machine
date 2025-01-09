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

**Step 1:** Download Oracle Linux ISO

Visit the Oracle Linux Downloads page https://yum.oracle.com/oracle-linux-downloads.html?er=221886 
Download the Oracle Linux 7 ISO file (choose the latest release of Oracle Linux 7).

**Step 2:** Create a New Virtual Machine in VirtualBox

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

**Step 3:** Configure the Virtual Machine

Select your new virtual machine in the VirtualBox Manager. Click Settings.

System:
Under the Processor tab, allocate at least 2 CPUs.

Storage:
In the Storage section, click on the Empty optical drive. Click the Disk icon next to the "Attributes" section and choose Choose a disk file.
Select the Oracle Linux 7 ISO file you downloaded earlier.
Click OK.

Network:
In the Network section, set Adapter 1 to NAT or Bridged Adapter, depending on your networking requirements.
Click OK to save settings.

![image](https://github.com/user-attachments/assets/da61b1ba-2ec2-4f9b-9541-783ab2970eaa)


**Step 4:** Start the Installation

Select the virtual machine and click Start.The virtual machine will boot from the Oracle Linux 7 ISO.In the boot menu, select Install Oracle Linux 7 and press Enter.

![image](https://github.com/user-attachments/assets/eb9b1a59-4032-4295-9c2d-91a2849121c3)


**Step 5:** Follow the Installation Wizard

Language Selection: Choose your preferred language and click Continue.

![image](https://github.com/user-attachments/assets/9f763d69-8dc6-4ef7-a6bb-4b9862280213)


Installation Summary: Date & Time: Set your timezone.

![image](https://github.com/user-attachments/assets/2830af0c-cebe-4c3d-b4af-f4307e625d5a)

![image](https://github.com/user-attachments/assets/b3624d82-3c2a-4cdd-9a57-a6d282198e91)

![image](https://github.com/user-attachments/assets/aa209a74-9c36-42cc-84fb-208baaf89ca4)

![image](https://github.com/user-attachments/assets/df7f2415-4bf6-4ce4-93bf-e814fcd33d07)

![image](https://github.com/user-attachments/assets/37054342-96df-4907-b839-6228beac9076)




Keyboard: Confirm or modify the keyboard layout.

Installation Destination: Select your virtual disk and click Done.

Network & Hostname: Enable the network connection if required.

Begin Installation:
Click Begin Installation.
Set Up User Accounts:
Root Password: Set the root (administrator) password.
Create a User: Optionally, create a non-root user account.






















