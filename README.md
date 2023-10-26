# Task2-Update-files
Create 5 X CentOS 7 VMs.  
Call them centos1, centos2, centos3, centos4 and centos5  
 
1. Update /etc/hosts file on each VM using Ansible so that each VMs name and IP is appended into the file  
 For example, assuming 45.23.12.12 is the IP address of centos1 VM, the /etc/hosts file on centos1  
VM should have below line appended:  
45.23.12.12 centos1  
 
2. Update /etc/resolv.conf file on each VM using Ansible with below 2 lines  
nameserver 8.8.8.8  
nameserver 8.8.4.4  
 
3. Update /etc/chrony.conf file on each VM using Ansible with below NTP servers  
time1.google.com  
time2.google.com  
 
Use variables for all the above values  
