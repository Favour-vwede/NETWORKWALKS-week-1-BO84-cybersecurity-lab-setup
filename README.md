
# Cybersecurity Lab Setup | Kali Linux & VirtualBox

Building a controlled virtual environment for cybersecurity learning, network analysis, and authorized security testing.

![Platform](https://img.shields.io/badge/Platform-VirtualBox-blue)
![OS](https://img.shields.io/badge/OS-Kali%20Linux-557C94)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project documents the setup of a virtual cybersecurity lab using **Kali Linux and Oracle VirtualBox**.

The goal was to create a controlled environment where I can explore cybersecurity tools, understand network configurations, and practice security-related tasks without directly modifying my host operating system.

This lab serves as the foundation for my hands-on cybersecurity learning journey and future practical projects.

## 🎯 Project Objectives

- Install and configure VirtualBox.
- Set up Kali Linux as a virtual machine.
- Configure the virtual machine's network settings.
- Check network connectivity and DNS resolution.
- Explore IP addressing and network configuration.
- Prepare a virtual environment for future cybersecurity exercises.
- Document the setup process and practical learning experience.

## 🏗️ Lab Architecture

The lab consists of a host computer running VirtualBox, with Kali Linux operating inside a virtual machine.

```text
        HOST COMPUTER
        Windows 11 Pro
              |
         VirtualBox
              |
        Kali Linux VM
              |
     Virtual Network
              |
    Future Lab Machines
```

Additional virtual machines can be added as the lab expands.

> Note: The diagram represents the planned lab structure. Additional target machines have not been included in the current setup.

## ⚙️ Lab Configuration

| Component | Configuration |
|---|---|
| Host Operating System | Windows 11 Pro |
| Virtualization Software | Oracle VirtualBox |
| Guest Operating System | Kali Linux |
| Host RAM | 8 GB |
| Host Storage | 256 GB SSD |
| Virtual Network | [Your configured network mode] |
| Kali Linux IP Address | [Your actual IP address] |
| DNS Server | [Your configured DNS server] |

*Replace the bracketed values with your actual network configuration.*

## 🛠️ Tools & Technologies

- **Kali Linux:** A Linux distribution designed for penetration testing and security auditing.
- **VirtualBox:** Virtualization software used to run Kali Linux separately from the host operating system.
- **Terminal:** Used to execute commands and inspect system and network information.
- **NetworkManager:** Used to view and manage network connections in Kali Linux.

## 🚀 Implementation Process

### Step 1: Install VirtualBox

Installed Oracle VirtualBox on the host computer to create and manage virtual machines.

### Step 2: Set Up Kali Linux

Downloaded and configured Kali Linux as a virtual machine within VirtualBox.

### Step 3: Configure Virtual Machine Settings

Configured the virtual machine's resources and network adapter to support the lab environment.

### Step 4: Inspect Network Configuration

Used Kali Linux terminal commands to examine network interfaces, IP addressing, routing, and DNS settings.

Commands used:

```bash
ip addr
ip route
cat /etc/resolv.conf
```

### Step 5: Verify Network Connectivity

Tested connectivity using:

```bash
ping -c 4 8.8.8.8
ping -c 4 google.com
```

The first command checks connectivity to an IP address, while the second also depends on DNS resolution.

### Step 6: Prepare for Future Exercises

Prepared the environment for future practical work involving network analysis, reconnaissance, vulnerability assessment, and other authorized cybersecurity exercises.

## 📸 Screenshots

Screenshots documenting the setup can be added below.

### 1. VirtualBox Configuration

![VirtualBox Configuration](screenshots/virtualbox-setup.png)

### 2. Kali Linux Desktop

![Kali Linux Desktop](screenshots/kali-desktop.png)

### 3. Network Configuration

![Network Configuration](screenshots/network-configuration.png)

### 4. Connectivity Verification

![Connectivity Test](screenshots/connectivity-test.png)

*Replace these example image paths with your uploaded screenshots. If you have not captured them yet, remove these image entries until the files are available.*

## 💡 Key Learnings

Through this project, I gained practical experience with:

- Virtualization and virtual machine management.
- Setting up a Linux-based cybersecurity environment.
- Understanding virtual network adapters and connectivity.
- Inspecting IP addresses, routing, and DNS configuration.
- Using terminal commands to troubleshoot basic network issues.
- Documenting technical work using GitHub and Markdown.

The setup also helped me understand how a controlled lab environment supports safer, repeatable cybersecurity practice.

## 🔒 Security & Ethical Considerations

This lab is intended for educational purposes and authorized security testing only.

- Test only systems you own or have explicit permission to assess.
- Use isolated lab environments for practical security exercises.
- Avoid exposing vulnerable lab machines to untrusted networks.
- Keep the host operating system and virtual machine software updated.
- Create virtual machine snapshots before significant changes or experiments.

## 🔗 Resources

- [Kali Linux Official Website](https://www.kali.org/)
- [VirtualBox Official Website](https://www.virtualbox.org/)
- [Kali Linux Documentation](https://www.kali.org/docs/)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

## 👩‍💻 Author

**Favour**

Aspiring Cybersecurity Professional | Cybersecurity Learner

Currently building practical skills in cybersecurity, networking, Linux, and security analysis.

---

*This project is part of my ongoing cybersecurity learning journey. More hands-on labs and practical projects will be added as I continue to develop my skills.*



