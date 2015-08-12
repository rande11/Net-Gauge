# Net-Gauge 

**Ok, at the moment this program does not work yet.** I am in the middle of creating a whiptail menu system that will allow easier entry of wan, lan, and user data.

Before I started using github, my verioning had gone to v2.2.4a. Below I will list all major and minor changes. Obviously this is not ready for release still being  in alpha.

I will explain how it works in later versions.

#####v0
Highly specific script. All calls to external program used exact infomation in the script itself. With data usage being writen to multiple file (1 for each user). Web interface shows all user's data usage on plain table. External script get_usage.sh used to get usage.

#####v0.5
<ul><li>Minor inprovements to script.</li>
<li>User's device information retived from file, not hard coded in script.</li></ul>

#####v1
() Minor inprovements to script.
() Web interface shows user's device usage for that device.
() Web interface added admin mode to view all usage data.

#####v1.5
() Minor inprovements to script.
() Script now only sees one user with multiple devices (before had to go in if loops to exclude reusing same user names).

#####v2
() Minor inprovements to script.
() Usage data stored in 1 file now (before was 1 file per user).
() Admin web interface included links to show output of 3 programs: iptables, ip route, and ip rule.

#####v2.1
() Minor inprovements to script.
() Script uses ip rule to seperate WANs (before it was hastaly done with iptables)
() Script function to cut user now implimented better.
() Script include code from external file get_usage.sh.
() Impoved array usage.

#####v2.2
() Start work on menus script.
() Cut out web interface for now.

#####v2.2.1
() menus - Got menu system working.
() menus - Start data input.

#####v2.2.2
() menus - Got data input working.
() menus - Start data validation.

#####v2.2.3
() menus - Got data save working (add wan dev).
() menus - Woking on issues with data validation.

#####v2.2.4
() menus - Got data validation working (add wan dev).
() menus - Continue finishing data input.
