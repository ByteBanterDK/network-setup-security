<h1> <body> Network Infrastructure and Security Setup </body> </h1>

<h2>Description</h2>
This project involves setting up and securing a home network infrastructure using the ARCHER AX10 router and a Virgin Media box. The goal is to ensure a robust and secure network environment that optimizes connectivity and provides secure access for both primary users and guests. The project includes configuring the router, securing network access, setting up IPv6, and demonstrating how to manage and monitor the network effectively.
<h2>Key Objectives:</h2>
- Set up ARCHER AX10 Router: Establishing the ARCHER AX10 router and configuring it with the Virgin Media box for optimal performance.
- Secure Network Access: Configuring secure passwords and enabling WPA3 encryption to ensure network security.
- Guest Network Configuration: Setting up a separate guest network to provide secure and limited access for visitors.
- IPv6 Configuration: Enabling and configuring IPv6 to future-proof the network and improve performance.
- Router Management: Demonstrating how to use the router's web interface for configuration and monitoring.
- QR Code Generation: Creating QR codes for easy Wi-Fi access, allowing guests to connect to the guest network by scanning the code with their phones.
- Network Monitoring: Using built-in router tools to monitor network performance and connected devices.

<h2>Languages and Utilities Used</h2>
Languages: Bash, Command Prompt (CMD)
Utilities: OBS Studio (for recording setup process), QR Code generators

<h2>Environments Used</h2>
Operating Systems: Windows 10 Pro, Android/iOS (for smartphone setup)
Hardware: ARCHER AX10 Router, Virgin Media Box
Tools: Router's web interface, QR Code generation tools

<h2>Program Walk-through:</h2>
<br />
Let's start off by setting up the ARCHER AX10 Router on the computer first. Procced to connect your ethernet cable router to your ISP. 
<h5> Now go to your ISP for example BT, Virgin media or Sky. Then plug in the ethernet cable, that comes with your router into the Sky hub for example: </h5>
<img src="https://i.imgur.com/qCwUNzX.jpg">
Now we need to reset our network router, this is for me as i already set the router up before however i want to demonstrate how to reset and you can see the <body> ETHERNET CABLE</body> is plugged in back of the router into your ISP.
<img src="https://i.imgur.com/r8gohXN.jpg">
You can use a toothpick for example, to poke the hole gently for it to reset:
<img src="https://i.imgur.com/TQxdfnP.png">
You can see when <body> RESETED </body> the router it will be flashing lights, however we need to setup the network and make it more secure:
<img src="https://i.imgur.com/jLiT3Yj.jpeg">
<h3> Finally most imporant step</h3>
Have look behind your router, we will need the Password/Pin to get into the wifi and have internet connection:
<img src="https://i.imgur.com/yCZW87I.jpg">
<br />
<br />
Turn on your computer, then click on the wifi symbol and you will find your router wifi SID, click on it enter your password/pin:
<img src="https://i.imgur.com/UVwL3LK.jpg">
When connected to your wifi, go on to your perferd search engine, then input your routers ip address you can find it online <body> Password would be admin</body> You can find the passwords for your routers online:
<img src="https://i.imgur.com/p8ORCQr.png">
When logged in you will be greeted with a lot of information but don't worry i will be helping you go through the proces Starting :
<img src="https://i.imgur.com/pjvUz6D.png">  
Now let's click on client's here you will see a view of devices that are connected to the router, having acess to interent: 
<img src="https://i.imgur.com/whmRFQr.png">
Starting off with the interent option, you can pick many interent connections type and even change your mac address: 
<img src="https://i.imgur.com/30wJwrK.png"> <img src="https://i.imgur.com/eHk902J.png"> 
Now procced to click on "wireless" we will be securing our network:
<img src="https://i.imgur.com/DbQNxUu.png"> 
Make sure to change the network security to WPA3 the reason is:
WPA3 provides better security than WPA2:

