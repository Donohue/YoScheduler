# Yo Scheduler

Schedule your Yos directly from your Mac:

1. Edit yo.sh and enter your Yo API key. You can grab an API key here: http://yoapi.justyo.co/
2. Edit com.bthdonohue.yoscheduler and change the path to this directory. You can also rename this file if you'd like, but make sure you reflect that change in the file itself. Otherwise it won't load into launchctl.
3. Edit the time the Yo is scheduled for. I currently have it scheduled for Thursday at noon, which is when betaworks does their company wide meeting.
4. Copy com.bthdonohue.yoscheduler to ~/Library/LaunchAgents
5. Run this command "launchctl load -w ~/Library/LaunchAgents/com.bthdonohue.yoscheduler" without quotes
6. ???
7. Profit

