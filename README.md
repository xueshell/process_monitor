# process_monitor
Launch your program / script once and process_monitor makes sure to restart it in case of unexpected crash!

Based on a answer given at [askubuntu](https://askubuntu.com/questions/163993/how-do-i-automatically-restart-docky-after-a-crash/264938) (part of **StackExchange**) by [Neil Huang](https://askubuntu.com/users/8261/neil-huang).

Made originally to monitor Docky program (Linux dock application) which tend to crash spontaneously.

## TO DO:

* check if process_monitor exists, if so, don't start another one - to avoid multiplying them when logging off and on