Stronger Encryption: Harder for attackers to crack passwords.
Protected Management Frames: Better defence against eavesdropping and forgery.
Simplified Connectivity: Protects against common attacks even with weaker passwords.
Forward Secrecy: Keeps past sessions secure even if one is compromised.
WPA3 enhances your network's security against modern threats:
<img src="https://i.imgur.com/MGKotOR.png">
After change the SID and Password to something secure especially when it comes to the password:
<img src="https://i.imgur.com/00nfUrx.png">
Then procced to create a guest network this is imporant because it provides a separate, secure connection for visitors, protecting your main network and its devices from potential security risks:
<img src="https://i.imgur.com/M7rFAF9.png"> <img src="https://i.imgur.com/0WsI4wn.png">
Now let's get busy, click on advance you will see interent and Lan and many more features below however we will be creating IVP6m, Port fowarding, DCHP sever and many more:
<img src="https://i.imgur.com/Kxf5jAD.png">
Setting up a DHCP server is important because it automatically assigns IP addresses to devices on a network, simplifying management and ensuring efficient IP address allocation without conflicts, let's add a device onto the DCHP server:
<img src="https://i.imgur.com/xxjKKJQ.png">
Click on the "View Connection devices" then pick the device you would perfer:
<img src="https://i.imgur.com/IKBzaqY.png"> 
<img src="https://i.imgur.com/3z5fsbU.png">
When added the devices would be under DHCP Client List:
<img src="https://i.imgur.com/FMfOUjv.png">
With this demonstrate we won't be setting up IPTV/VLAN as it optimises network performance by separating IPTV traffic from other data, ensuring high-quality video streaming without interfering with regular internet usage, we want to go through the basis:
<img src="https://i.imgur.com/G7lfk1i.png">
Make sure to not turn on Guest permissions should not allow guests to see each other or your local network to prevent potential security risks, such as unauthorised access to personal data and devices, which could lead to privacy breaches or network attacks:
<img src="https://i.imgur.com/MhGhGwJ.png">
Below "Guest Network" their is option Wireless Schedule this is great feature if for example you're not home Fri-Sat 11am - 6pm you can turn the router off:
<img src="https://i.imgur.com/52F4xbT.png">
<img src="https://i.imgur.com/Bqfhjqp.png">
<img src="https://i.imgur.com/evwhrJF.png">
<br />
<br />
Why WPS Should Be Turned Off
WPS (Wi-Fi Protected Setup) should be turned off because it has known security vulnerabilities that can be exploited by attackers to gain access to your network, potentially leading to unauthorised usage and compromising network security.

Benefit of Keeping WPS On
The primary benefit of keeping WPS enabled is that it simplifies the process of connecting devices to your network, allowing users to easily add new devices without having to manually enter complex Wi-Fi passwords.
<img src="https://i.imgur.com/elIkXNK.png">
<img src="https://i.imgur.com/tzATpTO.png">
Moving forward to the next section "NAT FORWARDING", setting up port forwarding click on on add:
<img src="https://i.imgur.com/OTYZASV.png">
Then page will pop up showing view common services and view connected devices:
<img src="https://i.imgur.com/UQlbH19.png"> 
Common services has many protocols, for this demonstrate i am picking HTTP port 80:
<img src="https://i.imgur.com/0HEwTKx.png">
<h4> <body> Benefit of Port Forwarding </h4> </body>

