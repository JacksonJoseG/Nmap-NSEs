Nmap script used to scan minecraft servers, based on shodan.io output.

Usage:
    nmap --script minecraft-info.nse -p 25565 <host>

Output Example:
  Host script results:
    minecraft-info:
        Description: A Minecraft Server
        Max Players: 20
        Online Players: 2
        Version: 1.8
        Protocol: 47
        Login Status: Original Server
