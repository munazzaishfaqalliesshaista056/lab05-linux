# Security Detective

## Question 1
Answer: I am munazzaishfaqalliesshaista056. My home folder is /home/munazzaishfaqalliesshaista056.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu and the Ubuntu version is Ubuntu 24.04 LTS (or similar release version from os-release).
Commands: hostname, cat /etc/os-release

## Question 3
Answer: Total RAM is available via free -h and root disk available space is shown in df -h /.
Commands: free -h, df -h /

## Question 4
Answer: The users shown with /bin/bash can be found using grep.
Command: grep '/bin/bash' /etc/passwd

## Question 5
Answer: The command reports process line count. Note that ps aux | wc -l includes a header line, so it is an approximate process count.
Command: ps aux | wc -l

## Question 6
Answer: The creation/deletion times found in the available logs for lab5user are recorded in auth.log or journalctl.
Commands: sudo grep lab5user /var/log/auth.log; sudo journalctl | grep lab5user
