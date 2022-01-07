# apt-install-script-Raspberry-Pi
This is a bash script that automates installation of cybersecurity and other tools on the Raspberry Pi.

It is currently configured to only run the updates and exit.

It you want to run the full tool install comment out the exit on line nine and save the script.  For example change exit to #exit.  This will allow the script to run to the end and install all tools listed in the script.

After downloading the script change the permission to make it executable as follows;

chmod +x apt-getInstallerPi.sh

run the script as root with sudo;

sudo ./apt-getInstallerPi.sh
