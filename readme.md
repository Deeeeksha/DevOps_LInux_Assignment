

### Question/Answer

### Ques.1 What is a GNU Project? 
Ans.1 The GNU project is a massive collaborative initiative for  free software development. The original goal of the project was to create a free operating system and, if possible,everything that is
normally useful  with a Unix system, so that we can do without any non-free software. 

### Ques.2 What is the difference between Unix and Linux? 
Ans.2 Linux is an open source multitasking and multi-user operating system. Unix is ​​a multitasking and multiuser operating system but is not free to use and is not open source. 
Linux uses KDE and Gnome. Other  supported GUIs are LXDE, Xfce, Unity, Mate. Unix was initially a command-based operating system. Most Unix distributions now have Gnome.

### Ques.3 What do you mean by BIOS integrity check? Name firmwares other than BIOS 
Ans.3 The first step in the Linux boot process is the BIOS which performs system integrity checks. So once the BIOS boots up the hard drive, it looks for the boot block to know how to boot  the system.
Depending on how you partition your drive, it will resemble the master boot record (MBR) or GPT.UEFI is essentially a small operating system that runs on  the PC's firmware, and it can do a lot more 
than a BIOS. It can be stored in the motherboard's flash memory, or it can be loaded from a hard drive or network share at startup. Different PCs with UEFI  have different interfaces and functions.  

### Ques.4 What is  UEFI? 
Ans. UEFI stands for "Unified Extensible Firmware Interface". The UEFI specification defines a new model for the interface between PC operating systems and platform firmware. UEFI was developed to 
enable support for new technologies during the boot process before the operating system loads. UEFI defines a new method by which operating systems and platform firmware communicate, providing a
lightweight BIOS alternative that uses only the information necessary to initiate the operating system boot process. 

### Ques.5 What is the difference between BIOS and UEFI? 
Ans.5 The main difference between UEFI and legacy boot is that  UEFI is the final method of booting a computer  designed to replace the BIOS while  legacy boot is the process of booting the computer
using the BIOS firmware . 
BIOS stands for Basic Input/Output System, which is the firmware we talked about in the  boot sequence above. 
It is stored on an EPROM (Erasable Programmable ReadOnly Memory), which allows the manufacturer to easily distribute updates. UEFI stands for Unified Extensible Firmware Interface. It does the same 
job as a BIOS, but with one fundamental difference: it stores all  initialization and boot data in an .efi file, rather than storing it on  firmware. 

### Ques.6 When should you go for Ubuntu and when for other systems? 
Ans.6 Compared to Windows, Ubuntu offers a better option for privacy and security. The best advantage of  Ubuntu is that we can get the required privacy and extra security without  any 
third-party solutions. The risk of hacking and various other attacks can be minimized by using this distribution. 

### Ques.7 List the different Linux distributions and their usage scenarios. 
Ans.7 THe various LInux Distribution and their usage are as follows:
 1. Debian: Debian is known as the mother of popular Linux distributions such as Deepin, Ubuntu and Mint which have provided solid performance, stability and unparalleled user experience. 
 2. Gentoo: Gentoo is a distro designed for professional  and expert use, taking into account the packages they work with from the start. This category includes developers, system and network
administrators. 
 3. Ubuntu: Created and maintained by Canonical, Ubuntu is one of the most popular Linux distributions loved by beginners, intermediate users and professionals all over the world. Ubuntu is specially
designed for Linux beginners  or those moving from Mac and Windows. 
 4. Kali Linux: Developed and maintained by Offensive Security, Kali Linux is a Debian-based Linux distribution designed for penetration testing and conducting digital research. 
 5. Linux Mint: Linux Mint is an extremely popular community Linux distribution based on Ubuntu. It has surpassed its time to deliver one of the most stylish, easy-to-use distributions popular with
desktop and professional users. 

### Ques.8 What does a systemd.unit (5) mean? 
Ans.8 unit (5) for general options for all unit configuration files. General configuration items are configured in the generic sections [Unit] and [Install]. The service-specific configuration options
are configured in the [Service] section. Additional options are listed in systemd. 
 
### Ques.9 What are the getty  and uname commands? 
Ans.9  The getty command defines and manages terminal lines and ports. The getty command is executed by the init command. The getty command is associated with the Terminal State Manager program.
The Terminal State Manager program provides combined terminal control and connection functions. The Uname command is used to display basic  operating system and hardware information. 

