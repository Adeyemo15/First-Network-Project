# First-Network-Project
My first hands-on networking project - building a home wireless network with DHCP, multiple clients, and full internet connectivity using Cisco Packet Tracer.
My First Step into Networking
A Personal Documentation
Who I Am
My name is Ogunlade Israel Adeyemo. I am building my foundation in cybersecurity and network engineering. This document marks the beginning of that journey.
Why I Started
I wanted to understand how devices actually connect to the internet. Not just as a user clicking "Connect to WiFi" - but what really happens underneath. How does information move from my laptop to a website on the other side of the world? What makes it possible? What keeps it secure?
I chose to start with the basics: building a home network from scratch.
What I Built
I created a complete home network using Cisco Packet Tracer. The network connects three devices through a wireless router to the internet.
The setup includes:
One laptop connecting wirelessly
Two desktop computers connecting through cables
One wireless router managing all connections
Full internet connectivity for all devices
How I Learned
Understanding the Router
The router became the center of everything. I learned it does three jobs at once:
First, it creates the wireless signal that devices connect to. I named my network "MyHome" and protected it with WPA2 security. This taught me that WiFi without proper security is like leaving your front door unlocked.
Second, it assigns IP addresses automatically. I discovered DHCP - a protocol that gives every device a unique address without me typing anything. The laptop received 192.168.0.4. The router itself lives at 192.168.0.1. Every device knows where to find the others.
Third, it connects the entire home network to the internet. Without this, my network would be isolated - devices could talk to each other, but nowhere else.
Watching Connections Happen
I opened the laptop's network settings and watched the numbers appear. IP address: 192.168.0.4. Subnet mask: 255.255.255.0. Default gateway: 192.168.0.1. DNS server: 209.165.200.230.
These were not just random numbers. Each one has a purpose. The IP address is the laptop's name on the network. The gateway is the door to the outside world. The DNS server translates website names into addresses the network understands.
Testing What I Built
I ran four tests to prove everything worked.
I pinged the router from the laptop. Four responses came back in less than one millisecond each. This meant the wireless connection was solid. The laptop and router were talking perfectly.
I pinged an internet address - 209.165.200.230. Four responses returned in 3 to 10 milliseconds. This proved the router was doing its job as a gateway. My private network was reaching the public internet.
I traced the route to that same internet address. The path showed three steps: first the home router, then a hidden step where the internet provider sits, then finally the destination server. The middle step showed "Request timed out" but I learned this is normal - many internet routers ignore these requests for security reasons.
I opened a web browser and loaded a real website. The page appeared. This was the final proof - from physical cables and wireless signals through network addresses and routing decisions all the way to a working application.
What These Numbers Mean to Me Now
Before this project, an IP address was just something technical. Now I see it as identity. Every device needs one to exist on a network. The subnet mask defines the neighborhood. The gateway is the exit door. The DNS server is the translator between human names and machine numbers.
The MAC address - 00D0.5876.4306 on my laptop's wireless adapter - is the permanent fingerprint burned into the hardware. The IP address is temporary, assigned for a visit. The MAC address is forever, tied to that specific piece of equipment.
The Wireless Details
My network runs on 2.4 GHz frequency. I chose Channel 1 at 2.412 GHz specifically. I learned that channels matter - neighboring networks can interfere if everyone uses the same one. The 20 MHz channel width keeps things stable rather than pushing for maximum speed.
The security is WPA2-Personal. This means a shared password protects the network. When the laptop connected, it proved its identity through this protocol. The data traveling through the air is encrypted. Someone nearby cannot simply listen in.
The wireless mode is Infrastructure - meaning all devices talk through the central router. They do not talk directly to each other. This is how real networks operate. The router controls everything.
Lessons That Stay With Me
Automatic does not mean magic. DHCP seems like magic when you first see it. An IP address just appears. But now I understand the conversation happening behind the scenes. The laptop asks. The router offers. The laptop requests. The router acknowledges. Four steps. Every time.
Security is built in, not added on. WPA2 is not an extra feature. It is essential. Without it, wireless data floats through the air for anyone to grab. With it, even if someone captures the signals, they see only scrambled information.
Testing proves understanding. I could have stopped after seeing the "Connected" status. But running ping commands and traceroute showed me the actual paths. The numbers confirmed the theory. The responses proved the configuration worked.
Layers matter. Physical cables and wireless signals form the bottom layer. IP addresses and routing sit above that. Applications like web browsers live at the top. Each layer depends on the one below. A problem at any level breaks the whole chain. Fixing networks means thinking in these layers.
The Challenges I Faced
At first, the laptop would not connect. I had entered the wrong network name. This taught me that precision matters in networking. One wrong character and nothing works.
I tried typing "clear" in the command prompt to clean my screen. The system rejected it. I learned that Windows uses "cls" instead. Small detail, but part of learning any system is learning its specific language.
Understanding why the second hop in my traceroute timed out confused me briefly. Research showed this is standard behavior. Not every timeout means something is broken. Sometimes it means security is working.
Where This Leads
This home network is small. Three devices. One router. But the principles scale everywhere. Enterprise networks with thousands of devices use the same concepts. The internet itself operates on these foundations.
I now understand:
How my phone connects to coffee shop WiFi
Why my home internet sometimes needs the router restarted
What network administrators mean when they talk about DHCP scopes
Why public WiFi warnings exist
More importantly, I have a base to build on. Every advanced topic in cybersecurity and networking rests on these fundamentals. Before I can secure networks, I must understand how they function. Before I can detect attacks, I must recognize normal traffic patterns.
This project was my first hands-on proof that I can build, configure, test, and verify a working network. The documentation in these screenshots and notes is evidence of that capability.
Technical Summary
Table
Element	Details
Network Address	192.168.0.0/24
Router Gateway	192.168.0.1
Laptop IP	192.168.0.4 (DHCP)
Wireless Network	MyHome
Security	WPA2-Personal
Frequency	2.4 GHz, Channel 1
Internet DNS	209.165.200.230
Testing Results	100% success on all connectivity tests
Final Thought
Every expert was once a beginner who refused to skip the basics. This project is my foundation. The configurations I built. The tests I ran. The errors I fixed. All of it becomes part of how I understand the digital world.
The network is small. The learning is real. The journey continues.
Documented by: Ogunlade Israel Adeyemo
Date: April 15, 2026
Project: Home Network Wireless Configuration
