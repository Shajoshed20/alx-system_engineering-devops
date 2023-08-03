# 0x07. Networking basics #0

## Learning Objectivies :page_with_curl:

### OSI Model
* What it is
* How many layers it has
* How it is organized

### What is a LAN
* Typical usage
* Typical geographical size

### What is a WAN
* Typical usage
* Typical geographical size

### What is the Internet
* What is an IP address
* What are the 2 types of IP address
* What is localhost
* What is a subnet
* Why IPv6 was created

### TCP/UDP
* What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
* What is the main difference between TCP and UDP
* What is a port
* Memorize SSH, HTTP and HTTPS port numbers
* What tool/protocol is often used to check if a device is connected to a network

## Tasks :woman_technologist:

* Task 0 - Questions:
    - What is the OSI model?
    - How is the OSI model organized?

* Task 1 - Questions:
    - What type of network a computer in local is connected to?
    - What type of network could connect an office in one building to another office in a building a few streets away?
    - What network do you use when you browse www.google.com from your smartphone (not connected to the Wifi)?

* Task 2 - Questions:
    - What is a MAC address?
    - What is an IP address?

* Task 3 - Questions:
    - Which statement is correct for the TCP box:
        - It is a protocol that is transferring data in a slow way but surely
        - It is a protocol that is transferring data in a fast way and might loss data along in the process
    - Which statement is correct for the UDP box:
        - It is a protocol that is transferring data in a slow way but surely
        - It is a protocol that is transferring data in a fast way and might loss data along in the process
    - Which statement is correct for the TCP worker:
        - Have you received boxes x, y, z?
        - May I increase the rate at which I am sending you boxes?

* Task 4 - Write a Bash script that displays listening ports:
    - That only shows listening sockets
    - That shows the PID and name of the program to which each socket belongs

* Task 5 - Write a Bash script that pings an IP address passed as an argument.