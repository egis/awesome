[awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin)  

## Deployment
[Ansible](https://docs.ansible.com/)  


## Workstations
[awesome-osx-command-line](https://github.com/StevenBlack/awesome-osx-command-line)  
[awesome-shell](https://github.com/alebcay/awesome-shell)  
[Github dotfiles](http://dotfiles.github.io/)  
[zsh tips](http://www.rayninfo.co.uk/tips/zshtips.html)  

[fasd](https://github.com/clvv/fasd)  Command-line productivity booster, offers quick access to files and directories  
[k](https://github.com/supercrabtree/k)  ls on steroids  
 

### Windows
[Babun - a windows shell you will love!](https://babun.github.io/)  
[NirCmd - Windows command line tool](http://www.nirsoft.net/utils/nircmd.html?2)  



### Online Tools for testing/debugging

[Tailtub](https://tailtub.com) Pipe your app and server logs to TailTub  
[Teleconsole](https://www.teleconsole.com/) Share your terminal in seconds  
[ngrok](https://ngrok.com/) secure introspectable tunnels to localhost  
[now](https://zeit.co/now) realtime global deployments:  Every time you deploy a project, now will provide you with a new, unique URL  
[runnable](https://runnable.com/) For every branch, Runnable builds, tests, and runs full-stack environments including all the services, databases, and data you need to test and review end‑to‑end.  

### Online Tools for production

[Weave](https://www.weave.works/) connect, monitor and deploy containers and microservices  
[Wormhole Network](https://wormhole.network/) On-demand secure private networks - Create a secure private network for your servers, your distributed team or just your friends  
[ZeroTier](https://www.zerotier.com/index.shtml) Simple Software Defined Networking - Connect servers, containers, desktops, laptops, phones, tablets, and embedded devices with virtual networks that work everywhere

### Hosting

[awesome-aws](https://github.com/donnemartin/awesome-aws)  
[awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted)  
[scaleway](https://www.scaleway.com/) Deploy BareMetal SSD cloud servers in seconds  
[packet](https://www.packet.net/) The Promise of the Cloud Delivered on Bare Metal  
[hyper.sh](https://hyper.sh/) Effortless docker hosting  

## DevOps

[awesome SRE](https://github.com/dastergon/awesome-sre)  
[DevOps Bookmarks](http://www.devopsbookmarks.com/)  
[Google SRE Handbook](https://landing.google.com/sre/book/index.html)  
[DevOps Checklist](http://devopschecklist.com/)  
[HumanOps](http://www.humanops.com/)  
Let's focus on the human aspects of running infrastructure  

## Learning
 
[awesome-shell Guides](https://github.com/alebcay/awesome-shell#guides)   
[command line power user](http://commandlinepoweruser.com/)  
A video series for web developers on learning a modern command line workflow with ZSH, Z and related tools.  
[linuxjourney](https://linuxjourney.com/)  
[sysadmincasts](https://sysadmincasts.com/)  
[servers for hackers](https://serversforhackers.com)  
[docker cheatsheet](https://github.com/wsargent/docker-cheat-sheet)  


### Interactive Learning
[pgexercises](https://pgexercises.com/)  
[Commandline Challenge](https://cmdchallenge.com)  
[shortcutfoo](https://www.shortcutfoo.com/)  

### Networking
To capture network traffic: [justsniffer]( http://justniffer.sourceforge.net) or [tcpdump](http://www.thegeekstuff.com/2010/08/tcpdump-command-examples/)  
To check current network activity: iftop  
To check history network activity: [vnstat](http://humdi.net/vnstat/man/vnstat.html)  

### Monitoring
Alternatives to top: htop, [dstat](http://dag.wiee.rs/home-made/dstat/), [glances](https://github.com/nicolargo/glances)  
To keep restarting a process when it ends: [psy](https://github.com/substack/psy)  
[A swiss army knife of linux debugging tools](http://jvns.ca/blog/2016/09/17/strange-loop-talk/)  

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
[Brendan Gregg Portfolio](http://www.brendangregg.com/portfolio.html)
Everything you could ever want to know on linux performance monitoring and optimization.  
[Julia Evans](http://jvns.ca/)  
[Linux Performance Analysis in 60 seconds](http://techblog.netflix.com/2015/11/linux-performance-analysis-in-60s.html)  
