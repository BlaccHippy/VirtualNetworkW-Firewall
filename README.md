# VirtualNetworkW-Firewall

## Objective
•	Create and deploy virtual networks in Azure, then secure the networks by configuring a firewall that is located between the internet and the virtual networks.  💻

### Skills Learned
•	Configure and Deploy a Virtual Network for Web Server and a Virtual Network for Firewall which Logically segments networks 
•	Create and Configure a Virtual Machine with RDP for remote access to web server, enable just in time access for VM
•	Connect the two networks using Azure Network peering 
•	Configure and deploy the firewall to run on virtual network created for it 
•	Apply Rules to Firewall to protect Virtual Networks (ex. NAT, DNS, Application)

### Tools Used ⚙
•	Microsoft Azure VM
•	Microsoft Sentinel

## Steps

Examples below.

Create Web Server Virtual Network 
![VN Create Network](https://github.com/user-attachments/assets/0c1f0bff-5949-42eb-afad-b1029f398a61)

Assign Web Server Ip and Subnet 
![VN Assign IP Address](https://github.com/user-attachments/assets/69d3ceba-9d0f-4154-a340-69118c8d24ed)

Configure VM
![VM Configure](https://github.com/user-attachments/assets/29b7e0b1-270d-42af-9ca8-38e590fe593f)

Virtual Network for Firewall 
![VN Create 2nd VN for firewall to sit](https://github.com/user-attachments/assets/b2596f05-f038-40db-924d-bcaf953d0037)

Peer Firewall network and web server network to allow communication between the two 
![VN Peer Firewall Hub to WebServer](https://github.com/user-attachments/assets/24a7aad5-6378-4e1d-96b6-2777f414fe39)

Web Server and Firewall Synced
![VN Web Server and Firewall Synced](https://github.com/user-attachments/assets/98dc021a-0f62-43a8-88dd-49e7665b04ac)

Firewall Created 
![FW Creation](https://github.com/user-attachments/assets/1d2e633e-cd52-4aaa-87b9-8a1ce452638c)

Connect firewall to virtual network created for it
![FW Connect Fw to Vnet for FW Hub](https://github.com/user-attachments/assets/15616551-06f9-4c6c-b809-e88db343d73f)

Creating NAT Rule of Firewall for HTTPS Traffic 
![FW Create NAT Rule](https://github.com/user-attachments/assets/ee8e0d82-4b08-4ece-acbb-fa142c3431b2)

Add DNS Rule on Firewall 
![FW DNS Rule](https://github.com/user-attachments/assets/9b39885e-bcf3-4165-997f-2cbfccb3ab30)

Add firewall application rules 
![FW App Rule](https://github.com/user-attachments/assets/803f71b6-a6ac-49ea-b14c-2e8cd452e2c8)

NAT rule that will allow web server to provide remote access to VM 
![FW Create Nat rule that will allow web server to provide remote access to VM](https://github.com/user-attachments/assets/fb29338c-b0d1-4b88-8061-157e228abfda)

Just in Time access enabled for VM
![JIT enabled](https://github.com/user-attachments/assets/82354654-03f0-4d49-8ad7-f2e379feee86)

VM has JIT enabled and can be accessed by RDP 
![VM Request JIT Access for RDP to WebServer](https://github.com/user-attachments/assets/3ae38599-334c-4f5f-a020-6427b161aa56)

