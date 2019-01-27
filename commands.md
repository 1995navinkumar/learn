## How to find the MAC address of a computer?
* On a Macintosh, go to “System
Preferences.” In the search entry box in
the upper right, type Ethernet ID and
hit “Return.” The next window you see will
show your Ethernet ID, which is really just
another name for your MAC address
* On a Windows machine, go to “Start > Run.”
Type cmd and you will open the command
line utility. Type ipconfig/all and the
MAC address will appear in the output.
* If you are a Unix or Linux user, open
a command prompt window and enter
sudo /sbin/ifconfig -a. The
MAC address will show under “hwaddr” or
“ether.” 

## How to find the MAC addresses stored in a Switch
1. Connect the computer to the switch using a Serial cable.
2. Open a terminal program such as Hyperterminal, and get to the command prompt of the switch.
    * switch#  show mac-address (HP switch)  