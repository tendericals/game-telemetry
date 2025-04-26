# Hosts File Location and DNS Cache Flush

The hosts file is located at:

C:\Windows\System32\drivers\etc\hosts

arduino
Copy
Edit

After updating the hosts file, open Command Prompt as an administrator and run:

ipconfig /flushdns

vbnet
Copy
Edit

This clears the DNS cache so the changes can take effect.
