```mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant User
participant WebServer
participant Firewall

Attacker->>BotNet: Commands botnet to flood the targeted webserver
BotNet->>WebServer: The botnet sends thousands of requests to Webserver
WebServer->>Firewall: The firewall
