<h1>Virtual-Private-Networks</h1>
I will be creating a virtual machine in Azure. Then establishing a VPN connection and testing it across networks.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN
- whatismyipaddress.com

  <h2>Operating Systems Used </h2>
  - Windows 10

<h2>Steps</h2>

1. Create Virtual Machine in Azure:

- Provision a Windows 10 Virtual Machine on Azure.
- Access https://whatismyipaddress.com/ and record the IP address.
- Create a Resource Group for the VM.

2. Log into the VM:

- Use Remote Desktop to log into the Windows 10 VM.
- Access https://whatismyipaddress.com/ and note the IP address.
- Sign up for ProtonVPN and test the VPN connection:

3. Sign up for the free version of Proton VPN on your local computer.

- Within the VM, download and install the Proton VPN client.
- Log into the VPN and select a server in a different country (e.g., Netherlands).
- Access https://whatismyipaddress.com/ and record the new IP address.
- Test browsing to Google, and/or Disney to observe potential differences based on the VPN server's location.

4.Clean up Azure resources:

- Delete the Resource Group created earlier.
- Ensure all associated resources within the Resource Group are deleted.

<h2>Image Links</h2>

- https://imgur.com/a/3PvpdoA
- https://imgur.com/BwD3kzZ
- https://imgur.com/Z8Ld0pT
- https://imgur.com/y4qRAVJ
- https://imgur.com/xN6LKE2
- https://imgur.com/e7agASR
