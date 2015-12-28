# process_monitor
Launch your program / script once and process_monitor makes sure to restart it in case of unexpected crash!

Based on a answer given at [askubuntu](https://askubuntu.com/questions/163993/how-do-i-automatically-restart-docky-after-a-crash/264938) (part of **StackExchange**) by [Neil Huang](https://askubuntu.com/users/8261/neil-huang).

Made originally to monitor Docky program (Linux dock application) which tend to crash spontaneously.

## Usage

run a program like so:

~/process_monitor.sh /path/to/your/program.sh

everytime it is closed or crashes, it restarts. To close it for good you have to kill the process_monitor.sh process.

**Tip**: rather than starting from terminal, add a command as your startup script.

## TO DO:

* check if process_monitor exists, if so, don't start another one - to avoid multiplying them when logging off and on