### Linux
#### Networking
To capture network traffic: [justsniffer]( http://justniffer.sourceforge.net) or [tcpdump](http://www.thegeekstuff.com/2010/08/tcpdump-command-examples/)  
To check current network activity: iftop  
To check history network activity: [vnstat](http://humdi.net/vnstat/man/vnstat.html)  
#### Monitoring
Alternatives to top: htop, [dstat](http://dag.wiee.rs/home-made/dstat/), [glances](https://github.com/nicolargo/glances)  
To keep restarting a process when it ends: [psy](https://github.com/substack/psy)  

### Fortigate
[CLI](http://docs-legacy.fortinet.com/fgt/handbook/cli_html/index.html)

Packet Sniffing: 
```
diagnose sniffer packet any "host 191.9.110.207 or host 10.0.1.2 
diag sys session list
```
Ping: `execute ping x.x.x.x`  
System Status: `get sys perf top` or `get sys perf status`  
Kill a service: `diag sys kill 11 {pid}`  
Restart: `execute reboot`  

### Java

To list java processes: `jps`  
To take a stack trace: `jstack <pid>`  
To take a memory dump: `jmap  -dump:format=b,file=heap.binz`  
