```mermaid
flowchart TD

    Inbound["Inbound Query / Message / Request"]

    Guardian["Primary Personal Agent\n(Cognitive Audit Layer)"]

    Human["Human"]

    Inbound --> Guardian

    subgraph Audit["Cognitive Audit Functions"]
        Nudge["Nudge Detection\n• Persuasive linguistics\n• Emotional manipulation\n• Dark patterns\n• Coercive framing"]

        Priority["Prioritization\n• Ranked by individual's\n  declared priorities"]

        Notes["Content Notes + Risk Summary\n• Misleading claims\n• Incorrect information\n• Potential fraud signals"]
    end

    Guardian --> Nudge
    Guardian --> Priority
    Guardian --> Notes

    Guardian -->|"Filtered Content + Risk Summary"| Human

    style Guardian fill:#e6f2ff,stroke:#1f4fd8,stroke-width:2px
