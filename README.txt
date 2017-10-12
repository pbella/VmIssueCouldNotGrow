I found reproducing the issue a bit tricky as I could only reliably do so with a specific VM version and VM parameters applied.  The combination provided here reproduces the crash every time on my system running Debian 9 (Stretch) and should run in about 5-10 minutes depending on the speed of your system.

Steps to reproduce:
./squeak.sh
doit on the first expression in the Workspace

cng-crash-console-output.txt - output from the console when run on my system
