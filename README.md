# Configure-and-test-basic-firewall-rules-to-allow-or-block-traffic.
Configured and tested basic firewall rules using Windows Defender Firewall to block and allow network traffic, including port-based filtering and rule verification.

**Objective**
Configure and test basic firewall rules to allow or block network traffic using Windows Defender Firewall or UFW (Uncomplicated Firewall) on Linux.

**Tools Used**

Windows Defender Firewall (Windows)
Terminal / Command Prompt

**Tasks Performed**

Listed existing firewall rules
Blocked inbound traffic on Telnet port (23)
Tested blocked port connectivity
Removed test firewall rule to restore original state
Documented firewall rules and commands used
**Steps Performed (Windows Firewall)**

Open Run and type wf.msc
Go to Inbound Rules
Click New Rule → Port
Select TCP and enter 23
Choose Block the connection
Apply rule to all profiles
Name the rule and save
Test using telnet localhost 23
Delete the test rule after verification
**Testing**
Attempted to connect to port 23 (Telnet) after blocking
Connection was refused, confirming firewall rule effectiveness

**Deliverables**

Screenshots of firewall rules
Screenshot of blocked connection test
Firewall configuration output file (Setup and Use a Firewall on WindowsLinux.pdf)
