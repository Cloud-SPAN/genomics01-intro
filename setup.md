---
layout: page
title: Setup
---

# Overview

This course is designed to be run on pre-configured Amazon Web Services Machine Images (AMIs), one AMI for each participant. All of the software and data used in the course are hosted on each AMI with the exception of three software tools: *Git Bash*, a *spreadsheet*, and the *Integrative Genomics Viewer*. These software tools will be run in the personal computer of each participant, either a laptop or desktop (tablets and iPads are not suitable). Please install the software tools in your personal computer before the course; directions to install them are given below. Git Bash is only needed if you will be using a Windows computer. It is a command-line interface, also known as as CLI and shell, which will allow you to access your AMI from your personal computer.

Please follow the instructions below to prepare your computer for the course. Option A uses an AMI; Option B runs all software in your personal computer.

- Required additional software + Option A  
  **OR**
- Required additional software + Option B

## Required additional software to install in your personal computer

This course requires Git Bash, a working spreadsheet and the IGV application. If you don't have a spreadsheet program already, you can use LibreOffice. It's a free, open source spreadsheet program. Directions to install the these applications are included below for each Windows, Mac OS X, and Linux systems.

> ## Windows
> > ## Installing Git Bash
> > - Download the [Git for Windows installer](https://git-for-windows.github.io/) which installs both Git and Git Bash. 
> > - Once the installer is downloaded, double click on it and follow the next steps.
> > - Click on "Next" four times (two times if you've previously installed Git). You don't need to change anything in the screens Information, Location, Components, and Start Menu.
> > - Select "Use the nano editor by default" and click on "Next". You may need to scroll up to see this option.
> > - Click on "Next".
> > - Keep "Use Git from the command line and also from 3rd-party software" selected and click on "Next". If you forgot to do this, programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
> > - Click on "Next" two times.
> > - Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
> > - Select "Use Windows' default console window" and click on "Next".
> > - Click on "Next" three times.
> > - Click on "Install".
> > - Click on "Finish".
> {: .solution} 
> > ## Installing LibreOffice spreadsheet
> > - Download the [LibreOffice for Windows installer](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Windows should automatically be selected. Click on "Download" for the version LibreOffice X.X.X (whichever is the most recent version). You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically. Once the installer is downloaded, double click on it and follow the next steps.
> > - Click on "Install anyway" (in the screen "The app you are trying to install isn't a Microsoft verified app")
> > - Click on "Next" two times.
> > - Click on "Install".
> > - Click on “Yes” (in the screen “Do you want to allow this app to make changes to your device?”)
> > - If the screen "Files in Use" appears, Select "Do not close applications. A reboot will be required to complete the setup." and click on "OK".
> > - Click on "Finish".
> > - Click on "Yes" if asked to restart to your system.
> {: .solution}
> > ## Installing the Integrative Genomics Viewer (IGV)
> > - Download the [IGV for Windows installer](https://software.broadinstitute.org/software/igv/download), the version "IGV for Windows Java included". Once the installer is downloaded, double click on it and follow the next steps.
> > - Click on "Install anyway" (in the screen "The app you are trying to install isn't a Microsoft verified app")
> > - Click on "Yes" (in the screen "Do you want to allow this app to make changes to your device?")
> > - Select "I accept the terms of the License Agreement" and click on "Next".
> > - Click on "Install".
> > - Once the installation is finished, run IGV by double clicking the IGV icon in your Desktop screen.
> > - Click on "Allow access" if the screen "Windows Defender Firewall has blocked some features of this app" appears.
> {: .solution} 
{: .solution}

> ## Mac OS X
>
> - Install LibreOffice by going to [the installation page](https://www.libreoffice.org/download/libreoffice-fresh/). The version for Mac should automatically be selected. Click on "Download" for the version LibreOffice X.X.X (whichever is the most recent version). You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically.
> - Once the installer is downloaded, double click on it and LibreOffice should install.
{: .solution}

> ## Linux
> > ## Install LibreOffice spreadsheet
> > LibreOffice is usually pre-installed in most Linux distributions. Please check first whether it is installed in your system. If it is not, then **try first option 1** as it is the simplest and recommended.
> > > ## Option 1 
> > > Use the software manager (graphical) application of your Linux distribution, such as **Ubuntu Software** (Center) in the case of Ubuntu Linux, or **Software** in the case of Fedora Linux. Follow these steps in Ubuntu (which should be similar for other distributions):
> > > - Open **Ubuntu Software**
> > > - Search for libreoffice
> > > - Click on "LibreOffice Calc" to install only the spreadsheet or on "LibreOffice" to install all the LibreOffice applications
> > > - Click on "Install"
> > {: .solution} 
> > > ## Option 2
> > > > ## Debian - Ubuntu - Mint 
> > > > - Download the [LibreOffice for Linux installer](https://www.libreoffice.org/download/libreoffice-fresh/). A version for Linux should automatically be selected but you must select the **deb** version as follows. On the version LibreOffice X.X.X (whichever is the most recent version), on "Choose your operating system:", select "Linux (64-bit) (**deb**)". **Click on** "Download". You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically. Once the installer is downloaded, follow these steps.
> > > > - Open a Terminal (Console) and change to the location where you downloaded the installer.
> > > > - Uncompress and run the installer with the commands in the Code box below, but using:
> > > >   - the actual name of the installer you downloaded and 
> > > >   - the name of the directory created by the "tar ..." command 
> > > >   - you may be asked your password by the sudo command.
> > > > ~~~
> > > > $ tar zxvf LibreOffice_7.2.0_Linux_x86-64_deb.tar.gz
> > > > $ cd LibreOffice_7.2.0.4_Linux_x86-64_deb
> > > > $ cd DEBS
> > > > $ sudo dpkg -i *.deb
> > > > ~~~
> > > > {: .bash}
> > > {: .solution} 
> > > > ## Fedora - Centos - Mandriva - Mageia - openSUSE and other RPM based systems
> > > > - Download the [LibreOffice for Linux installer](https://www.libreoffice.org/download/libreoffice-fresh/). A version for Linux should automatically be selected but you must select the **rpm** version as follows. On the version LibreOffice X.X.X (whichever is the most recent version), on "Choose your operating system:", select "Linux (64-bit) (**rpm**)". **Click on** "Download". You will go to a page that asks about a donation, but you don't need to make one. Your download should begin automatically. Once the installer is downloaded, follow these steps.
> > > > - Open a Terminal and change to the location where you downloaded the installer.
> > > > - Uncompress the installer using the tar command in the **Code** box but **use** the actual name of the installer you downloaded (which should look like "LibreOffice_7.2.0_Linux_x86-64_rpm.tar.gz"):
> > > > ~~~
> > > > $ tar zxvf LibreOffice_YOURVERSION_Linux_x86-64_rpm.tar.gz
> > > > ~~~
> > > > {: .bash}
> > > > The "tar ..." command will create a new directory whose name will be similar to the name of the installer you downloaded but without the ending ".tar.gz" (e.g., LibreOffice_7.2.0_Linux_x86-64_rpm). 
> > > > - Change location as shown in the next Code box but **using** the name of your newly created directory in the first command:
> > > > ~~~
> > > > $ cd LibreOffice_YOURVERSION_Linux_x86-64_rpm
> > > > $ cd RPMS
> > > > ~~~
> > > > {: .bash}
> > > > - For **Fedora** and **Centos**, run the installer using the command in the next Code box (you may be asked your password). Once the installer finishes, LibreOffice will be installed in your system.
> > > > ~~~
> > > > $ su -c 'yum install *.rpm'
> > > > ~~~
> > > > {: .bash}
> > > > - For **Mandriva** and **Mageia**, run the installer using the command in the next Code box (you may be asked your password). Once the installer finishes, LibreOffice will be installed in your system.
> > > > ~~~
> > > > $ su -c 'urpmi *.rpm'
> > > > ~~~
> > > > {: .bash}
> > > > - For **openSUSE** and **other RPM based systems**, run the installer using the command in the next Code box (you may be asked your password). Once the installer finishes, LibreOffice will be installed in your system.
> > > > ~~~
> > > > $ su -c 'rpm -Uvh *.rpm'
> > > > ~~~
> > > > {: .bash}
> > > {: .solution} 
> > {: .solution} 
> {: .solution} 
> > ## Install the Integrative Genomics Viewer (IGV)
> > - Download the [IGV for Windows installer](https://software.broadinstitute.org/software/igv/download), the version "IGV for Windows Java included". Once the installer is downloaded, double click on it and follow the next steps.
> > fasdfa
> {: .solution} 
{: .solution}

## Option A (**Recommended**) --- Using the lessons with an AMI provided to you

If you are signed up to take the Cloud-SPAN Foundation Course, you do _not_ need to worry about setting up an AMI instance. The Cloud SPAN team will create an instance for you and this will be provided to you at no cost. Your Instructor will provide instructions for connecting to the AMI instance at the workshop.

## Option B: Using the lessons with your own AMI on your AWS account

If you would like to work through these lessons independently, outside the Cloud SPAN Foundation course, or with your own copy of the AMI used in the course, you will need to start your own AMI instance. Follow these [instructions on creating an Amazon instance](https://cloud-span.github.io/foundation-01-intro/AMI-setup/). Use the AMI **to change: ami-04b3bc83255f918b0** (Cloud SPAN Foundation Course AMI) listed on the Community AMIs page. Please note that you must set your location as Ireland (eu-west-1) in order to access this community AMI. You can change your location in the upper right corner of the main AWS menu bar. The cost of using this AMI for a few days, with the t2.medium instance type is very low (about USD $1.50 per user, per day).

*The advantage of Option B is that you will be able to keep all the software and data for as long as you keep your AMI*. 


