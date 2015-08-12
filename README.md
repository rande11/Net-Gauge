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
<ul><li>Minor inprovements to script.</li>
<li>Web interface shows user's device usage for that device.</li>
<li>Web interface added admin mode to view all usage data.</li></ul>

#####v1.5
<ul><li>Minor inprovements to script.</li>
<li>Script now only sees one user with multiple devices (before had to go in if loops to exclude reusing same user names).</li></ul>

#####v2
<ul><li>Minor inprovements to script.</li>
<li>Usage data stored in 1 file now (before was 1 file per user).</li>
<li>Admin web interface included links to show output of 3 programs: iptables, ip route, and ip rule.</li></ul>

#####v2.1
<ul><li>Minor inprovements to script.</li>
<li>Script uses ip rule to seperate WANs (before it was hastaly done with iptables).</li>
<li>Script function to cut user now implimented better.</li>
<li>Script include code from external file get_usage.sh.</li>
<li>Impoved array usage.</li></ul>

#####v2.2
<ul><li>Start work on menus script.</li>
<li>Cut out web interface for now.</li></ul>

#####v2.2.1
<ul><li>menus - Got menu system working.</li>
<li>menus - Start data input.</li></ul>

#####v2.2.2
<ul><li>menus - Got data input working.</li>
<li>menus - Start data validation.</li></ul>

#####v2.2.3
<ul><li>menus - Got data save working (add wan dev).</li>
<li>menus - Woking on issues with data validation.</li></ul>

#####v2.2.4
<ul><li>menus - Got data validation working (add wan dev).</li>
<li>menus - Continue finishing data input.</li>
<li>Start figuring out what to put in options.cfg file for options.</li></ul>
