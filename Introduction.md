MeshCentral is a free open source web-based remote computer management software. You could setup your own management server on a local network or on the internet and remote control and manage computers that runs either Windows* or Linux* OS.

[[images/introduction3.png]]

To begin a management server will be required. A management server could be any computing device (PC or VM) that has sufficient compute, storage and reliable network components to host an environment for MeshCentral and deliver good performance during remote management exercise. Whilst there are many configurations available for advanced users, typical server setup would only take just a few minutes to complete. 

At a high level, there are only four (4) main steps: Setup, Install, Connect and Control. 
* 1st, the user setup the MeshCentral server on VM or PC
* 2nd, the user logs on to MeshCentral portal with a valid account, creates an administrative mesh to collect all end-points (systems to be managed)
* 3rd, the user then generates an agent and installs it on a target or each end-point that immediately attempts a connection back to MeshCentral server. 
* 4th, the user controls/manages assets or end-points that are available in respective administrative mesh

Because the MeshCentral server is written in NodeJS it can be installed on many operating systems including Windows, Linux. Please refer to the MeshCentral Installer’s Guide available at https://www.meshcommander.com/meshcentral2 for information on how to install the server.

The server can be installed both on a local area network for local computer management and in the cloud for management of computers over the Internet. You can also install it on small IoT devices like a Raspberry Pi all the way to big servers. It’s recommended to get started with a test setup to get a feel for this server. Once installed, come back to this document for configuring and using your new server.