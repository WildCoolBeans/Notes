# Network
## ==Nmap==
###### Ping
```shell
nmap -sn -v -iL hosts.txt -oA ping
cat ping.gnmap | grep "Up" | cut -d " " -f 2 >> Up_Hosts.txt
```

###### TCP - Top 1000
```shell
nmap -Pn -v -sV -iL hosts.txt -oA tcp_top_1000
cat tcp_top_1000 | grep "open" | cut -d " " -f 2 >> TCP_Open_Hosts.txt
```

###### TCP - Top 1000 - Service
```shell
nmap -Pn -v -sV -sC --script-timeout=30 -iL hosts.txt -oA tcp_top_1000_detailed
cat tcp_top_1000_detailed | grep <PORT>/open | cut -d " " -f 2 >> <PORT>.txt
```

###### TCP - All Port
```shell
nmap -Pn -v -sV -p- -iL hosts.txt -oA tcp_allPort
cat tcp_allPort | grep "open" | cut -d " " -f 2 >> TCP_Open_Hosts.txt
```

###### TCP - All Port - Service
```shell
nmap -Pn -v -sV -sC -p- --script-timeout=30 -iL hosts.txt -oA tcp_allPort_detailed
cat tcp_allPort_detailed | grep <PORT>/open | cut -d " " -f 2 >> <PORT>.txt
```

###### UDP - Top 1000
```shell
nmap -Pn -v -sU -iL hosts.txt -oA udp_top_1000
cat udp_top_1000 | grep "/open/" | cut -d " " -f 2 >> UDP_Open_Hosts.txt
```

###### UDP - Top 1000 - Service
```shell
nmap -Pn -v -sU -sV -sC --script-timeout=30 -iL hosts.txt -oA udp_top_1000_detailed
cat udp_top_1000_detailed | grep "<PORT>/open/" | cut -d " " -f 2 >> <PORT>_udp.txt
```
***
## ==FTP (21)==
###### Nmap Enum
```shell
nmap –script ftp-anon,ftp-bounce,ftp-libopie,ftp-proftpd-backdoor,ftp-vsftpd-backdoor,ftp-vuln-cve2010-4221,tftp-enum -p 21 <IP>
```

###### Manual Connection
**Check for anonymous user** (User: anoymous, Password: NULL)
```shell
ftp <IP>
```
***
## ==Internal Web (80, 443)==
###### Aquatone (Screenshot)
[[Git#Aquatone|Install]]
```shell
cat <Nmap XML File> | aquatone -nmap
```

###### Eyewitness (Screenshot)
```shell
eyewitness -f <File> --web
eyewitness -f <File> --web --proxy-ip 127.0.0.1 --proxy-port 8080 --proxy-type socks5 
```

###### Nikto (Vuln Scan)
```shell
nikto -output <Out File JSON> -host <IP/URL> -id <User:Pass> -port <Port> -Tuning x,6,0 -Display V | tee nikto_raw.out
```
***
## ==NFS (2049)==
###### Show Mount (Display Accessible Shares)
```shell
showmount -e <IP>
```

###### Mount (Mount Shares)
```shell
mount -t nfs [-o vers=2] <IP>:<Folder> <Local Folder> -o nolock
```

###### Priv Esc
>https://book.hacktricks.xyz/linux-unix/privilege-escalation/nfs-no_root_squash-misconfiguration-pe
***
***
# Web
## ==Crawling==
###### Gobuster
```shell
gobuster dir --url <URL> -w <WORDLIST> | tee <gobuster_raw.out
```

