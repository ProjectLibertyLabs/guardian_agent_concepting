```mermaid
flowchart TD
    PoP["Proof of Personhood(Unique Human Root)"]

    Guardian["Primary Guardian Agent"]

    Sub1["Sub-Agent: Travel"]
    Sub2["Sub-Agent: Research"]
    Sub3["Sub-Agent: Commerce"]

    Action["External Action / Transaction"]

    PoP --> Guardian
    Guardian -->|Delegates limited authority| Sub1
    Guardian -->|Delegates limited authority| Sub2
    Guardian -->|Delegates limited authority| Sub3

    Sub2 --> Action

    style PoP fill:#fff5f5,stroke:#c53030,stroke-width:2px
    style Guardian fill:#e6f2ff,stroke:#1f4fd8,stroke-width:2px
