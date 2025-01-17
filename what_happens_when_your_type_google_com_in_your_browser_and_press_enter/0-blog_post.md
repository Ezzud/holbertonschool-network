# What Happens When You Type "https://www.google.com" and Press Enter?

We've all done it—typed __https://www.google.com__ into the browser and pushed the Enter button. But have you ever wondered what happens behind the scenes? A slick very complicated working mechanism of ranges of technology and processes provides the homepage (or any site) to your screen. Let's break down the journey step by step.

## 1. DNS Request: The Domain Name System (DNS)

So on typing out __https://www.google.com__ on the browser and hitting Enter, the first thing that happens is a DNS (or Domain Name System) lookup. Understand that your browser needs to convert the human readable domain name **www.google.com** into an IP address (Internet Protocol address), which is a unique numerical identifier for computers connected to the internet. The DNS functions almost like a phonebook for the internet in terms of matching domain names with IP addresses.

If the domain name is not already resolved on your machine (for example, it is not cached), your browser will send a request to a DNS server. That server then checks its own records, or other DNS servers, until it finds the address that corresponds to google.com. After acquiring this address (for instance, 142.250.64.78), it serves it back to your browser.

## 2. TCP/IP: Establishing a Connection

Armed with the IP address, your browser would now have to establish contact with a web server that would be serving the site. In here, TCP/IP (Transmission Control Protocol/Internet Protocol) comes into play, being the basic communication protocol suite that is being used by the internet to transfer data.

Here is where the magic of three-way handshakes comes into being: 
- 1. Your browser sends a message requesting a connection (called SYN) to the server. 
- 2. The server acknowledges this message with a reply that also includes its own request for a connection (called SYN-ACK).  
- 3. Your browser will now send back yet another message confirming that the connection has been established (ACK). 


