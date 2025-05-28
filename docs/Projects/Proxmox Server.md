<h1> Virtualization using Proxmox Virtual Environment with my old PC
<h6>Ive been diving deeper into virtualization by setting up my own home lab using my old pc as a hypervisor server using proxmox . With just two VMs, one running Microsoft Server and another as a Windows client Ive been able to simulate enterprise environment. 
<h6> Proxmox is a type 1 hypervisor and Proxmox also has built-in tools to manage these virtual computers, take backups, and even set up special storage and networking configurations. It's often used in data centers and IT labs. Proxmox VE (Virtual Environment) is a powerful open-source platform for virtualization, allowing you to run multiple virtual machines (VMs) and containers on a single physical server.
<h4> The Hardware
<p> This is my refurbished PC that I got thru buy and sell
<p>Specs
<p>CPU: AMD A8-7650K Radeon R7
<p>RAM: 8GB 1333mhz
<p>SSD: 120GB for Caching
<p>HDD: 500gb for local storage or NAS
<img src="/assets/LabsPics/ProxHardware.jpg"  width="2000"/> <br>
<h4> This the Web GUI of the Server
<p>This is where you can manage all the resources of your environment, including physical nodes, virtual machines, containers, storage devices, and network configurations. The Proxmox Web GUI provides a comprehensive and intuitive platform to monitor system performance, allocate hardware resources, configure high availability and clustering, and manage user permissions and backups.
<img src="/assets/LabsPics/ProxGUI.jpg"  width="2000"/> <br>
<h4> ADDS with Windows Server and Client
<h6> I have implemented a basic Active Directory Domain Services (ADDS) configuration between two virtual machines within my Proxmox environment to simulate a typical enterprise setup. One VM serves as the Domain Controller, running Windows Server, where I installed and configured ADDS, DNS, and Group Policy Management. I created a new forest and domain, set up organizational units (OUs), and added user and computer accounts to reflect a structured company hierarchy. The second VM, acting as a client machine, was joined to the domain to verify connectivity and domain functionality. I successfully tested domain login from the client VM, applied group policies to manage user settings, and ensured name resolution through the DNS role on the domain controller. This setup allows for centralized management, authentication, and policy enforcement, laying the foundation for more advanced services like RADIUS, file sharing, and role-based access control in future configurations.
<img src="/assets/LabsPics/ProxServerClient.jpg"  width="2000"/> <br>