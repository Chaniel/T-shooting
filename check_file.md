If your system have problem, you should check following files

- service access log
- service error log
- /var/log/messages
- /var/log/secure

```bash
top
free
df -h
sar

netstat -antp | wc -l
netstat -antp | grep ES |wc -l
netstat -ntlp 
```
