# Creating a Python Virtual Environment on Windows
>You can create a Python virtual environment on a Windows system using Windows Subsystem for Linux (WSL).

**In this article**

Installing WSL

Installing Ubuntu 

Installing Required Packages

Creating a Python Virtual Environment

Activating and Deactivating the Virtual Environment

## Installing of WSL
•	Open PowerShell as an Administrator

•	Run the following command to enable WSL feature `wsl --install`. This command enables the WSL feature on your Windows system.

•	After enabling the feature, then set the default WSL version to 2 using this command ``` wsl –setdefault-version 2```. This command configures WSL to use version 2 by default, which provides better performance and compatibility with certain Linux distributions.

•	After the update, restart the computer if prompted.

## Installing Ubuntu
•	Download from Microsoft Store on your Windows machine or directly from google, see [ubuntu](https://ubuntu.com/download/desktop).

•	Download and install the desired ubuntu version.

•	Once the installation is complete, launch Ubuntu from the Start menu.

## Installing Required Packages

Before creating a virtual environment, it’s essential to install the necessary packages.

•	Open the Ubuntu terminal.

•	Update ubuntu for the latest packages and security patches `sudo apt update` and upgrade installed packages `sudo apt upgrade` to ensure that we have the latest information about available packages using commands
![alt](https://github.com/Maheshwari2121/create-virtual-environment/blob/07dc14a9e65b94c3b1c4d3da961559ff73f58c7c/Screenshot%20(35).png)

•	If Python 3 is not already installed, you can install it using `sudo apt install python3 `.
![alt](https://github.com/Maheshwari2121/create-virtual-environment/blob/07dc14a9e65b94c3b1c4d3da961559ff73f58c7c/sc5.png#creating-a-linux-virtual-environment-on-windows)

## Creating a Python Virtual Environment

• Decide on a location for your Python project and create a new directory for it. For example, `mkdir my_project` , `cd my_project`

• Inside your project directory, create a new Python virtual environment (e.g., "my_venv") using the `python3 -m venv my_venv` 

• To activate the virtual environment, run the activation script located in the 'bin' directory of the virtual environment using `source my_env/bin/activate`. After activation, your terminal prompt will change, indicating that you are now working within the virtual environment.

• While the virtual environment is active, you can use pip to install Python packages specific to your project. For ex: `pip install package_name`. You can now work on your Python project within the virtual environment. Any packages you install or scripts you run will be isolated within this environment.

![alt](https://github.com/Maheshwari2121/create-virtual-environment/blob/8e80a58fb6899532777643eea0d5b6170c84552c/ss4.png)

## Activating and Deactivating the Virtual Environment

• When you're done working within the virtual environment, you can deactivate it by simply running: `deavtivate`

![alt](https://github.com/Maheshwari2121/create-virtual-environment/blob/07dc14a9e65b94c3b1c4d3da961559ff73f58c7c/Screenshot%20(34).png)











