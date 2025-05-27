# ModOs

Modern Linux distributions, including Kali Linux, offer a vast range of system features that, while useful for general purposes, can be excessive or even risky in security-sensitive or educational environments. For students and security professionals, the ability to control and customize system features offers not only better performance and security but also a deeper understanding of system behavior. Inspired by this, we aim to work directly with the Kali Linux environment and modify it to support selective disabling of kernel-level features such as printf, networking, and file system access. This approach provides a practical and impactful method for producing secure and controlled execution environments.


General Goals:
•	Modify the Kali Linux kernel to support compile-time or runtime control over selected features.
•	Build different Kali variants with key functionalities (e.g., file system, networking, printf) disabled.
•	Evaluate the behavior and security implications of each customized build.
Milestones:
1.	Set up kernel compilation environment for Kali Linux.
2.	Identify and modularize key kernel functionalities.
3.	Implement compile-time flags or runtime toggles.
4.	Build and test multiple Kali variants.
5.	Demonstrate real-world use cases (e.g., secure lab environment, student practice VM).
6.	Document the process, outcomes, and lessons learned.

We will work directly on the Kali Linux kernel source, enabling selective compilation of key components. Tools and technologies to be used:
•	Operating System: Kali Linux
•	Language: C (Kernel programming)
•	Tools: GCC, Make, QEMU/VirtualBox for VM testing, Git for version control
•	Process:
1.	Set up the Kali Linux kernel build system
2.	Modify kernel modules for printf, networking, and filesystem
3.	Integrate configuration flags using Kconfig
4.	Compile and deploy custom builds in VM for testing
This approach ensures direct interaction with real-world systems while enhancing OS understanding and control.
