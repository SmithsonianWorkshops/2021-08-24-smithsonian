# Data Carpentry Software Installation Instructions

This document provides more detailed installation instructions for installing Data Carpentry software. It also provides alternative installation instructions for students who are using Smithsonian Institution computers that require an admin password for software installation.

## DB Browser for SQLite

These instructions have been tested on a Windows (Dell) laptop. The installation process on Macs may differ slightly.

1.	On the DB Browser Download page (https://sqlitebrowser.org/dl/), download DB Browser for SQLite - .zip (no installer) for 64-bit Windows (or download the 32-bit version if you are on an older computer). This will download a .zip archive to your computer (DB.Browser.for.SQLite-\#.\#.\#-win64.zip)

2.	Unzip this archive into a folder on your computer (e.g. the Documents folder).
	- To unzip, double click on the zip archive. There should be a folder inside, DB Browser for SQLite.  Drag and drop this folder from the zip archive to the destination of your choice on your computer.

3.	Open the unzipped DB Browser for SQLite folder. Inside, you should find a file called DB Browser for SQLite.exe. If you double click on this file, the program should open.

4.	(Optional) You can create a desktop shortcut to quickly access the program. Right-click on the DB Browser for SQLite.exe file, then select Send to > Desktop (create shortcut). 

## Anaconda/Jupyter/plotnine

These instructions have been tested on a Windows (Dell) laptop. The installation process on Macs may differ slightly.

1.	Download the appropriate Anaconda installer for your operating system (https://www.anaconda.com/products/individual#download-section). For both Windows and Mac, the 64-Bit Graphical Installer is recommended.

2.	Once the installer has downloaded, double click the file to launch the setup process.

3.	Use the default options preselected by the installer. 
	a.	To avoid the need for admin permissions, make sure that **Select Installation Type > Install for: Just me (recommended)** is selected. 
	b.	Check the box next to **Advanced Options > Register Anaconda3 as my default Python 3.8**

4.	Once the installation process is done, test that it has installed correctly by launching Jupyter Notebook. The Jupyter interface should open in your default web browser. To exit, close the browser window and the Jupyter Notebook command line window.
	a.	Windows: Start Menu > Anaconda3 (64-bit) > Jupyter Notebook
	b.	Mac: Open Terminal. Type `jupyter notebook` then hit enter.

5.	We need to install an additional package called plotnine for Day 2 of our Python lesson. This can be installed from the command line. To open a command line window:
	a.	Windows: Start Menu > Anaconda3 (64-bit) > Anaconda Prompt (Anaconda3)
	b.	Mac: Terminal

6.	In the command line window, type `conda install -c conda-forge plotnine` then hit enter

7.	You should see some text containing a Package Plan, some packages that will be downloaded, and some new packages that will be installed. You will then be prompted whether to proceed. Type `y` then hit enter.

8.	To test whether plotnine has installed successfully, in your command line window, type `conda list plotnine` then hit enter. You should see plotnine listed in your environment.