### Ques.10 What is the squashfs file system? 
Ans.10  This is a read-only file system that allows you to compress entire file systems or single directories, write them to other devices/partitions or regular files, and then write them down. 
using a loopback device (if it is a file). The modular and compact  design of the SquashFS system is a bliss. For archiving purposes, SquashFS gives you much more flexibility and performance speed than
a tarball archive. 
 SquashFS is distributed as a Linux kernel source patch (which provides support for reading SquashFS into your kernel), the mksquashfs tool, which creates compressed file systems (in a file or on a block device), and the unsquashfs tool, which creates multiple files extracts from an existing overwritten file system.

### Ques.11 What are /dev/loop and /dev/tty ?
Ans.In Unix and Linux-like operating systems, files are accessible as block files using loop devices. These devices have no concern with RAM occupation in the system. The dev loop is also termed as vnode disk (vnd) and loopback file interface (lofi).

The “/dev/loop” devices treat files with a filesystem image as if they were block devices.They have nothing to do with RAM occupation. The loop devices are snaps because snap packages are created that way.
These files contained a filesystem that was mounted to the location. It is an approach that developers use to pack an entire package in a single file, but the operating system accesses all the files. The approach used here is therefore known as loop mounts.
/dev/tty stands for the controlling terminal (if any) for the current process (the process that uses "/dev/tty" in a command). To find out which tty's are attached to which processes use the "ps -a" command at the shell prompt (command line)
/dev/tty is a special file, representing the terminal for the current process. So, when you echo 1 > /dev/tty , your message ('1') will appear on your screen. Likewise, when you cat /dev/tty , your subsequent input gets duplicated (until you press Ctrl-C).


### Ques.12 What are Linux Signals?
Ans. A signal is an event generated by the UNIX and Linux systems in response to some condition. Upon receipt of a signal, a process may take action.
A signal is just like an interrupt; when it is generated at the user level, a call is made to the kernel of the OS, which then acts accordingly.
There are two types of signals:
    • Maskable: signals which can be changed or ignored by the user (e.g., Ctrl+C).
    • Non-Maskable: signals which cannot be changed or ignored by the user. These typically occur when the user is signaled for non-recoverable hardware errors.


### Ques.13 What is the purpose of creating and using hidden files?

Ans. Hidden files are usually system or application files, concealed to prevent accidental changes. This guide will show you how to display and work with hidden files in Linux. Note: Some directories require administrator, root, or sudo privileges to access.

### Ques.14 How cxt4 is faster/better?
Ans.Ext4 is also said to be slightly faster in sequential reads and writes.When it comes to file checking, EXT4 is quicker because unallocated blocks of data are marked as such and are simply skipped during disk check operations.

### Ques.15 What is swap & swap memory ?
Ans.Swap is a space on a disk that is used when the amount of physical RAM memory is full. When a Linux system runs out of RAM, inactive pages are moved from the RAM to the swap space

Memory swapping is a computer technology that enables an operating system to provide more memory to a running application or process than is available in physical random access memory (RAM).

### Ques.16 How to mount a file system ?
And. To mount a file system in a given location (mount point), use the mount command in the following form:

mount [OPTION...] DEVICE_NAME DIRECTORY

Once the file system is attached, the mount point becomes the root directory of the mounted file system.
Usually when mounting a device with a common file system such as ext4 or xfs the mount command will auto-detect the file system type. However, some file systems are not recognized and need to be explicitly specified.
Use the -t option to specify the file system type:
mount -t TYPE DEVICE_NAME DIRECTORY

 use the -o option:
mount -o OPTIONS DEVICE_NAME DIRECTORY

Multiple options can be provided as a comma-separated list (do not insert a space after a comma).
You can get a list of all mount options by typing man mount in your terminal.


### Ques.17 Mention a ZFS use case.
Ans. ZFS was created at Sun Microsystems and open-sourced as part of OpenSolaris. It has since been ported to other OSes, including FreeBSD, Linux, and Mac OSX. If you want to know more about the origins of ZFS, ask Jeff Bonwick. ZFS is typically used on large storage servers and works well there.

 ZFS is an advanced file system, it has features as follows
    • Pooled storage
    • Copy-on-write
    • Snapshots
    • Data integrity verification and automatic repair
    • RAID-Z
    • Maximum 16 Exabyte file size
    • Maximum 256 Quadrillion Zettabytes storage

