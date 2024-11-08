# 🦌 HTB Fawn Lab - Tasks and Answers 🐾

To attack the target machine, you must be on the same network. Connect to the Starting Point VPN using one of the following options:

- **Connect using Pwnbox** 🖥️: A preconfigured, browser-based virtual machine with all the hacking tools you need pre-installed. You get 2 hours free with Pwnbox—upgrade to VIP+ for unlimited access.
- **Connect using OpenVPN** 🔒: Use your own machine by downloading your VPN configuration file and connecting from your environment.

💡 **Tip**: It may take a minute for HTB to recognize your connection. If you don't see an update after 2-3 minutes, refresh the page.

---

## Task 1: What does the 3-letter acronym **FTP** stand for? 📂

- **Answer**: **File Transfer Protocol** 🌐
- **Explanation**: **FTP** is used to transfer files between computers over a network. It's an older protocol commonly used for sharing files in client-server models. 📁💻

## Task 2: Which port does the **FTP** service usually listen on? 🔌

- **Answer**: **21** 🔢
- **Explanation**: **FTP** typically operates on port 21 by default, allowing clients to connect and transfer data to and from the server. 🔗📡

## Task 3: What acronym is used for a secure extension of FTP that operates over SSH? 🔐

- **Answer**: **SFTP** 🔒
- **Explanation**: **SFTP** (Secure File Transfer Protocol) is an FTP extension that provides encrypted file transfers by running over the SSH protocol, ensuring privacy and data integrity. 🔑💻

## Task 4: What command can we use to send an ICMP echo request to test our connection to the target? 🌐

- **Answer**: **ping** 🏓
- **Explanation**: The **ping** command sends ICMP echo requests to test whether a host is reachable on a network. It's a basic tool to check the availability of the target system. 🖧✨
- **Command**:
  ```bash
  ping <target_ip>

## Task 5: From your scans, what version of FTP is running on the target? 📋

- **Answer**: **vsftpd 3.0.3** 📝
- **Explanation**: The scan reveals that **vsftpd** (Very Secure FTP Daemon) version 3.0.3 is running on the target, indicating the FTP server’s software and version. 📊

## Task 6: From your scans, what OS type is running on the target? 🖥️

- **Answer**: **Unix** 🐧
- **Explanation**: The scan shows that the target system is running a **Unix-based** operating system, commonly used in server environments. 🔍

## Task 7: What command displays the ftp client help menu? 📝

- **Answer**: **ftp -h** 📖
- **Explanation**: The **ftp -h** command shows the help menu for the ftp client, listing available commands and options. 📑💻
- **Command**: ```ftp -h```

## Task 8: What username is used over FTP to log in without an account? 👤

- **Answer**: **anonymous** 🌍
- **Explanation**: Many **FTP** servers allow the anonymous username for public access, typically for downloading files without a personal account. 🌐🔓

## Task 9: What response code indicates 'Login successful' in FTP? 📬

- **Answer**: **230** 📨
- **Explanation**: In **FTP**, the response code **230** confirms that the login was successful. Response codes in FTP indicate the status of various commands. 💬

## Task 10: What command, besides dir, lists files on the FTP server? 📁

- **Answer**: **ls** 📂
- **Explanation**: The **ls** command is widely used on Unix systems to list files and directories. On an FTP server, ls and dir both display contents. 📜

## Task 11: What command is used to download a file from the FTP server? 💾

- **Answer**: **get** 📥
- **Explanation**: The **get** command downloads files from an FTP server to the client’s machine, allowing you to retrieve data remotely. 📩
- **Command**: ```get <filename>```

## 🎯 Submit Flag 🏁

- **Flag**: **035db21c881520061c53e0536e44f815** 🏆
- **Explanation**: This flag is the final step to submit after completing all tasks successfully. Congratulations! 🎉

💡 **Pro Tip**: If you’re having trouble connecting, try Pwnbox for a preconfigured setup, or refresh your page after a few minutes if your VPN connection isn’t recognized right away. 🔄💻