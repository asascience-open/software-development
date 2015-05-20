# Unix System Administration

 - Command Line and Terminal
 - Basic Bash Scripting
 - Must-know tools
   - nc (netcat)
   - nmap
   - ifconfig
   - ls
   - cat
   - man
   - grep
   - sed
   - tcpdump (just know that it's there and you can google your specific case)
   - passwd
   - ssh
   - dd
   - mkdir
   - find
   - locate (slocate)
   - mkfs
   - wc
   - sort


For example what does the following do:

```
#!/bin/bash

mkdir /tmp/textfiles
cd /tmp/textfiles
dd if=/dev/urandom of=garbage bs=1024 count=1024
cat garbage | base64 > bigfile.txt
rm garbage
```

 - Basic firewall with `iptables`
 - User Management
 - SSH
   - Passwordless SSH access with keys
   - SSH Tunneling (so important)
 - sudo and the sudoers file

