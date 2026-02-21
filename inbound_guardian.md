```mermaid
flowchart TD

    Inbound["Inbound Query / Message / Request"]

    Guardian["Primary Personal Agent\n(Cognitive Audit Layer)"]

    Human["Human"]

    Inbound --> Guardian

    subgraph Audit["Cognitive Audit Functions"]
        Nudge["Nudge Detection Persuasive linguistics Emotional manipulation Dark patterns Coercive framing"]

        Priority["Prioritization Ranked by individual's\n  declared priorities"]

        Notes["Content Notes + Risk Summary Misleading claims Incorrect information Potential fraud signals"]
    end

    Guardian --> Nudge
    Guardian --> Priority
    Guardian --> Notes

    Guardian -->|"Filtered Content + Risk Summary"| Human

    style Guardian fill:#e6f2ff,stroke:#1f4fd8,stroke-width:2px
