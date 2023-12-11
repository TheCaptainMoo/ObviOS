# ObviOS
A (concept) Operating System focused on privacy and transparency 

## How would it improve transparency?
ObviOS aims to increase the transparency of programs e.g. asking for permission before reading, writing, creating files (with the user being able to control which (if any) permissions are requested). ObviOS also aims to increase the user's understanding of how applications work and operate under the hood. 

## Concept Design
The actual concept design for the operating system is still a WIP and any concepts designs for the style of the OS and its key features would be greatly appreciated.

## Key Features
### User Controlled Permissions
For a program to do anything significant such as file manipulation, microphone/camera access, internet access (this may be handled by an external Firewall software such as Portmaster), it must ask for explicit permission from the user (to always permit, permit now, don't/never permit), similar to a mobile device. In addition, for file manipulation, it may show which file/s the program is creating/editing or for internet access, it may show the address and the type of connection (peer to peer, client to server) etc.

A user would also be able to change all of these permissions outside the application (most likely in a Settings like application, similar to mobile devices). 

### Easily Accessible Log Files
Log files for all permission requests (type of permission, timestamp) as well as their status (always permitted, never permitted, etc.) will be stored in a specific folder, clearly separating applications into different files, directories, etc. 

### Other Features
Refer to ```CONTRIBUTIONS.md```

## Key Apps
Examples of applications are simply references to the rough features to be expected for each app. 
- An advanced Firewall (such as Portmaster) to control network traffic (for privacy and transparency)
- A disassembler (such as IDA) to better analyse the processes of executable files (for transparency)
- A secure browser (such as Tor) to minimise fingerprinting and hide IP addresses (for privacy)

## Contribution
For contribution, please reference the ```CONTRIBUTIONS.md```

## Questions
Feel free to ask any questions on the Discussions tab.