### Ques.18 How to check the port number of a process?
Ans. The Netstat.exe command has a switch that can display the process identifier (PID) that is associated with each connection to identify port conflicts. This information can be used to determine which process (program) listens on a given port.
Using Netstat command:
    1. Open a terminal
    2. Type in the command: sudo netstat -ano -p tcp
    3. You'll get an output similar to this one
    4. Look-out for the TCP port in the Local Address list and note the corresponding PID number

### Ques.19 What is unix time sharing(UTS)?
Ans. UTS (UNIX Time-Sharing) namespaces allow a single system to appear to have different host and domain names to different processes. When a process creates a new UTS namespace the hostname and domain of the new UTS namespace are copied from the corresponding values in the caller's UTS namespace

### Ques.20 What are control groups ?
Ans.Cgroups are special mechanisms provided by the Linux kernel which allows us to allocate a kind of resources like processor time, number of processes per group, amount of memory per control group or combination of such resources for a process or set of processes. Cgroups are organized hierarchically and here this mechanism is similar to usual processes as they are hierarchical too and child cgroups inherit a set of certain parameters from their parents. But actually they are not the same. 
The main differences between cgroups and normal processes are that many different hierarchies of control groups may exist simultaneously at one time while the normal process tree is always single.

### Ques.21 What is the difference between sbin & usr/sbin?
Ans.sbin:this directory holds commands needed to boot the system, but which are usually not executed by normal users.

usr/sbin:This directory contains program binaries for system administration which are not essential for the boot process, for mounting /usr, or for system.


### Ques.22 Examples of awk, grep and sed
Ans.
Grep Example:
Example data file boot book booze machine boots bungie bark 
The simplest possible example of grep is simply:
 grep "boo" a_file In this example, 
grep would loop through every line of the file "a_file" and print out every line that contains the word 'boo': boot book booze boots 

Awk Example:
AWK can operate on any file, including std-in, in which case it is often used with the '|' command, for example, in combination with grep or other commands. For example, if I list all the files in a directory like this
: [mijp1@monty RandomNumbers]$ ls -l total 2648
 -rw------- 1 mijp1 mijp1 12817 Oct 22 00:13 normal_rand.agr
 -rw------- 1 mijp1 mijp1 6948 Oct 22 00:17 random_numbers.f90

Sed example:
You can embed your sed commands into the command-line that invokes sed using the '-e' option, or put them in a separate file e.g. 'sed.in' and invoke sed using the '-f sed.in' option. This latter option is most used if the sed commands are complex and involve lots of regexps! For instance: sed -e 's/input/output/' my_file will echo every line from my_file to standard output, changing the first occurrence of 'input' on each line into 'output'. NB sed is line-oriented, so if you wish to change every occurrence on each line, then you need to make it a 'greedy' search & replace like so: sed -e 's/input/output/g' my_file

