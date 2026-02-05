### > ./init_cycle.sh

```mermaid
graph LR
    A[🔨 Build] -->|DevSecOps| B(⚡ Break);
    B -->|Pentest| C{🔍 Analyze};
    C -->|Logseq| D[📝 Document];
    D -->|Reflect| A;
    style A fill:#0d1117,stroke:#333,stroke-width:2px,color:#fff
    style B fill:#0d1117,stroke:#333,stroke-width:2px,color:#fff
    style C fill:#0d1117,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#0d1117,stroke:#333,stroke-width:2px,color:#fff