Port forwarding is beneficial as it allows external devices to access services on a local network, such as a web server (HTTP), enabling remote access to applications and improving network flexibility and functionality:
<img src="https://i.imgur.com/3Stntkg.png">
<body> <h4> Benefit of Port Triggering </body> </h4>
Port triggering dynamically opens specific ports when an application initiates a connection, providing a more secure way to handle multiple services by only allowing access when needed and reducing the risk of constant exposure:
<img src="https://i.imgur.com/dZupl8E.png">
It is recommended to turn off UPnP (Universal Plug and Play) because it can expose your network to security risks by allowing devices to open ports automatically without user intervention, potentially leading to unauthorised access or malicious attacks:
<img src="https://i.imgur.com/7ABLOYW.png">
For the last option on "NAT FOWARDING" Instead of UPnP, consider using a DMZ (Demilitarised Zone) for better control over which devices can access your network:
<img src="https://i.imgur.com/u4Poqap.png">
Now enabling QOS,(Quality of Service) can help by prioritising network traffic, ensuring that critical applications and services receive the necessary bandwidth and perform optimally, even during high-traffic periods. This is particularly useful for streaming, gaming, and VoIP calls, where consistent performance is essential:
<img src="https://i.imgur.com/eNuDboy.png">
You even have the chance to prioritise any devices that are connected to your router, to include turning on for couple of hours or having the ability to setup schedule: 
<img src="https://i.imgur.com/3P40m8i.png">
The schedule, works just as setting up for the router you could turn off the QOS between mon-fri or just a specific day. 
<img src="https://i.imgur.com/JzLxbiX.png"> 
Let's keep the firewall settings default however, short brief explation for each setting below:
<h2> SPI Firewall:</h2>
- Monitors incoming and outgoing packets to ensure they are part of a legitimate session, enhancing security by blocking suspicious traffic.

<h2> Respond to Pings from LAN:</h2>
- Allows devices within the local network to check connectivity and diagnose internal network issues.

<h2>Respond to Pings from WAN:</h2>
- Disabling this improves security by making the router less visible to potential attackers on the internet.
<img src="https://i.imgur.com/SFOZIK5.png">
Next setting is access control this is great feature to enable:
<img src="https://i.imgur.com/T8pX9mP.png">
<h2> Blacklist and Whitelist </h2>
<body>Blacklist:</body>

A list of devices or IP addresses that are explicitly denied access to the network. This is used to block unwanted or harmful devices.
<body>Whitelist:</body>

A list of approved devices or IP addresses that are granted access to the network. This ensures only trusted devices can connect, providing an additional layer of security.
<img src="https://i.imgur.com/oIQYv59.png">
You can see below in the screen soon as i added my iphone, the device i wanted to black list it immediately disconnected me from the interent:
<img src="https://i.imgur.com/DhRBXP7.png">
<h2>Benefits of Access Control on a Router</h2>
Access Control:

Enhances network security by allowing the router to restrict or permit specific devices from accessing the network, thus preventing unauthorised usage and potential security breaches.
<img src="https://i.imgur.com/Y5n0byg.png">
Moving along, we have IP & Mac binding the Importance & Benefits of IP & MAC Binding are:
<body>Importance:</body>

Preventing IP Spoofing: IP & MAC binding helps prevent IP spoofing, a common technique used by attackers to impersonate a trusted device on the network.
Network Security: It ensures that only devices with a specific MAC address can use a specific IP address, adding an extra layer of security to your network.
<body>Benefits:</body>

Enhanced Control: Provides better control over which devices can access the network by binding a device's MAC address to a specific IP address.
Consistent Connectivity: Ensures that devices always get the same IP address, which is crucial for network stability and for devices that require a static IP, such as servers and printers.
Easier Network Management: Simplifies network management by making it easier to identify devices on the network and enforce network policies.
<img src="https://i.imgur.com/XTR8Po4.png">
<h2>Application Layer Gateway (ALG)</h2>

Importance:
- Protocol Support: Helps routers handle protocols with dynamic ports, such as SIP for VoIP and FTP.
  
