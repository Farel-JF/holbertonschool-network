Network Configuration Scripts
This repository contains a set of Bash scripts for configuring and testing network settings on an Ubuntu server. Each script addresses a specific network-related task.

Scripts
0. Change Your Home IP
File: 0-change_your_home_IP

Description:
This script modifies the /etc/hosts file to change the IP addresses associated with localhost and facebook.com. Specifically, it sets localhost to resolve to 127.0.0.2 and facebook.com to resolve to 8.8.8.8.

Usage:

Run the Script:

bash
Copy code
sudo ./0-change_your_home_IP
Verify Changes:

bash
Copy code
ping localhost
ping facebook.com
Ensure that localhost resolves to 127.0.0.2 and facebook.com resolves to 8.8.8.8.

Revert Changes (if necessary):

To restore the original configuration:

bash
Copy code
sudo mv /etc/hosts.bak /etc/hosts
1. Show Attached IPs
File: 1-show_attached_IPs

Description:
This script displays all active IPv4 addresses attached to the machine.

Usage:

Run the Script:

bash
Copy code
./1-show_attached_IPs
Verify Output:

You should see a list of IPv4 addresses, each on a new line. For example:

plaintext
Copy code
10.0.2.15
127.0.0.1
To visualize the end-of-line characters:

bash
Copy code
./1-show_attached_IPs | cat -e
2. Port Listening on Localhost
File: 2-port_listening_on_localhost

Description:
This script listens on port 98 on localhost. It allows you to test connectivity and data transfer on this port.

Usage:

Start the Script:

Open a terminal and run the script with sudo to listen on port 98:

bash
Copy code
sudo ./2-port_listening_on_localhost
Connect to the Port:

Open another terminal and use telnet to connect to localhost on port 98:

bash
Copy code
telnet localhost 98
Send and Receive Messages:

Type a message in the telnet session and press Enter. The message will appear in the terminal running the listening script.

Example:

plaintext
Copy code
Hello world
test
Stop the Script:

To stop listening, press Ctrl+C in the terminal where the script is running.
