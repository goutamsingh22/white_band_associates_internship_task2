# internship_task2

# PART A 


# 1. Router
A router connects different networks and allows devices in a local network to access the Internet.
The router receives data from one network and forwards it to the correct destination network using IP addresses. It acts as a traffic manager between your home network and the Internet.
Real-World Usage
•	Home Wi-Fi routers 
•	Office networks 
•	Connecting multiple devices to the Internet 

# 2. Switch
A switch connects multiple devices within the same local network and allows them to communicate efficiently.
The switch uses MAC addresses to send data only to the intended device instead of broadcasting it to all devices.
Real-World Usage
•	Connecting computers in offices 
•	School computer labs 
•	Data centers 

# 3. Hub
A hub connects multiple devices in a network and shares data among them.
When a hub receives data, it sends the data to all connected devices regardless of the intended recipient.
Real-World Usage
•	Small or old networks 
•	Educational demonstrations 
•	Rarely used today because switches are more efficient 

# 4. Access Point (AP)
An Access Point provides wireless connectivity to devices in a network.
It receives data from a wired network and broadcasts Wi-Fi signals so wireless devices can connect.
Real-World Usage
•	Offices 
•	Colleges and universities 
•	Shopping malls and airports 

# 5. Firewall
A firewall protects a network or device from unauthorized access and cyber threats.
It monitors incoming and outgoing network traffic and allows or blocks data based on security rules.
Real-World Usage
•	Home routers with built-in firewall 
•	Corporate networks 
•	Server security systems 

# 6. Modem
A modem connects a home or office network to the Internet Service Provider (ISP).
It converts digital signals from a computer into signals that can travel through telephone, cable, or fiber lines and vice versa.
Real-World Usage
•	Broadband Internet connections 
•	Fiber Internet services 
•	Cable Internet connections

# PART B 

1. 192.168.1.10 – Private IP
This IP belongs to the 192.168.x.x private address range used in home and office networks.
2. 10.0.0.5 – Private IP
This IP belongs to the 10.x.x.x private address range commonly used in large organizations.
3. 172.16.5.20 – Private IP
This IP falls within the 172.16.x.x to 172.31.x.x private address range.
4. 8.8.8.8 – Public IP
This IP is publicly accessible on the Internet and is used as a public DNS server.
5. 1.1.1.1 – Public IP
This IP is publicly accessible on the Internet and is used as a public DNS server.
6. 192.168.100.1 – Private IP
This IP belongs to the 192.168.x.x private address range and is often used by routers.

# PART C 

1. Which IP range does your device belong to?
My device's IPv4 address is 192.168.1.25, which belongs to the 192.168.0.0 – 192.168.255.255 range.
This range is reserved for private networks and is commonly used in homes, offices, and educational institutions.

2. Is it Public or Private?
The IP address 192.168.1.25 is a Private IP Address because it falls within the private IP range defined by RFC 1918.
Private IP addresses are used inside local networks and cannot be directly accessed from the Internet.

3. What role does your router play in your network?
The router acts as a bridge between my local network and the Internet. It assigns IP addresses to devices, forwards data packets to the correct destination, and allows multiple devices to share a single Internet connection.
The router also serves as the Default Gateway, enabling communication with external networks.

4. What would happen if the DNS server stopped working?
If the DNS server stopped working, devices would not be able to translate domain names into IP addresses.
For example:
•	google.com would not open. 
•	youtube.com would not open.


# PART D


# PART E 
# 1. What IP address did DNS return for Google?
The DNS server returned the IP address 142.250.183.78 for google.com. This means that the domain name google.com was successfully translated into its corresponding IP address.
Your IP may be different because Google uses multiple servers around the world. Write the IP address shown on your system.

# 2. Was the ping successful?
Yes, the ping was successful because replies were received from Google's server. This confirms that the network connection and Internet access are working properly.
If you see packet loss like:
100% packet loss
then the ping was not successful.

# 3. Why is DNS important before communication begins?
DNS (Domain Name System) is important because it converts human-readable domain names such as google.com into IP addresses that computers can understand. Before a device can communicate with a website, it must know the website's IP address. DNS performs this translation, allowing users to access websites using names instead of remembering numerical IP addresses.

However, if the IP address of a website is known, it may still be possible to access the website directly using its IP address.
Therefore, Internet connectivity may still exist, but website names cannot be resolved.
