```mermaid
flowchart LR
    Attention["Human Attention (Single Spotlight)"]

    Task1["Decision"]
    Task2["Learning"]
    Task3["Judgment"]

    Attention --> Task1
    Attention -.-> Task2
    Attention -.-> Task3

    subgraph Note[" "]
      N["Attention can switch, but cannot truly split"]
    end 

    Note --- Attention
