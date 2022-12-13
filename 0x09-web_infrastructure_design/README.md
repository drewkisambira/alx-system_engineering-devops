0x09. Web infrastructure design
Web Infrastructure is the physical hardwarem transmission media, and software used to interconnect computers and users on the internet. It includes internet servers, web servers, internet storage, network equipment and infructructure software. The design is the architecture on the environment to ensure faster response time to users or clients and also allow for further scale in future.

Horizontal and vertical scaling.
Horizontal scaling or scaling out involves adding additional servers.
Vertical scaling or scaling up involves adding more resources to the existing servers.
Files Descriptions
0-simple_web_stack - a one server web infrastructure that hosts the website that is reachable via www.foobar.com.
1-distributed_web_infrastructure - a three server web infrastructure that hosts the website www.foobar.com.
2-secured_and_monitored_web_infrastructure - a three server web infrastructure that hosts the website www.foobar.com, it must be secured, serve encrypted traffic, and be monitored.
3-scale_up - Split components (web server, application server, database) with their own server
Resources
DNS
Learn everything about DNS in cartoon
A
CNAME
MX
TXT
Use DNS to scale with round-robin DNS
What is an NS Record?
What is an SOA Record?
Monitoring
monitoring tools: newRelic, DataDog, Uptime Robot, Nagios, WaveFront.
Web Server
Wikipedia page about web server
Web server
What is a Web Server?
Network Basics
What is a protocol
What is an IP address
What is TCP/IP
What is an Internet Protocol (IP) port?
Load Balancer
Load-balancing
Load-balancing algorithms
Server
What is a server
What is a server
Where are servers hosted (data centers)
LAMP Stack
Others
What is a database
What's the difference between a web server and an app server?
DNS record types
Single point of failure
How to avoid downtime when deploying new code
High availability cluster (active-active/active-passive)
What is HTTPS
What is a firewall
