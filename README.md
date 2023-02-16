---
# OSCP Tools
---
This is a tutorial about the tools which can be used for OSCP examination.

`Installation`
```bash
sudo apt update;sudo apt full-upgrade;sudo apt install offsec-pwk
```
- [apache2](#apache)
- atftp
- axel
- burpsuite
- busybox
- cewl
- crowbar
- crunch
- curl
- cutycapt
- default-libmysqlclient-dev
- dirb
- dnsenum
- dnsrecon
- enum4linux
- exe2hexbat
- exploitdb
- firefox-esr
- freerdp2-x11
- hashcat
- hashid
- httptunnel
- hydra
- iptables
- john
- kali-linux-core
- kali-tools-windows-resources
- kerberoast
- leafpad
- masscan
- medusa
- metasploit-framework
- mimikatz
- mingw-w64
- nano
- nbtscan
- netcat
- nikto
- nmap
- onesixtyone
- openssl
- openvpn
- passing-the-hash
- powercat
- powershell-empire
- proxychains
- pure-ftpd
- python3
- rdesktop
- recon-ng
- rinetd
- seclists
- shellter
- snmp
- socat
- sqlmap
- tcpdump
- theharvester
- wce
- wget
- whois
- wine
- wireshark
- wpscan

*******
<div id='apache'/>
1. apache2



The Apache HTTP server project develops and maintains an open-source HTTP server. The Apache HTTP web server is one of the most used web server worldwide.

On Ubuntu you can install the Apache HTTP server with the following command.

1.1 `Installation`
```bash
sudo apt-get install apache2
```

1.1 `Starting Apache`
To start the Apache service, use the following command.
```bash
sudo service apache2 start
```

To make sure that it is running

```bash
sudo service apache2 status
```

