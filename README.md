# CapacityBay_Monitor
As soon as you run the command you get various System related information which are:

Internet Connectivity
OS Type
OS Name
OS Version
Architecture
Kernel Release
Hostname
Internal IP
External IP
Name Servers
Logged In users
Ram Usages
Swap Usages
Disk Usages
Load Average
System Uptime
Check the installed version of script using -v (version) switch.
Setting appropriate permissions.


# chmod 755 capacitybay_monitor.sh
It is strongly advised to install the script as user and not as root. It will ask for root password and will install the necessary components at required places.

To install "capacity_monitor.sh" script, simple use -i (install) option as shown below.

./capacity_monitor.sh -i 
Enter root password when prompted. If everything goes well you will get a success message like shown below.

Password: 
Congratulations! Script Installed, now run monitor Command
After installation, you can run the script by calling command 'monitor' from any location or user. If you don’t like to install it, you need to include the location every-time you want to run it.

# ./Path/to/script/capacity_monitor.sh
Now run monitor command from anywhere using any user account simply as:

$ monitor
