# System Information Recon

## Commands Used
- whoami
- uname -a
- ip a

## Results

(kali㉿kali)-[~]
└─$ whoami
kali
                                                                            
┌──(kali㉿kali)-[~]
└─$ uname -a
Linux kali 6.17.10+kali-amd64 #1 SMP PREEMPT_DYNAMIC Kali 6.17.10-1kali1 (2025-12-08) x86_64 GNU/Linux
                                                                            
┌──(kali㉿kali)-[~]
└─$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 00:0c:29:1c:c5:fc brd ff:ff:ff:ff:ff:ff
    inet 192.168.109.128/24 brd 192.168.109.255 scope global dynamic noprefixroute eth0
       valid_lft 1490sec preferred_lft 1490sec
    inet6 fe80::1525:290d:d846:c6bc/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
