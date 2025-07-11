# KF2-MSK-GS-Resources

## Description
This repository contains resources from the Killing Floor 2 servers of the [MSK-GS project](https://steamcommunity.com/groups/msk-gs), such as configs, map cycles, banner images, and so on  

## Structure
- **banners** - images for welcome screens
- **common** - configs common to all servers
- **instances** - config dirs of the main servers
- **instances-beta** - config dirs of the beta servers
- **mapcycles** - map rotation cycles
- **instances/**<server_name>**/instance.conf** - server startup options (game mode, difficulty, mutators, etc.)
- **instances-beta/**<server_name>**/instance.conf** - same as above, but for beta servers

## Usage
### License
Please read the [license](LICENSE) before using any file from here.  

### Server management
[MSK-GS](https://steamcommunity.com/groups/msk-gs) servers used the [KF2-SRV](https://github.com/GenZmeY/KF2-SRV) management system.  
You can also use [KF2-SRV](https://github.com/GenZmeY/KF2-SRV), but keep in mind that I create it for myself, and unfortunately did not provide manual for it.  
I do not recommend using [KF2-SRV](https://github.com/GenZmeY/KF2-SRV) unless you have sufficient knowledge of Linux in general and CentOS in particular, as well as the ability to learn unknown tools.  
If you decide to choose a different KF2 server management system, you will probably have to adapt these resources for your case.  

### Symlinks
I used symlinks so that different servers can use the same configs and map rotation cycles. They usually refer to files in [common](common) and [mapcycles](mapcycles).  
Keep this in mind when setting up your server. If you do not need symlinks, you can simply replace them with the necessary files. Otherwise use `ln -s <target> <link_name>` (linux) or `mklink <link_name> <target>` (windows)  

## Mirrors
- https://github.com/GenZmeY/KF2-MSK-GS-Resources  
- https://codeberg.org/GenZmeY/KF2-MSK-GS-Resources  

## P.S.
**GL & HF** 🙃  
