# Task 1 
This repository contains all the submission material regarding task 1 for the internship.

## Task: Scan Your Local Network for Open Ports
- Objective: Learn to discover open ports on devices in your local network to understand network exposure.
- Tools: Nmap (free), Wireshark (optional)

## Steps performed:
1. I was using kali linux, hence nmap was installed already.
2. I opened my terminal and ran `ifconfig` to list the ip address for my local network. As seen in the below image :-
![image](https://github.com/user-attachments/assets/37296513-40cc-415b-9755-77890bc14010)
- It lists the ip ranges with IPv4 and IPv6 address types.
3. I then ran help command to see options available for nmap : `nmap -h`.
4. Then I saw some useful options, as the internet may contain any firewall or other rules, I used option `-sS` to stealth scan the network, `-Pn` to skip the host discovery, `-p-` to scan all the ports in the network, and `-oN` to save the result into a normal text file.
5. Hence I can now see which ports were open.
6. Now utilizing the information available, I noted the security risk that can be found from these ports. It can be found in Risk folder of the repository.

### Outcome: Basic network reconnaissance skills; understanding network service exposure.

## Conclusion:
- This task helped me understand how to use Nmap to perform a basic port scan on my local network. I identified active hosts, discovered open ports, and learned how to analyze the services running on them. This process is crucial in network security to assess potential vulnerabilities and reduce attack surfaces.
