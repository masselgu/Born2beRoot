<div align="center">

# 🖥️ Born2beRoot

### System Administration · Linux · Security · Virtualization

**42 Network / 1337 Coding School**

*A hands-on journey into Linux system administration, server hardening, and service deployment.*

<br>

![42](https://img.shields.io/badge/School-1337-000000?style=for-the-badge)
![Shell](https://img.shields.io/badge/Scripting-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Security](https://img.shields.io/badge/Focus-System%20Security-blue?style=for-the-badge)

</div>

---

## 📖 About the Project

**Born2beRoot** is a system administration project from the 42 Network curriculum, completed at 1337 Coding School.

The objective is to create and configure a secure Linux server inside a virtual machine, following a strict set of system administration and security requirements.

Rather than relying on a preconfigured environment, this project involves understanding how a Linux system works internally, from disk partitioning and user management to network security, remote access, and automated system monitoring.

I also went beyond the mandatory requirements by implementing bonus services, including **FTP, MongoDB, and WordPress**, to explore service deployment, database management, and web hosting in a Linux environment.

This project allowed me to gain practical experience with Linux, cybersecurity fundamentals, networking, automation, and server administration.

## 🎯 Project Objectives

- Install and configure a Linux operating system in a virtual machine.
- Understand disk partitioning, filesystems, and logical volume management.
- Implement secure user and group management.
- Enforce password policies and account security.
- Configure SSH for secure remote administration.
- Set up a firewall and restrict network access.
- Apply the principle of least privilege.
- Automate system monitoring using Bash and scheduled tasks.
- Deploy additional services through the bonus implementation.
- Understand how different services operate together on a Linux server.

## ⚙️ Mandatory Part

### 1. Operating System & Virtualization

The project begins with installing a Linux server in a virtual machine and configuring the environment according to the subject's requirements.

Key concepts:
- Linux installation and system configuration.
- Virtual machine management.
- Disk partitioning and filesystem organization.
- Logical Volume Manager (LVM), where required by the chosen configuration.
- Package installation and system updates.

### 2. User & Group Management

Proper access control is essential for maintaining a secure server.

Implementation topics:
- Creating and managing user accounts.
- Configuring groups and group membership.
- Managing file ownership and permissions.
- Applying password policies.
- Configuring administrative privileges through `sudo`.
- Following the principle of least privilege.

### 3. Password Policy & Authentication

A secure server requires strong authentication and properly configured account policies.

Security topics:
- Password complexity requirements.
- Password expiration and renewal policies.
- Minimum password age and password history, where required.
- Account security and access restrictions.
- Secure administrative access.

### 4. SSH Configuration

SSH provides secure remote access to the server.

Configuration topics:
- Enabling and managing the SSH service.
- Configuring the SSH listening port according to the project requirements.
- Restricting remote access where appropriate.
- Understanding SSH authentication and secure administration.

### 5. Firewall Configuration

A firewall helps protect the server by controlling incoming network traffic.

Key concepts:
- Configuring firewall rules.
- Allowing only required network connections.
- Restricting access to exposed services.
- Managing and verifying firewall status.

### 6. Sudo & System Security

Administrative privileges must be controlled carefully.

Security measures include:
- Configuring appropriate `sudo` privileges.
- Applying restrictions to administrative commands.
- Understanding privilege escalation.
- Reviewing system logs and administrative activity.
- Reducing unnecessary access and exposure.

### 7. Automated System Monitoring

A monitoring script provides information about the current state of the server.

Depending on the implementation, the script can report:
- System architecture and kernel information.
- Number of physical processors and virtual CPUs.
- Available and used RAM.
- Disk utilization.
- CPU utilization.
- System uptime.
- Active TCP connections.
- Logged-in users.
- Network addresses and MAC addresses.
- Number of commands executed through `sudo`.

The script can be scheduled to run automatically using `cron`, providing recurring system status reports without manual intervention.

## 🚀 Bonus Part

In addition to the mandatory requirements, I extended the server with additional services to explore practical Linux service administration.

### 📂 FTP Server

An FTP service was configured to support file transfers between clients and the server.

Areas explored:
- FTP service installation and configuration.
- User access and file permissions.
- File transfer management.
- Network port configuration.
- Firewall integration and service accessibility.

**Objective:** Understand how file transfer services operate and how to manage their access within a server environment.

### 🗄️ MongoDB

MongoDB was included as a database service to explore NoSQL database administration on Linux.

Areas explored:
- Database service installation and configuration.
- Managing the database service.
- Understanding database and collection concepts.
- Database access and configuration.
- Service management and troubleshooting.

**Objective:** Gain practical experience deploying and managing a database service on a Linux server.

### 🌐 WordPress

WordPress was deployed as a content management system to explore web application hosting.

Areas explored:
- WordPress installation and configuration.
- Configuring the components required to run the application.
- Database integration, where applicable.
- Web service configuration.
- Application deployment and troubleshooting.
- Understanding how web applications depend on other server services.

**Objective:** Explore how a Linux server can host a web application and its supporting services.

### 🔧 Additional Services

Other services and configurations were also explored as part of the bonus implementation.

These extensions helped reinforce the relationship between:
- Linux system administration.
- Network configuration.
- Service management.
- Database administration.
- Web application hosting.
- Server security.

*The exact service configurations and security measures should be documented according to the implementation in the virtual machine.*

## 🛠️ Technologies & Tools

| Category | Technologies |
|---|---|
| Operating System | Linux — Debian or Rocky Linux, depending on the installation |
| Virtualization | VirtualBox or the virtualization platform used |
| Shell Scripting | Bash |
| Remote Administration | SSH |
| Firewall | UFW or firewalld, depending on the operating system |
| Privilege Management | sudo |
| Task Scheduling | cron |
| File Transfer | FTP |
| Database | MongoDB |
| Content Management | WordPress |
| Version Control | Git |
| Repository Hosting | GitHub |

## 🔐 Security Principles

Security is one of the central themes of Born2beRoot.

Throughout the project, I worked with concepts such as:

- **Least privilege:** Granting users only the permissions they need.
- **Access control:** Managing users, groups, permissions, and administrative privileges.
- **Network security:** Restricting access through firewall rules and SSH configuration.
- **Authentication:** Applying appropriate password and account policies.
- **Automation:** Scheduling recurring system monitoring.
- **Service management:** Configuring services while considering their network exposure and access requirements.

These principles provide a foundation for building and maintaining more secure Linux environments.

## 📚 Skills Acquired

### Linux System Administration
- Linux installation and configuration.
- Filesystem and partition management.
- User and group administration.
- Permissions and ownership.
- Package and service management.

### Networking & Security
- SSH configuration.
- Firewall administration.
- Authentication and password policies.
- Administrative privilege management.
- Network service configuration.

### Automation & Troubleshooting
- Bash scripting.
- Scheduled tasks with cron.
- System monitoring.
- Log inspection.
- Service diagnostics and troubleshooting.

### Service Deployment
- FTP service administration.
- MongoDB deployment and management.
- WordPress hosting.
- Understanding interactions between server components.

## 🧪 Verification & Evaluation

The project should be validated against the official Born2beRoot subject requirements.

Depending on the operating system and configuration, verification can include:
- Checking the operating system and kernel.
- Inspecting disk partitions and LVM configuration.
- Reviewing user, group, and password policies.
- Checking SSH configuration and service status.
- Verifying firewall rules.
- Confirming the monitoring script's output and scheduling.
- Testing the bonus services that were implemented.

All checks should reflect the actual configuration of the virtual machine.

## 👨‍💻 Author

**masselgu**

Student at **1337 Coding School — 42 Network**

- GitHub: [@masselgu](https://github.com/masselgu)

## 🏁 Conclusion

Born2beRoot was an opportunity to move beyond simply using Linux and begin understanding how to administer and secure a complete server environment.

By completing the mandatory requirements and extending the installation with bonus services, I developed a stronger foundation in system administration, access control, networking, automation, and service deployment.

The project also helped me understand the importance of configuring services carefully, limiting unnecessary exposure, and verifying that a server behaves as expected.

**Born2beRoot is a foundation for my continued learning in Linux, infrastructure, networking, and cybersecurity.**

---

<div align="center">

**Built with curiosity, configured with care.**

*42 Network · 1337 Coding School*

</div>
