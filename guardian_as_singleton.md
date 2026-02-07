```mermaid
flowchart TD
    Human["Human (Proof of Personhood)"]
    Guardian["Guardian Agent (Singleton)"]

    App1["Application / Service A"]
    App2["Application / Service B"]
    App3["Application / Service C"]

    Human --> Guardian

    Guardian -->|Delegates scoped access| App1
    Guardian -->|Delegates scoped access| App2
    Guardian -->|Delegates scoped access| App3

    style Guardian fill:#e6f2ff,stroke:#1f4fd8,stroke-width:2px
