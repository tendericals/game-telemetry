# hosts file location and DNS cache flush

the hosts file is located at

C:\Windows\System32\drivers\etc\hosts

## after updating the hosts file open cmd as an admin and run

ipconfig /flushdns

this clears the DNS cache so the changes can be updated
