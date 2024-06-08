
``` mermaid
  journey
    section الأمناء
      الأمناء: Me
    section مجلس الإدارة
      الرئيس: Me
      النواب: Me
    section الأعضاء
      Go downstairs: Me
      Sit down: Me

```



``` mermaid
flowchart LR
    A[أعضاء مجلس الأمناء] --> B[رئيس مجلس الإدارة]
    B --> C[نائب رئيس مجلس الإدارة]
    B --> D[مدير الوحدة العلمية]
    B --> E[مدير الوحدة اللوجستية]
    B --> F[مدير مكتب العلاقات]

    C --> G[مسؤولي الأندية]
    C --> H[مسؤولي المشاريع]

    G --> I[منسقي الأندية]
    H --> J[منسقي المشاريع]

    E --> K[أعضاء المكتب الإعلامي]
    E --> L[أعضاء مكتب الأنشطة]
    E --> M[أعضاء مكتب الأرشيف]
    F --> N[أعضاء مكتب العلاقات]

    style A fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style B fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style C fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style D fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style E fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style F fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style G fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style H fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style I fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style J fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style K fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style L fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style M fill:#3399FF,stroke:#000,stroke-width:1px,color:white
    style N fill:#3399FF,stroke:#000,stroke-width:1px,color:white
```


