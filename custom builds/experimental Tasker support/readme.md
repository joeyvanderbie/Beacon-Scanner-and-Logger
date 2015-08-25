Enabling experimental Tasker support - August 2015

I've put together an APK which you can install that I think will give you what you need. 
You'll find a new preference in the settings screen called "Realtime Logging", which when enabled
means that a log file will be created every time a beacon is detected. The logfile is called "realtimelog.txt".

The 'read line' function in tasker will enable you to query the log file, you can then take the appropriate 
action based on the beacon details retrieved.

I've also added the option to scan every second when in background mode, but haven't had a chance to test this feature.\

There is a known bug, where if you select the "back" arrow at the top of the screen when in the File List the app will
crash. You can use the normal android back button to work around this.

I'll try and test these features fully, so they can be included in the next release of the app, but for now I 
hope you find the attached APK useful.

Thanks to David Schmid for initally requesting this feature and suggesting the use of read line.
