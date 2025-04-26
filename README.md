# hosts File Location and DNS Cache Flush

The hosts file is located at:

C:\Windows\System32\drivers\etc\hosts

## after updating the hosts file, open Command Prompt as an administrator and run:

ipconfig /flushdns

This clears the DNS cache so the changes can take effect.
