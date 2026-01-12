# User and Privilege Recon

## Commands Used
- id
- groups
- sudo -l

## Results
(kali㉿kali)-[~]
└─$ id
uid=1000(kali) gid=1000(kali) groups=1000(kali),4(adm),20(dialout),24(cdrom),25(floppy),27(sudo),29(audio),30(dip),44(video),46(plugdev),100(users),101(netdev),103(scanner),107(bluetooth),120(lpadmin),129(wireshark),130(kaboxer)
                                                                       
┌──(kali㉿kali)-[~]
└─$ groups                              
kali adm dialout cdrom floppy sudo audio dip video plugdev users netdev scanner bluetooth lpadmin wireshark kaboxer
                                                                       
┌──(kali㉿kali)-[~]
└─$ sudo -l             
[sudo] password for kali: 
Matching Defaults entries for kali on kali:
    env_reset, mail_badpass,
    secure_path=/usr/local/sbin\:/usr/local/bin\:/usr/sbin\:/usr/bin\:/sbin\:/bin,
    use_pty

User kali may run the following commands on kali:
    (ALL : ALL) ALL

