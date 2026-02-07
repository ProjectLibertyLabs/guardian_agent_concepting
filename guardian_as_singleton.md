```mermaid
flowchart TD
    Human["Human Attention"]

    G1["Guardian Agent A"]
    G2["Guardian Agent B"]
    G3["Guardian Agent C"]

    Human --> G1
    Human --> G2
    Human --> G3

    G1 -->|"Urgent!"| Human
    G2 -->|"Priority!"| Human
    G3 -->|"Act now!"| Human

    style Human fill:#fff2e6,stroke:#d86b1f,stroke-width:2px
