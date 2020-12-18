# How to Flush DNS in Windows 10?
Command Prompt and Windows Powershell, which is a new addition to Windows, can be used to clear DNS cache.

# Option 1 – Command Prompt
To reset the DNS resolver cache, perform the following steps:

Click the Start button, then type cmd
Right-click Command Prompt, then choose Run as Administrator.
Type ipconfig /flushdns then press Enter. (be sure there is a space before the slash)
A command box will flash on the screen for a split second, and the DNS Resolver cache is cleared.

Besides, there are some other related commands that you might be interested in:

ipconfig /displaydns: It displays your current DNS cache under Windows IP configuration.

ipconfig /registerdns: To register your DNS cache recorded in the Hosts file.

ipconfig /release: To release the current IP address settings.

ipconfig /renew: To reset and request a new IP address.

# Option 2 – Windows PowerShell
Select the Start button, then type powershell
Select Windows PowerShell
Type the following command, then press Enter:
Clear-DnsClientCache
äö
