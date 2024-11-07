# 🐱 HTB Meow Lab - Tasks and Answers 🐾


## Task 1: What does the acronym **VM** stand for? 🖥️

- **Answer**: **Virtual Machine** 🌐
- **Explanation**: The acronym **VM** stands for "Virtual Machine." It's a software-based emulation of a physical computer that lets you run multiple operating systems on a single host. Think of it as a computer within a computer! 🖥️💻


## Task 2: What tool do we use to interact with the operating system in order to issue commands via the command line? 🖱️

- **Answer**: **Terminal** 🖥️
- **Explanation**: The **terminal** is the command-line interface (CLI) where you can type commands, such as starting your VPN connection, or running other network-related tasks. It's also known as a **console** or **shell**! 💻⏳


## Task 3: What service do we use to form our VPN connection into HTB labs? 🔒

- **Answer**: **OpenVPN** 🌐
- **Explanation**: **OpenVPN** is the service used to establish secure and encrypted VPN connections for HTB labs. It's open-source and widely used for making safe connections over the internet. 🔐🌍


## Task 4: What tool do we use to test our connection to the target with an ICMP echo request? 🌐

- **Answer**: **Ping** 🏓
- **Explanation**: The **ping** command is used to test whether a host is reachable on a network by sending ICMP echo requests. It’s a simple and effective tool to check if the target is online. 🖧✨
-  Command that gives you the answer: ```sudo nmap <ip> -A```


## Task 5: What is the name of the most common tool for finding open ports on a target? 🔍

- **Answer**: **Nmap** 🔒
- **Explanation**: **Nmap** (Network Mapper) is the go-to tool for discovering open ports and services on a target system. It helps hackers and security professionals gather information for penetration testing. 🚪🔍


## Task 6: What service do we identify on port 23/tcp during our scans? 💻

- **Answer**: **Telnet** 🖥️
- **Explanation**: **Telnet** is a protocol often running on port 23/tcp, used for text-based communication between systems. If open, it allows remote access to the target. 🚪💬


## Task 7: What username is able to log into the target over telnet with a blank password? 🚪🔑

- **Answer**: **root** 🧑‍💻
- **Explanation**: The **root** user is the highest privilege user, and it can log into the target system over **Telnet** with a blank password. This can be a security vulnerability if not properly secured. 🛡️🔓


## 🎯 Submit Flag 🏁

- **Flag**: `b40abdfe23665f766f9c61ecba8a4c19` 🏆
- **Explanation**: After successfully completing all tasks, this flag is the final step to submit. You've cracked it! 🎉

---

💡 **Pro Tip**: Refresh your page after 2-3 minutes if HTB doesn’t recognize your VPN connection right away. You can also use **Pwnbox** if you're having trouble with local setups! 💻✨