Benefits:
- Seamless Communication: Ensures applications like VoIP work properly through NAT.
- Enhanced Security: Inspects specific protocols for better security.
- Improved Performance: Optimises connections and data integrity.
<img src="https://i.imgur.com/e40UaMV.png">
For this demonstration, we won't go through the entire process of setting up an OpenVPN on the router. However, I will show you a website where you can start, First is to enable the "OpenVPN":
<img src="https://i.imgur.com/MxJUVHc.png">
Then generate a certificate could take up to couple of minutes:
<img src="https://i.imgur.com/6Gu0NM4.png">
The webiste you can setup is called OpenVPN, this will allow you to have a VPN on your router and any devices even guests will have more privacy and security:
<img src="https://i.imgur.com/39M5reR.png">
PPTP (Point-to-Point Tunneling Protocol) is an older VPN protocol that's easy to set up and has lower overhead, making it faster. However, it has weaker security compared to newer protocols, so it's generally not recommended for secure communications.
<img src="https://i.imgur.com/782B6Tk.png">
IPv6 is crucial for expanding internet capacity and helpful to increase number of connected devices, offering improved security and performance compared to IPv4, click on interent connection type, and pick 6to4 tunnel for this demonstration:
<img src="https://i.imgur.com/oWzCXSq.png">
You can see, checking your wifi status it show's no "IPV6 Connectivity":
<img src="https://i.imgur.com/LFUBv88.png">
When IPV6 is turned on and choosing 6to4 Tunnel, You would have to click on connect for it to work and your IPV6 address will pop up:
<img src="https://i.imgur.com/wPoHS9o.png">
<img src="https://i.imgur.com/NEb0t6U.png">
EasyMesh is beneficial because it allows for seamless integration and management of multiple Wi-Fi access points within a network, ensuring consistent coverage and performance throughout the entire area:
<img src="https://i.imgur.com/Y8xNRJM.png">
You can purchase them for cheap price online just searching up easymesh:
<img src="https://i.imgur.com/hnH8Zqv.png">
Navigating into the systems settings, click on administration now you have the optioin to change your router's local management password also setup "local management":
<img src="https://i.imgur.com/8t8zHSm.png">
Setting up local management is beneficial as it enables users to configure and monitor their network devices directly from within their local network, providing greater control and flexibility over network settings and security features.
<img src="https://i.imgur.com/KiouGjA.png">
To setup a QR code you would need to Navigate back to wireless settings then next to your wifi, click on share network and you can save it even on your moblie device, or print it out, letting your guests come through your door and scan the QR code for that specific network:
<img src="https://i.imgur.com/a3sQ6ji.png">
Finally Let's setup the TP-Link on the moblie device Procced to download TP-Link Tether on app store or google play store for this demonstrate it's going to be for app store:
<img src="https://i.imgur.com/vSlUjFT.png">
<br />
<br />
Go on to your settings, click onto settings and the wifi SID for your router will pop up connect to it with using the password/pin:
Go through the process setting up the app, Accept the terms of use and privacy policy:
<img src="https://i.imgur.com/lvgMiDD.png">
Next allow permission for "Tether" connect to local networks:
<img src="https://i.imgur.com/kEQorNV.png">
Create a TP-Link ID make sure you remember the email address and the password: 
<img src="https://i.imgur.com/8GHJ3JX.png">
Turn on two step verification and go through that process:
<img src="https://i.imgur.com/uHPObKT.png">
Click on add device, and choose the router type today we're setting up a Wirless Router:
<img src="https://i.imgur.com/A8TE7tU.png"> <img src="https://i.imgur.com/4wY8Q6y.png">
<img src="https://i.imgur.com/iYkffS6.png">
When connected to the wifi, go back onto the app it will start "searching for devices":
<img src="https://i.imgur.com/26NJ3HV.png">
Your specifically model will pop up click on it:
<img src="https://i.imgur.com/fvFBwlC.png">
Create a local account, make sure to remember the credentials:
<img src="https://i.imgur.com/VC9vw5M.png">
Select "Dynamic IP" connection type for now then procced to go onto the next step:
<img src="https://i.imgur.com/BFrys2X.png">
Leave the MAC Address, then it will load all the settings you have just configured could take couple of minutes:
<img src="https://i.imgur.com/uFSCgml.png"> 
<img src="https://i.imgur.com/H1khrxH.png">
<img src="https://i.imgur.com/O69CCl0.png">
Now you have access to the router on your moblie device:
<img src="https://i.imgur.com/aWK4ABU.png">
<br/>
