This is a script for automating some mundane and boring tasks in Kali Linux. This script is a menu of items you can run to perform various tasks. Primarily it is used for information gathering techniques and not for hardcore hacking. This script uses NMAP, Whois, theHarvester, Fierce DNS, Nikto, Metagoofil, NSLookup and others. This script outputs a text file of the results into the folder associated with the command. 

Assumptions:
There is no warranty and I take no responsibility for what you do with this script and whether or not it works for you. 
You have installed Kali Linux on a VM or a physical system.
You know how to use Kali a little and have some general knowledge of linux.
Your username is "user" (you can edit the script and input your username).
You have a text file on your desktop called "targets.txt".
You know what sudo is.
Google is your friend. 

First things first, when running this script make sure to create a text file on your desktop and call it targets.txt. In the targets.txt file, input the IP addresses or CIDR ranges of IPs you want to run NMAP against. All of these IPs should be separated with a space, no commas or anything and all IPs need to be on one line. Otherwise you'll get an error. You can edit the location of your targets.txt file within the script as needed. 

Run this script with sudo, otherwise some of the commands won't work. 

When you execute this script it will prompt you for information. It will ask you for the name of the client and will create a folder on your desktop with that client name and subfolders of the output of each command. 

From there just enter the option you want and hit enter. It will prompt you for more information if needed. 

Be patient. I added some crappy progress bars but not every command has them. Even if it looks like it's not doing anything because you're not seeing a progress meter, doesn't mean it's not working. Check the output folders to see your progress if needed. 

Have fun with this script and only use it for legit purposes. 