### Ques.23 How many tables are there in iptables?
Ans. iptables contains five tables:
    1. raw is used only for configuring packets so that they are exempt from connection tracking.
    2. filter is the default table, and is where all the actions typically associated with a firewall take place.
    3. nat is used for network address translation (e.g. port forwarding).
    4. mangle is used for specialized packet alterations.
    5. security is used for Mandatory Access Control networking rules (e.g. SELinux


### Ques.24 What is prot, opt, in, out, source & destination ?
Ans.
prot:prot is a combination of the following access flags: PROT_NONE or a bitwise-or of the other values in the following list: PROT_NONE The memory cannot be accessed at all. PROT_READ The memory can be read. PROT_WRITE The memory can be modified. PROT_EXEC The memory can be executed.

Opt: It means reserved for the installation of add-on application software packages. In this context, “add-on”  means software that is not part of the system; for example, any external or third-party software.

In: packets coming from the network and going to your server.

Out: An OUT file is a compiled executable file created by various source code compilers in Unix-like operating systems, such as Linux and AIX. It may store executable code, shared libraries, or object code. OUT files have been largely replaced by the newer COFF (Common Object File Format) format.

Source: source is a shell built-in command which is used to read and execute the content of a file(generally set of commands), passed as an argument in the current shell script.OR Specifies which packets the command filters based on the source of the packet.

Destination: Specifies which packets the command filters based on the destination of the packet.

### Ques.25 Why are rules added to the top?
Ans.

### Ques.26 What type of rules can we add to the iptables?
Ans.
    1. Set Default Chain Policies
    2. Block a Specific ip-address. 
    3. Allow ALL Incoming SSH. 
    4. Allow Incoming SSH only from a Specific Network. 
    5. Allow Incoming HTTP and HTTPS. 
    6. Combine Multiple Rules Together using MultiPorts. 
    7. Allow Outgoing SSH.
    8.  Allow Outgoing SSH only to a Specific Network
    9. Allow Outgoing HTTPS
    10.  Load Balance Incoming Web Traffic
    11. Allow Ping from Outside to Inside
    12.  Allow Ping from Inside to Outside
    13. Allow Loopback Access
    14. Allow Internal Network to External network.
    15. Delete Existing User.


### Ques.27 Can we block a website by its domain name only?
Ans.Blocking a domain name involves ordering a domain name lookup service (for most users, a function performed by their ISP) not to respond to any user request to look up the IP address associated with that name.


### Ques.28 How can we persist rules in iptables ?
Ans.Add rules to the iptables according to your requirement.
    1. Verify that all the rules are present using the command “iptables -L“. # iptables -L.
    2. Save the iptables. # service iptables save.
    3. Restart the service.
    4. Making service permanently ON using chkconfig.


### Ques.29 How can we save rules in iptables?
Ans.Saving iptables firewall rules permanently on Linux
    1. Step 1 – Open the terminal. 
    2. Step 2 – Save IPv4 and IPv6 Linux firewall rules. 
    3. Step 3 – Restore IPv4 and IPv6 Linux firewall rules.
    4. Step 4 – Installing iptables-persistent package for Debian or Ubuntu Linux.
    5. Step 5 – Install iptables-services package for RHEL/CentOS.


### Ques.30 What is the difference between ufw & iptables?

Ans. iptables provide a complete firewall solution that is both highly configurable and highly flexible.ufw aims to provide an easy to use interface for people unfamiliar with firewall concepts, while at the same time simplifies complicated iptables commands to help an administrator who knows what he or she is doing.

### Ques.31 What are public & private keys?

Ans.You keep the private key a secret and store it on the computer you use to connect to the remote system. Conceivably, you can share the public key with anyone without compromising the private key; you store it on the remote system in a . ssh/authorized_keys directory.The private key is secret, known only to the user, and should be encrypted and stored safely. The public key can be shared freely with any SSH server to which the user wishes to connect.

### Ques.32 How does ssh work ?
Ans. SSH (short for Secure Shell) is a network protocol that provides a secure way for two computers to connect remotely. SSH employs encryption to ensure that hackers cannot interpret the traffic between two connected devices.

### Ques.33 What is the difference between HTTP & HTTPS.
Ans.HTTPS is HTTP with encryption. The only difference between the two protocols is that HTTPS uses TLS (SSL) to encrypt normal HTTP requests and responses. As a result, HTTPS is far more secure than HTTP.

 ### Ques.34 What is SSL?
Ans.An SSL certificate is a digital certificate that authenticates a website's identity and enables an encrypted connection. SSL stands for Secure Sockets Layer, a security protocol that creates an encrypted link between a web server and a web browser.

### Ques.35 What is the difference between apt update & apt upgrade.
Ans. apt-get update updates the list of available packages and their versions, but it does not install or upgrade any packages. apt-get upgrade actually installs newer versions of the packages you have. After updating the lists, the package manager knows about available updates for the software you have installed.

### Ques.36 What do repositories contain in a Linux system?
Ans.A Linux repository is a storage location from which your system retrieves and installs OS updates and applications. Each repository is a collection of software hosted on a remote server and intended to be used for installing and updating software packages on Linux systems.

## Ques.37 What are the package managers used in Linux?
Ans. Application software for Linux typically comes in a package. The default package manager for Ubuntu is apt-get. Linux operating systems use a software tool known as a package manager to make sure the software is correctly installed and up-to-date.

### Quess.38 What does the number represent after the file permissions ?
Ans.The first number of the ls -l output after the permission block is the number of hard links. It is the same value as the one returned by the stat command in "Links''. This number is the hard link count of the file, when referring to a file, or the number of contained directory entries, when referring to a directory.

### Ques.39 What is the difference between apt and apt-get?
Ans.apt-get may be considered as lower-level and "back-end", and support other APT-based tools. apt is designed for end-users (human) and its output may be changed between versions. Note from apt(8): The `apt` command is meant to be pleasant for end users and does not need to be backward compatible like apt-get(8).

### Ques.40 How can 1 give access to someone to my AWS instance?
Ans.
1.    Connect to your Linux instance using SSH.

2.    Use the adduser command to add a new user account to an EC2 instance (replace new_user with the new account name). The following example creates an associated group, home directory, and an entry in the /etc/passwd file of the instance.

$ sudo adduser new_user

3.    Change the security context to the new_user account so that folders and files you create have the correct permissions:

$ sudo su - new_user

4.    Create a .ssh directory in the new_user home directory:

$ mkdir .ssh

5.    Use the chmod command to change the .ssh directory's permissions to 700. Changing the permissions restricts access so that only the new_user can read, write, or open the .ssh directory.

$ chmod 700 .ssh

6.    Use the touch command to create the authorized_keys file in the .ssh directory:

$ touch .ssh/authorized_keys

7.    Use the chmod command to change the .ssh/authorized_keys file permissions to 600. Changing the file permissions restricts read or write access to the new_user.

$ chmod 600 .ssh/authorized_keys


### Ques.41 What are daemon applications?
Ans.Daemon processes are used to provide services that can well be done in the background without any user interaction. For example a process that runs in background and observes network activity and logs any suspicious communication can be developed as a daemon process.some examples of use cases for daemon apps:

    • Web applications that are used to provision or administer users or do batch processes in a directory
    • Desktop applications (like Windows services on Windows or daemon processes on Linux) that perform batch jobs, or an operating system service that runs in the background
    • Web APIs that need to manipulate directories, not specific users


### Ques.42 What does a ".d" represent after a filename ?
Ans."d" stands for directory and such a directory is a collection of configuration files which are often fragments that are included in the main configuration file. The point is to compartmentalize configuration concerns to increase maintainability.

### Ques.43 What happens when a pem file gets deleted ?
Ans.PEM files are used to store SSL certificates and their associated private keys.This is the file you use in nginx and Apache to encrypt HTTPS without it you can’t access your instance from your system.

### Ques.44 What information is stored in the /etc/host file?
Ans. The /etc/hosts is an operating system file that translates hostnames or domain names to IP addresses. This is useful for testing website changes or the SSL setup before taking a website publicly live.

### Ques.45 What. is SCP & what does this command do ?
Ans.SCP (secure copy) is a command-line utility that allows you to securely copy files and directories between two locations. With scp , you can copy a file or directory: From your local system to a remote system.

### Ques.46 How port forwarding works ?
Ans. SSH Port forwarding is used to forward ports between a local and a remote Linux machine using SSH protocol. It is mainly used to encrypt connections to different applications. Even if that application doesn't support SSL encryption, SSH port forwarding can create a secure connection.

### Ques.47 How can we connect without IP to an AWS instance ?
Ans.Go into the EC2 dashboard, then in the NETWORK & SECURITY menu go to Elastic IPs. Click on Allocate a new address. Right click on the new IP and select Associate address. Associate it with your EC2 instance that doesn't have an elastic IP.


### Ques.48 What is an ssh agent?
Ans.ssh-agent is a program to hold private keys used for public key authentication. Through use of environment variables the agent can be located and automatically used for authentication when logging in to other machines using ssh(1).

### Ques.49 Create a unit file for any application.
Ans.A unit file is a plain text ini-style file that encodes information about a service, a socket, a device, a mount point, an automount point, a swap file or partition, a start-up target, a watched file system path
create a custom service unit file under the ‘/etc/systemd/system/’ directory because this is reserved for custom scripts. Any unit file in ‘/etc/systemd/system’ will override the corresponding file in ‘/lib/systemd/system’.

Syntax: The systemd unit file consists of three sections:

Section-1 [Unit]
Parameter 1
.
.
Parameter N

Section-2 [Service]
Parameter 1
.
.
Parameter N

Section-3 [Install]
Parameter 1


### Ques.50 What is RHEL?
Ans. Red Hat Enterprise Linux (RHEL) is a distribution of the Linux operating system developed for the business market. RHEL was formerly known as Red Hat Linux Advanced Server. RHEL is based on free, open source code.
