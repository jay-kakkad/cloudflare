## Instructions to Run the above Cli application

### Functionality
	1. Accpets Ipv4 and Ipv6 address
	2. Send ICMP "echo request" in infinite loop
	3. Allow to set TTL as an argument and report the corresponding "time exceeded” ICMP messages
	4. Report loss and RTT times for each message

### Two files are included 
	1. Source code ping.C
	2. Compiled version of ping.C

### How to Run
	1. open command line or terminal where the above code is located
	2. For compilation: gcc -o ping ping.c
	3. Execute: ./ping <hostname> <ttl_val>
