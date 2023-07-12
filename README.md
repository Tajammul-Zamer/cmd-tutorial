# CMD Tutorial
CMD, short for Command Prompt, is a command-line interpreter program available in Windows operating systems. It provides a text-based interface for users to interact with the operating system by typing commands. CMD allows users to execute various commands and perform a wide range of tasks, such as managing files and directories, running programs, configuring system settings, troubleshooting issues, and more.
 
With CMD, users can navigate through the file system, create, delete, and modify files and directories, execute programs and scripts, manage network settings, and access system utilities. It operates based on a command-line interface (CLI) paradigm, where users input commands as text and the system responds with text-based output.
 
CMD uses a set of commands, such as dir to list files, cd to change directories, mkdir to create a directory, and ping to test network connectivity, among others. Additionally, CMD supports batch scripting, allowing users to automate repetitive tasks by writing scripts that contain a sequence of commands.
 
CMD is widely used by IT professionals, developers, and power users who prefer working with command-line tools or need to perform advanced system operations efficiently. While Windows 10 introduced PowerShell as an advanced alternative to CMD, the Command Prompt remains a powerful tool for system administration and command-line tasks in Windows.
#
### To open the Command Prompt (CMD) in Windows, you can follow these steps:
 
#### 1. Using the Start Menu:
- Click on the "Start" button located at the bottom left corner of the screen.
- In the search bar, type "Command Prompt" or "CMD" (without the quotes).
- In the search results, click on the "Command Prompt" or "CMD" app.
  
#### 2. Using the Run Dialog:
- Press the Windows key + R on your keyboard simultaneously. The Run dialog will open.
- Type "cmd" or "cmd.exe" (without the quotes) in the Run dialog.
- Press Enter or click on the "OK" button.
 
#### 3. Using File Explorer:
- Open the File Explorer by pressing the Windows key + E on your keyboard.
- In the address bar at the top, type "cmd" (without the quotes) and press Enter.
- The Command Prompt window will open, starting in the current directory.
 
#### 4. Using the Power User Menu (Windows 10 and Windows 8):
- Right-click on the "Start" button or press the Windows key + X on your keyboard.
- In the menu that appears, click on "Command Prompt" or "Command Prompt (Admin)".
 
#### 5. Using Task Manager:
- Press Ctrl + Shift + Esc on your keyboard to open the Task Manager.
- In the Task Manager, click on the "File" menu.
- Choose "Run new task" or "Run new task (Administrator)".
- In the "Create new task" dialog, type "cmd" or "cmd.exe" (without the quotes).
- Press Enter or click on the "OK" button.
#
###  Windows-commands by Microsoft Learn, 1925 pages pdf
```
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/cmd
```
#
### Here Are Some CMD Commands With Use:
 
1. Change the current directory
```
cd [directory]
```
 
2. List the contents of a directory.
 ```
dir
```
3. Copy a file or directory.
```
copy
```
4. Move a file or directory.
```
move
```
5. Delete a file or directory.
```
del
```
6. Rename a file or directory.
```
ren
```
7. Create a new directory.
```
md
```
8. Delete an empty directory.
```
rd
```
9. Display the contents of a text file.
```
type
```
10. Display network configuration information.
```
ipconfig
```
11. Send a network packet to a specified IP address.
```
ping
```
12. Trace the route of a network packet to a specified IP address.
```
tracert
```
13. Display network connections and listening ports.
```
netstat
```
14. Shut down or restart the computer.
```
shutdown -
```
15. List all running tasks.
```
tasklist
```
 - Kill a running task.
```
taskkill
```
 - Open the Registry Editor.
```
regedit
```
 - Display system information.
```
systeminfo
```
 - Check the disk for errors.
```
chkdsk
```
 - Scan for and repair system file corruption.
```
sfc /scannow
```
 - Open the System Configuration Utility.
```
msconfig
```
 - Run the DirectX Diagnostic Tool.
```
dxdiag
```
 - Display the current user account.
```
whoami
```
 - Manage user accounts.
```
net user
```
 - Manage user groups.
```
net group
```
 - List the computers on the network.
```
net view
```
 - Flush the DNS cache.
```
ipconfig /flushdns
```
 - Delete all entries from the ARP cache.
```
arp -d
```
 - Query the DNS server for information about a domain name.
```
nslookup
```
 - Trace the route of a network packet to a specified IP address.
```
tracert
```
 - Display all active network connections.
```
netstat -an
```
 - Shut down the computer.
```
shutdown /s
```
 - Restart the computer.
```
shutdown /r
```
 - Abort a pending shutdown or restart.
```
shutdown /a
```
 - Display system information.
```
systeminfo
```
 - Check the disk for errors and fix them if possible.
```
chkdsk /f
```
 - Scan for and repair system file corruption.
```
sfc /scannow
```
 - Open the System Configuration Utility.
```
msconfig
```
 - Run the DirectX Diagnostic Tool.
```
dxdiag
```
 - Display the current user account.
```
whoami
```
 - Manage user accounts.
```
net user
```
 - List the computers on the network.
```
net view
```
 - Map a network drive.
```
net use
```
 - Share a network resource.
```
net share
```
 - Configure NetBIOS settings.
```
netbios
```
 - Display detailed network configuration information.
```
ipconfig /all
```
 - Display and manage routing tables.
```
route
```
 - Display and manage ARP cache entries.
```
arp
```
 - Query the DNS server for information about a domain name.
```
nslookup
```
 - Connect to a remote computer using the Telnet protocol.
```
telnet
```
 - Transfer files to and from a remote computer using the FTP protocol.
```
ftp
```
 - Send a network packet to a specified IP address.
```
ping
```
 - Trace the route of a network packet to a specified IP address.
```
tracert
```
 - Display network connections and listening ports.
```
netstat
```
 - List all running tasks.
```
tasklist
```
 - Kill a running task.
```
taskkill
```
 - Open the Registry Editor.
```
regedit
```
 - Display system information.
```
systeminfo
```
 - Check the disk for errors.
```
chkdsk
```
 - Scan for and repair system file corruption.
```
sfc /scannow
```
 - Open the System Configuration Utility.
```
msconfig
```
 - Run the DirectX Diagnostic Tool.
```
dxdiag
```
 - Display the current user account.
```
whoami
```
