# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

PROGRAM:

TRACEROUTE COMMAND:

        from scapy.all import*     
        target = ["www.google.com"]     
        result, unans = traceroute(target,maxttl=32) 
        print(result,unans)


## Output


![Screenshot 2025-04-27 205100](https://github.com/user-attachments/assets/6965eac9-8fd0-4678-861a-588abc468870)





## Result
Thus Execution of Network commands Performed 


