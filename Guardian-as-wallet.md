```mermaid
flowchart TD
    Human["Human"]

    Wallet["Guardian Agent(Digital Wallet)"]

    ID["Identity Credentials"]
    Keys["Keys & Permissions"]
    Policies["Attention & Consent Policies"]

    Human --> Wallet
    Wallet --> ID
    Wallet --> Keys
    Wallet --> Policies

    style Wallet fill:#f0fff4,stroke:#2f855a,stroke-width:2px
