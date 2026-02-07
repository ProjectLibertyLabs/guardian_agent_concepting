```mermaid
flowchart TD
    Human --> Guardian["Primary Guardian (Sovereign)"]

    Guardian -->|Time-bounded| AgentA["Specialized Agent A"]
    Guardian -->|Purpose-limited| AgentB["Specialized Agent B"]
    Guardian -->|Least privilege| AgentC["Specialized Agent C"]

    AgentA --> ServiceA["Service A"]
    AgentB --> ServiceB["Service B"]
    AgentC --> ServiceC["Service C"]
