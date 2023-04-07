# Privilege escalation

Linux privilege escalation is the process of gaining elevated privileges on a Linux system that a user is not authorized to have. This can be done by exploiting vulnerabilities or misconfigurations in the system. Here are some common methods for Linux privilege escalation:

1. Exploiting SUID executables: SUID (Set User ID) executables run with the privileges of the owner instead of the user executing the file. Attackers can identify SUID executables that have vulnerabilities and exploit them to gain elevated privileges.
2. Exploiting file permission issues: If a user has write permissions on a file that is executed by a privileged user or process, the user can modify the file and run it with elevated privileges.
3. Exploiting service vulnerabilities: Attackers can exploit vulnerabilities in system services, such as web servers or SSH, to gain access to the system with elevated privileges.
4. Exploiting kernel vulnerabilities: Attackers can exploit vulnerabilities in the Linux kernel to gain access to the system with elevated privileges.
5. Exploiting misconfigurations: Attackers can exploit misconfigurations, such as weak passwords or unsecured network services, to gain access to the system with elevated privileges.

To prevent Linux privilege escalation, it is important to follow security best practices, such as limiting user permissions, applying security patches and updates, and regularly monitoring system logs for suspicious activity. Additionally, using tools such as SELinux or AppArmor can help restrict the privileges of users and processes on the system.

GTFOBin

[https://gtfobins.github.io](https://gtfobins.github.io)
