# Reconnasiance
<details>
  <summary>Recon</summary>

* -f switch do not fragment, -l buffer size
  ```console
:~$ ping <host-ip> -f -l 1300
  ```
  
* __`tracert`__ for windows cmd
  ```console
:~$ traceroute <host-ip>
  ```
* [Path Analyzer Pro](https://www.pathanalyzer.com/download.opp/) in traceroute tools, ensure icmp and smart is selected, stop on control is selected

* Start Metasploit Console

```console
:~# msfdb init && msfconsole
:~# msfdb status
```
* Nmap Scanning entire Network

```shell
# Don’t ping=> -Pn, SYN scan=> -sS, Aggresive Scan=> -A, Normal_XML and Grepable format all at once=> -oA, Verbose=> -vv 

nmap -Pn -sS -A -oA -vv <Filename> 10.10.1.1/24
```


</details>
