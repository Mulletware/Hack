```mermaid
flowchart TD
    A[Maintain] --> B[Assimilate docs]
    B --> C[Init maintain]
    C --> D[Final Review]
    D --> E{Human Review}
    E -->|Re-run| A
    E -->|Approve| F[Process Complete]

    click B "./Assimilate_docs/index.md"
    click C "./Init_maintain/index.md"
    click D "./Final_Review/index.md"
```
