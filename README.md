Hosts File Location and DNS Cache Flush
The hosts file is located at:

makefile
Copy
Edit
C:\Windows\System32\drivers\etc\hosts
After editing the hosts file, open Command Prompt as an administrator and run:

bash
Copy
Edit
ipconfig /flushdns
This command clears the DNS cache to apply the changes immediately.
