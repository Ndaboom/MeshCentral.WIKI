[[images/MC2-Banner.png]]

MeshCentral is an open source, web-based, remote computer monitoring and management web site. It's completely free and you can install it to manage computers on a local network or over the Internet. Here are a few resources to get your started.

* [Main Web Site](https://www.meshcommander.com/meshcentral2). Contains instructions, download links, documentation and tutorial videos.
* [Twitter](https://twitter.com/meshcentral). For the very latest news and updates, this is where announcements are posted first.
* [Blog](https://meshcentral2.blogspot.com/). Every few weeks, there is a post on the latest news and updates.
* [GitHub Issues](https://github.com/Ylianst/MeshCentral/issues). This is where you post bug reports, feature requests and help others.
* [Reddit MeshCentral](https://www.reddit.com/r/MeshCentral/). Latest discussions on MeshCentral related topics.

For a quick overview of MeshCentral manageability and security features, take a look at these two one page PDF documents.

* [Manageability Features Guide](http://info.meshcentral.com/downloads/MeshCentral2/MeshCentral2ManagementFeaturesGuide.pdf).
* [Security Features Guide](http://info.meshcentral.com/downloads/MeshCentral2/MeshCentral2SecurityFeaturesGuide.pdf).

If you are familial with NodeJS, all you need to know to get MeshCentral running are these two commands:

```
npm install meshcentral
node node_modules/meshcentral
```

This would get your running with your own server in a minute of two and can start playing around. By default, MeshCentral will run in LAN-mode, where agents installed on other machines will multicast on the local network to find the server. Once familiar with the basics, you will want to configure MeshCentral on a computer with known DNS name so that agents install all over the internet can connect back to the server.