# Cisco-Packet-Tracer-101
This repository will contain basic packet tracer network models

<h3>01. Connecting 2 PCs with a Cross Fast Ethernet Cable</h3>
<ul></ul>
<img width="564" height="400" alt="1 to 1 connection" src="https://github.com/user-attachments/assets/fd0e70c6-0946-463a-b770-037f0420be28" />
<P>The is a simple one to one computer connection using the IPs displayed above, use the ping command to estabilsh that there is connection within the 2</P>
<h3>02. Using a HUB in a local area network</h3>
<ul></ul>
<img width="610" height="523" alt="HUB " src="https://github.com/user-attachments/assets/95ce093d-f4ef-4f02-b94f-f54b2c5ef5b9" />
<P>Whats a HUB? A hub is a networking device that enables connection with a computer network. When data is send from one computer to another, the data is "boardcast" to all the other computers connected to the hud's ports. #hint: The hub has no memory.</P>
<h3>03.Understand how a switch is different than a hub</h3>
<ul></ul>
<img width="730" height="520" alt="3" src="https://github.com/user-attachments/assets/0c2ce19e-fa0f-4558-b8a4-45ed9d52de84" />
<p>The switch is also a networking device just like the hub, the difference is that the switch(layer 2) allows unicast,boardcast and multicast. And unlike the hub its duplex meaning it can send/recieve data at the same time #hint: The sitch has memory</p>
<h3>04. Learn how a router is used within 2 local area networks</h3>
<ul></ul>
<img width="1279" height="631" alt="4" src="https://github.com/user-attachments/assets/ea5fec4b-0dd8-4697-be40-4bff06c25090" />
<p>A Router is a networking device that allows connection between 2 or more local area networks. After assigning IP address/subnet mask to the device in the Local area networks. In the router inerface in the GigabiEhernet 1 and 2 port an IP and subnet for the two LANs was configured which allowed data to be sent from one LAN to Other. </p>
<h3>05.implementing a repeater in our computer network </h3>
<ul></ul>
<img width="652" height="422" alt="6" src="https://github.com/user-attachments/assets/fd874dfa-d485-4b5a-8ad2-d4c44fb4d8ed" />
<p>A repeater is a device used to boost weak signal to cover more distance. The repeater was connected to the switches of the LANs to boost the connection between the 2 networks</p>
<H3>06. Implementing a access point into LAN</H3>
<ul></ul>
<img width="633" height="396" alt="7" src="https://github.com/user-attachments/assets/1cf1a7a4-097d-4664-abf6-2265269628de" />
<p>A access point is a device that grants wired network with a wireless connection. The Lan has wireless devices and a switch connected to the access point, giving the computers connection via straight though copper</p>
<h3>Implementing a DHCP</h3>
<UL></UL>
<img width="1166" height="571" alt="8" src="https://github.com/user-attachments/assets/f5c3c06e-c6e4-4628-b71e-7f1fc5fc9b89" />
<p>Dymanic host configuration protocol is a the process of assign IP addresses to devices in the network automatically. After assigning a IP address to the server i used the dhcp service to create the pool name, insert the starting IP address and subnet. Made the max number of users to be 10. Which assigned the PCs in the network with IP adderesses</p>
<h3>Simulating a Email Server</h3>
<ul></ul>
<img width="1042" height="575" alt="9" src="https://github.com/user-attachments/assets/f2d5228b-bddf-4b65-b6cc-beca7980ce5b" />
<p>Email is digtal messages betweem users through computers. In the servers email services i added users and created passwords. Set the incoming and outcoming server to the Servers IP Address. Which users used to sign in to thier emails allowing them to send messages back and forth</p>
<h3>Simulate FTP</h3>
<UL></UL>
<img width="1123" height="627" alt="file transfer" src="https://github.com/user-attachments/assets/41e0fe9c-1150-4810-babf-7c8789d18a79" />
<P>File transfer protocol is used to transfer computer files between a client and a server. Firstly you would need to assign your server with a ip adresss and set up a dns server. You will also need to assign your pc with static ip adderess if you dont have DHCP configured in your network, dont forget to assign the PCs with the dns server ip. On the server make a FTP service and create the users you would like in your network setting them with permissions. Haed over to one of the PCs command prompt. Use FTP command follow with the FTP Servers IP address, this command is used to establish connect from the PC to the FTP server. Its then going to ask for a username and password. You can then use the "put" command to upload a file.txt and a get command to "get" the file.txt from the server</P>
