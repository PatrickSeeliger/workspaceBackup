# workspaceBackup

This is just a test project to deploy to an AWS EC2 instance.

To get it to work in Eclipse with EGit (behind a firewall there are a few steps:
1. Setup Network Proxy settings:
1.1 Go to Window/Preferences/General/Network Connections
1.2 http and https need to use Provider=Manual, Host=*, Port=*, Authentication=Yes, Username=Windows domain user, Password=...
* look at the IE Internet Options/LAN settings, download the configuration script and select a nearby proxy server/port

2. Clone the remote repository:
2.1 Specify the URI with .git at the end
2.2 For protocol use https
2.3 For port use 80
2.4 For user specify the Windows domain user
2.5 For password specify the corresponding password
