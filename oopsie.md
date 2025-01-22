## Key Takeaways
1. Changing cookie is easy
2. burpsuite can be used to crawl passively 
3. We have scripts with built reverse shells in /usr/share
4. python3 -c 'import pty;pty.spawn("/bin/bash")' in order for functional shell jesus christ how do people come up with this
5. By going through web server code we come across reused password
6. su robert + password to switch user
7. id to get group id then find / -group groupName to get potential path
8. I see cat is being used insecurely with sid on so we create our own cat at /tmp
