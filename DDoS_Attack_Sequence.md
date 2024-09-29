```mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant User
participant WebServer
participant Firewall

Attacker->>BotNet: Commands BotNet to flood the targeted webserver
BotNet->>WebServer: Sends thousands of requests to Webserver
WebServer->>Firewall: Alerts Firewall of the unusual amount of traffic
Firewall->>WebServer: Examines traffic and detects traffic to be malicious
Firewall->>Webserver: Blocks the Malcious IPs
Firewall->>Webserver: 
 
```

#Documentation

## Explanation to SequenceDiagram Steps

**_1._** **Attacker Remotely Instructs Botnet**: The attacker remotely instructs the botnet to flood the targeted webserver for a DDOS attack.

**_2._** ****

**_3._** ****

**_4._** ****

**_5._** ****

**_6._** ****

**_7._** ****

**_8._** ****
