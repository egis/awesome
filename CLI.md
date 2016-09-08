### Linux

[Art of the command line](https://github.com/jlevy/the-art-of-command-line)  


## Windows
[Babun - a windows shell you will love!](https://babun.github.io/)  
[NirCmd - Windows command line tool](http://www.nirsoft.net/utils/nircmd.html?2)  


## ZSH

[dotfiles](http://github.com/egis/dotfiles)  
[commandlinepoweruser](http://commandlinepoweruser.com/)  
[zsh tips](http://www.rayninfo.co.uk/tips/zshtips.html)  

## Learning

[linuxjourney](https://linuxjourney.com/)  
[sysadmincasts](https://sysadmincasts.com/)  
[servers for hackers](https://serversforhackers.com)  
[pgexercises](https://pgexercises.com/)  
[shortcutfoo](https://www.shortcutfoo.com/)  
[docker cheatsheet](https://github.com/wsargent/docker-cheat-sheet)  


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
To take a memory dump: `jmap  -dump:format=b,file=heap.bin`  

### Performance Monitoring

[www.brendangregg.com/usemethod.html](http://www.brendangregg.com/usemethod.html)  
[www.brendangregg.com/linuxperf.html](http://www.brendangregg.com/usemethod.html)  
[Linux Performance Analysis in 60 seconds)([http://techblog.netflix.com/2015/11/linux-performance-analysis-in-60s.html))
