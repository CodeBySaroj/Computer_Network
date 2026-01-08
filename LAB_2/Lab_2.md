\# Lab 2: Important Network Commands for Testing and Troubleshooting



\## Introduction



Network troubleshooting is an essential skill for any network administrator or IT professional. Network commands help identify, diagnose, and resolve network connectivity issues, check system configurations, and ensure that devices communicate correctly. In this lab, we explore important network commands and their practical usage for testing and troubleshooting network problems.



\## Objectives



\* Learn essential network commands used for testing and troubleshooting.

\* Understand how to check network connectivity, IP configuration, and network routes.

\* Identify and diagnose common network issues using command-line tools.



\## Materials Required



\* Computer with Windows/Linux/Mac OS

\* Active network connection (LAN or Wi-Fi)

\* Command Prompt (Windows) / Terminal (Linux, Mac)



\## Network Commands and Usage



\### 1. ping



\* \*\*Purpose:\*\* Test connectivity to another host on the network.

\* \*\*Syntax:\*\*



```

ping <IP address or hostname>

```



\* \*\*Use:\*\* Shows if the target is reachable and the time it takes for packets to travel.



\### 2. ipconfig / ifconfig



\* \*\*Purpose:\*\* Display your computer’s IP address, subnet mask, and gateway.

\* \*\*Syntax:\*\*



```

ipconfig (Windows) / ifconfig (Linux)

```



\* \*\*Use:\*\* Helps identify which router or hop is slowing down or dropping packets.



\### 3. tracert / traceroute



\* \*\*Purpose:\*\* Find the path that data takes to reach a destination.

\* \*\*Syntax:\*\*



```

tracert <hostname or IP>

```



\* \*\*Use:\*\* Helps identify which router or hop is slowing down or dropping packets.



\### 4. nslookup



\* \*\*Purpose:\*\* Check if a domain name correctly resolves to an IP address.

\* \*\*Syntax:\*\*



```

nslookup <domain>

```



\* \*\*Use:\*\* Useful to troubleshoot DNS issues.



\### 5. netstat



\* \*\*Purpose:\*\* See all active network connections and open ports on your computer.

\* \*\*Syntax:\*\*



```

netstat -a

```



\* \*\*Use:\*\* Monitor which applications are using network connections.



\### 6. arp



\* \*\*Purpose:\*\* Display or modify the ARP cache (which maps IPs to MAC addresses).

\* \*\*Syntax:\*\*



```

arp -a

```



\* \*\*Use:\*\* Find MAC addresses of devices on the local network or detect IP conflicts.



\### 7. route



\* \*\*Purpose:\*\* View your computer’s IP routing table and diagnose routing paths.

\* \*\*Syntax:\*\*



```

route print

```



\* \*\*Use:\*\* Check network routes and identify potential routing problems.



\### 8. telnet



\* \*\*Purpose:\*\* Test connectivity to a specific TCP port on a remote host.

\* \*\*Syntax:\*\*



```

telnet <hostname\_or\_IP> <port>

```



\* \*\*Use:\*\* Verify if services like web servers, mail servers, or SSH are reachable.



\### 9. netsh



\* \*\*Purpose:\*\* Configure, reset, or troubleshoot network interfaces and Windows Firewall.

\* \*\*Syntax:\*\*



```

netsh interface show interface

```



\* \*\*Use:\*\* View interface status, reset TCP/IP stack, or troubleshoot network configuration issues.



\### 10. getmac



\* \*\*Purpose:\*\* Display MAC addresses of all network adapters on your computer.

\* \*\*Syntax:\*\*



```

getmac

```



\* \*\*Use:\*\* Identify network interface MAC addresses for troubleshooting or inventory.



\### 11. curl



\* \*\*Purpose:\*\* Test connectivity and HTTP requests to a URL or API.

\* \*\*Syntax:\*\*



```

curl <URL>

```



\* \*\*Use:\*\* Verify website accessibility, response codes, or download content for testing.



\### 12. systeminfo



\* \*\*Purpose:\*\* View detailed system information including network adapters and host info.

\* \*\*Syntax:\*\*



```

systeminfo

```



\* \*\*Use:\*\* Check OS, network adapters, and hardware info that might affect connectivity.



\## Procedure



1\. Open CMD (Windows) or Terminal (Linux/Mac).

2\. Execute each command using a target IP or domain.

3\. Observe and record the output.

4\. Analyse the results to understand connectivity, routing, or DNS issues.



\## Results



\* All commands executed successfully.

\* `ping` confirmed connectivity, `ipconfig` showed IP settings, `tracert` traced network paths.

\* `nslookup` verified DNS resolution, `netstat` monitored active connections.



\## Conclusion



These network commands allow us to efficiently identify and resolve connectivity and configuration issues. Tools such as `ping`, `tracert`, `nslookup`, and `netstat` provide valuable insights into network performance, routing paths, and service availability. Mastery of these commands is essential for effective network troubleshooting and maintaining reliable network operations.



