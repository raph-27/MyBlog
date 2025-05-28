<h1> Basic Containerization Using Raspberry Pi 3 with OpenMediaVault OS
<h6>I've got a spare Raspberry Pi 3, and it's incredible how much this tiny, credit card-sized computer can accomplish in a home lab setup. With the help of OMV (OpenMediaVault)—a Debian-based Linux OS designed for storage and server applications—I've transformed this humble board into a powerful multi-service server.
<h6> OpenMediaVault (OMV) is a free, open-source NAS (Network Attached Storage) operating system designed to make it easy to manage file storage on a server, Raspberry Pi, or old PC. It gives you a web-based GUI to manage storage, users, sharing protocols (like SMB, NFS, FTP), and services like Docker, rsync, and more—without needing deep Linux knowledge.
<h6>
<h4> The Hardware 
<img src="/assets/LabsPics/HardwarePi.jpg"  width="2000"/> <br>
<h4> The Containers
<p> i've installed this Containers using Docker Compose 
<img src="/assets/LabsPics/The Containers.jpg"  width="4000"/> <br>
<h4> Pi-Hole
<p>Pi-hole is a network-wide ad blocker that you can run on a local device like a Raspberry Pi, Docker container, or even a virtual machine. It works by acting as a DNS sinkhole, blocking requests to advertising and tracking domains for all devices on your network.
<img src="/assets/LabsPics/DNS Server.jpg"  width="4000"/> <br>
<h4> Plex Media Server
<p>Plex Media Server is a personal media server software that organizes your video, music, and photo collections and streams them to your devices—TVs, phones, computers, tablets—anywhere, over your network or the internet.
<img src="/assets/LabsPics/Media Server.jpg"  width="4000"/> <br>
<img src="/assets/LabsPics/Media Server Web.jpg"  width="4000"/> <br>