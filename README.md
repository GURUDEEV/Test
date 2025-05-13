# Test

## Monthly Activities Report

### April Activities:

1. **Jira Service Management**
   - Responded to server outage on NAM Jira DEV environment following a server reboot
   - Restored service functionality by restarting Jira services
   - Resolved plugin issue with Static Assets CDN by removing problematic database entry
   - Reference: [Atlassian Community Forum](https://community.atlassian.com/forums/Jira-questions/Static-Assets-CDN-Plugin-issues/qaq-p/1354121)

2. **Server Upgrades and Maintenance**
   - Upgraded .NET Core to version 8.0.14 on SD-C4A2-7EF5 server
   - Upgraded JDK to version 21.0.6 on SD-C4A2-7EF5 server
   - Configured Jenkins to work with the new JDK version
   - Upgraded Jenkins to latest version on SD-C4A2-7EF5 server
   - Removed older JDK versions to maintain system stability

### May Activities:

1. **Server Management**
   - Uninstalled Postgres from SD-60JH-3WK6 server
   - Upgraded Jenkins and .NET on SD-C4A2-7EF5 server

2. **Software Updates**
   - Upgraded Microsoft .NET Core Windows Server Hosting 6.0.10 (Product ID: 66903) (Version ID: 1199523) on SD-Q0L5-W9L8 server
   - Upgraded Microsoft .NET Runtime 6.0.10 (Product ID: 132667) (Version ID: 1199518) on SD-Q0L5-W9L8 server
   - Performed JDK upgrades on Linux Jira DEV server SD-LKP7-2FQ0

3. **Issue Resolution**
   - Fixed "Upload app" functionality in the "Manage apps" section on Training Jira instance
   - Resolved by accessing Training Linux server and adding `-Dupm.plugin.upload.enabled=true` to the setenv.sh file
