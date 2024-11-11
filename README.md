# Cloudflared-termux
![sajidibnnayeem](https://github.com/user-attachments/assets/99556f49-5b36-436a-a82a-2dcc2fda8a0d)
<p align="center"><b> Cloudflared-termux refers to the installation and use of Cloudflare's tunneling client in the Termux app, Enabling secure, Encrypted access to local or private services over the internet without directly exposing them.</b></p>

# Installation of Cloudflared in Termux

Step 1: Update and Upgrade Packages
------------------------------------

Initiate the Termux application, subsequently updating existing packages and enhancing them to their most recent iterations. Accomplish this task by executing the following command:
```bash
pkg update && pkg upgrade && pkg install git
```

Step 2: Cloning the Cloudflared Repository
-----------------------------------------

Clone the official Cloudflared repository utilizing the below-mentioned command:
```bash
git clone https://github.com/SajidIbnNayeem/Cloudflared-termux.git
```
This action shall populate the local machine with the source materials needed for successful Cloudflared deployment.

Step 3: Access the Cloned Directory
----------------------------------

Navigate to the freshly cloned folder by implementing the following order:
```bash
cd Cloudflared-termux
```

Step 4: Execution Permissions
-----------------------------

Make the pertinent installation script executable by applying the subsequent command sequence:
```bash
chmod +x Cloudflared-termux.sh
```

Step 5: Deploying the Script
----------------------------

Launch the previously enabled script, thereby instigating the automated Cloudflared installation routine:
```bash
bash Cloudflared-termux.sh
```
