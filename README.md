``` mermaid
flowchart
    C ([ User : cardholder ]) --- 
    B ([ user : bank ]) ---
    A ([ user : seller ]) ---
    C --- bs
    A --- B
