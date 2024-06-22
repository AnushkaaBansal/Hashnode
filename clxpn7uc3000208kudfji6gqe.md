---
title: "Essential Linux commands for DevOps"
seoTitle: "Essential Linux commands for DevOps"
seoDescription: "A transactional blog to get you started. "
datePublished: Sat Jun 22 2024 04:51:54 GMT+0000 (Coordinated Universal Time)
cuid: clxpn7uc3000208kudfji6gqe
slug: essential-linux-commands-for-devops
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/4Mw7nkQDByk/upload/d35b1cb5dbc58bbc9dbd4f88885661b8.jpeg
tags: linux, devops, linux-basics

---

### **Why Linux?**

* Multi-User & Multi -Tasking
    
* Open Source
    
* Security
    
* Need less resources
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1719031821759/2974e64e-bcca-4a5e-bf21-0a7d4ab828ae.png align="center")
    
    ### **Linux Flavours**
    
* RHEL (Red Hat Enterprise Linux)
    
* CentOS
    
* Ubuntu
    
* Amazon Linux
    
* Fedora
    
* Linux Mint
    
* OpenSUSE
    
    ### **Architecture of Linux**
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1718775975993/a3af56c0-5036-4e3a-9a79-74af928b9971.png align="center")
    
    ### **File system hierarchy**
    
* / - This is top level directory
    
* /root - It is home directory for root user
    
* /home - It is home directory for other users
    
* /boot - It contains bootable files for Linux
    
* /etc - It contains all configuration files
    
* /usr - by default softwares are installed in this directory
    
* /bin - It contains commands used by all users
    
* /sbin - It contains commands used by only root user (root)
    
    ### **Basic Linux Commands**
    
* cat (create & append file)
    
* touch (create blank file)
    
* nano (create & edit file)
    
* vi/vim (create & edit file)
    
* ls (list) (-a, -la)
    
* cd (change directory)
    
* pwd (print working directory)
    
* mkdir (create directory, multiple)
    
* cp (copy)
    
* mv (move)
    
* mv (rename)
    
* rm (remove file)
    
* tree (see in tree structure)
    
* rm -rf(remove directory & recursive)
    
* grep (pick & print)
    
* less (see output)
    
* head (see top 10 lines)
    
* tail (see last 10 lines)
    
* sort (display in Alphabetic/Numeric order)
    
* User
    
* Group
    
* Soft Link (shortcut)
    
* Hard Link (backup)
    
* /tar (to pack)
    
* gz (to compress)
    
* yum (to install)
    
* wget (to download)
    
    ### **File and directory permissions**
    
* chmod (permissions)
    
* chown (owner)
    
* chgrp (group)
    
* hostname (to see hostname)
    
* ifconfig (to get ip address)
    
* cat /etc/*rele* (to get os version)
    
* apt get install httpd (to install package)
    
* yum update httpd (to upgrade package)
    
* yum remove httpd (to uninstall package)
    
* yum list installed (to see installed packages)
    
* service httpd status (to see status)
    
* service httpd start (to start service)
    
* service httpd reload (to restart service)
    
* service httpd restart (to restart service)
    
* chkconfig httpd on (to start service permanently)
    
* chkconfig httpd off (to stop service permanently)
    
* Redirection (redirecting output)
    
* which (to see package installed or not)
    
* sudo (to get root privileges)
    
* whoami (to see user)
    
* find -type f (to see all files in current directory)
    
* find -type d (to see all directories in current directory)
    
* find / -type f (to see all files under top level root directory)
    
* find / -type d (to see all directories under top level root directory)
    
* find / -type f -name &lt;file\_name&gt; (to search specific file under top level root directory)
    
* find / -type d -name &lt;dir\_name&gt; (to search specific dir under top level root directory)
    
    ### **Advanced**
    
    AWK
    
    The awk command's main purpose is to make information retrieval and text manipulation easy to perform in Linux. This Linux command works by scanning a set of input lines in order and searches for lines matching the patterns specified by the user.
    
    ```plaintext
    $ awk '{print NR,$0}' employee.txt
    ```
    
    ```plaintext
    1 ajay manager account 45000
    2 sunil clerk account 25000
    3 varun manager sales 50000
    4 amit manager account 47000
    5 tarun peon sales 15000
    6 deepak clerk sales 23000
    7 sunil peon sales 13000
    8 satvik director purchase 80000
    ```
    
    ### **The below resource can be referred to-**
    
* %[https://github.com/milanm/DevOps-Roadmap]