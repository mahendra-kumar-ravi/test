learn form chai aour code

Node.js can be installed in multiple ways on a computer. The approach used by you depends on the existing Node.js development environment in the system. There are different package installers for different environments. You can install Node.js by grabbing a copy of the source code and compiling the application. Another way of installing Node.js is by cloning the Node.js GIT repository in all three environments and then installing it on the system.

Installing Node On Windows (WINDOWS 10)
You have to follow the following steps to install the Node.js on your Windows :

Step 1: Download the NodeJS
Downloading the Node.js ‘.msi’ installer the first step to install Node.js on Windows is to download the installer. Visit the official Node.js website i.e) https://nodejs.org/en/download/

Download-Node
Download Node.js

You can run the above commands to install the nodejs.You can also download Nodejs using Prebuilt installer .

Step 2: Go to Prebuilt Installer and Select the Versions
Nodejs-installer-(MSI)
Nodejs installer (MSI).png

You can select the required version or can download the Long Time Support version.Click on Download button to download the node version.

Once You Download the .msi installer follow next step.

Step 2: Running the Node.js Installer
Now you need to install the node.js installer on your PC. You need to follow the following steps for the Node.js to be installed:

Double-click on the .msi installer

The Node.js Setup wizard will open.
Welcome To Node.js Setup Wizard

Select “Next”
After clicking “Next”, the End-User License Agreement (EULA) will open.

Check “I accept the terms in the License Agreement”
Select “Next”


Destination Folder Set the Destination Folder where you want to install Node.js & Select “Next”.



Custom Setup

Select “Next”


Ready to Install Node.js.

The installer may prompt you to “install tools for native modules”. 

Select “Install”


Do not close or cancel the installer until the installation is complete. Complete the Node.js Setup Wizard.

Click “Finish”
Capture71image

Step 4: Verify that Node.js was properly installed or not
To check that node.js was completely installed on your system or not, you can run the following command in your command prompt or Windows Powershell and test it:-

C:\Users\Admin> node -v


If node.js was completely installed on your system, the command prompt will print the version of the Node JS installed.

Step 5: Updating the Local npm version
You can run the following command, to quickly update the npm

npm install npm --global // Updates the ‘CLI’ client
