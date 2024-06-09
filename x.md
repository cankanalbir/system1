``` mermaid
flowchart RL

subgraph 0 [أعضاء مجلس الأمناء]
BOT0([عبد الكريم لحموني])
BOT1(سعد الرفاعي)
BOT2(عبد الله دعمش)
BOT3(عضو آخر)
end

BOT0 & BOT1 & BOT2 & BOT3 -..-o BOD{مدير مجلس الإدارة <br> عبد الكريم لحموني}

style BOD stroke:black,stroke-width:2px

subgraph 1 [أعضاء مجلس الإدارة]
BOD --- scientific[ مدير الوحدة العلميّة <br> ماسة سودان ]
BOD --- projects{{مدير وحدة المشاريع <br> عبد الله دعمش }}
BOD --- logistics{{مدير الوحدة اللوجستيّة <br> سدرة عجم }}
BOD --- information{{مدير وحدة المعلومات <br> سعد الرفاعي }}
end

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style information stroke:black

subgraph 2 [مسؤولو الفرق]
scientific --> s1(مسؤولو الأندية)

projects --> p1(مسؤول منصّة مشاريع إبتكار)
projects --> p3(مسؤول منصّة تكنوفست بالعربي)
projects --> p2(مسؤولو المشاريع الأخرى)

logistics --> l1(مسؤول مكتب الأنشطة)
logistics --> l2(مسؤول المكتب الإعلامي)

information --> i1(مسؤول مكتب العلاقات)
information --> i2(مسؤول مكتب الموارد البشريّة)
end
```
























``` mermaid
flowchart RL

subgraph 0 [الأمناء]
BOT([أعضاء مجلس الأمناء])
end

BOT -..-o BOD{مدير مجلس الإدارة}
style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
style BOD stroke:black,stroke-width:2px

subgraph 1 [مجلس الإدارة]
BOD --- scientific{{مدير الوحدة العلميّة}}
BOD --- projects{{مدير وحدة المشاريع}}
BOD --- logistics{{مدير الوحدة اللوجستيّة}}
BOD --- information{{مدير وحدة المعلومات}}
end

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style information stroke:black

subgraph 2 [مسؤولو الفرق]
scientific --> s1(مسؤولوا الأندية)

projects --> p1(مسؤول منصّة مشاريع إبتكار)
projects --> p3(مسؤول منصّة تكنوفست بالعربي)
projects --> p2(مسؤولوا المشاريع الأخرى)

logistics --> l1(مسؤول مكتب الأنشطة)
logistics --> l2(مسؤول المكتب الإعلامي)

information --> i1(مسؤول مكتب العلاقات)
information --> i2(مسؤول مكتب الموارد البشريّة)
end
```




``` mermaid
timeline
aaa
bbb
ccc
ddd
```




``` mermaid
timeline
    title PetterTech YouTube channel
    asd: Creation of channel
    ddd: February <br> First video posted : June <br> Rebrand to PetterTech : October <br> First video to hit 1000 views
    xcx: August <br> Reached a total of 25 uploads : September <br> First video to hit 10k views
    ddd: October <br> Reached 1000 subscribers <br> : November <br> Eligible for YouTube partnership
```




``` mermaid
flowchart TD

subgraph 0 [الأمناء]
BOT([أعضاء مجلس الأمناء])
end

BOT -..-o BOD{مدير مجلس الإدارة}
style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
style BOD stroke:black,stroke-width:2px

subgraph 1 [مجلس الإدارة]
BOD --- scientific{{مدير الوحدة العلميّة}}
BOD --- projects{{مدير وحدة المشاريع}}
BOD --- logistics{{مدير الوحدة اللوجستيّة}}
BOD --- information{{مدير وحدة المعلومات}}
end

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style information stroke:black

subgraph 2 [مسؤولو الفرق]
logistics --> l1(مسؤول مكتب الأنشطة)
logistics --> l2(مسؤول المكتب الإعلامي)

projects --> p1(مسؤول منصّة مشاريع إبتكار)
projects --> p3(مسؤول منصّة تكنوفست بالعربي)
projects --> p2(مسؤولوا المشاريع الأخرى)

scientific --> s1(مسؤولوا الأندية)

information --> i1(مسؤول مكتب العلاقات)
information --> i2(مسؤول مكتب الموارد البشريّة)
end
```













``` mermaid
flowchart RL

subgraph 0 [الأمناء]
BOT([أعضاء مجلس الأمناء])
end

BOT -..-o BOD{مدير مجلس الإدارة}
style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
style BOD stroke:black,stroke-width:2px

subgraph 1 [مجلس الإدارة]
BOD --- scientific{{مدير الوحدة العلميّة}}
BOD --- projects{{مدير وحدة المشاريع}}
BOD --- logistics{{مدير الوحدة اللوجستيّة}}
BOD --- information{{مدير وحدة المعلومات}}
end

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style information stroke:black

subgraph 2 [مسؤولو الفرق]

subgraph 21
logistics --> l1
logistics --> l2(مسؤول المكتب الإعلامي)
end

subgraph 22
projects --> p1(مسؤول منصّة مشاريع إبتكار)
projects --> p3(مسؤول منصّة تكنوفست بالعربي)
projects --> p2(مسؤولوا المشاريع الأخرى)
end

subgraph 23
scientific --> s1(مسؤولوا الأندية)
end

subgraph 24
information --> i1(مسؤول مكتب العلاقات)
information --> i2(مسؤول مكتب الموارد البشريّة)
end

end

subgraph 211
logistics --> l1(مسؤول مكتب الأنشطة)
l1 --> XX1
end

```








``` mermaid
flowchart RL
BOT([مجلس الأمناء]) -.-o BOD{مجلس الإدارة}
style BOT stroke:black,stroke-width:3px,stroke-dasharray: 5 5
style BOD stroke:black,stroke-width:2px

BOD --- scientific{{الوحدة العلميّة}}
BOD --- projects{{وحدة المشاريع}}
BOD --- logistics{{الوحدة اللوجستيّة}}
BOD --- information{{وحدة المعلومات}}

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style information stroke:black

logistics --> l1(مكتب الأنشطة)
logistics --> l2(المكتب الإعلامي)

projects --> p1(منصّة مشاريع إبتكار)
projects --> p3(منصّة تكنوفست بالعربي)
projects --> p2(المشاريع الأخرى)

scientific --> s1(الأندية)

information --> i1(مكتب العلاقات)
information --> i2(مكتب الموارد البشريّة)
```








``` mermaid
flowchart RL

subgraph 0 [الأمناء]
BOT([أعضاء مجلس الأمناء])
end

BOT -..-o BOD{مدير مجلس الإدارة}
style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
style BOD stroke:black,stroke-width:2px

subgraph 1 [مجلس الإدارة]
BOD --- scientific{{مدير الوحدة العلميّة}}
BOD --- projects{{مدير وحدة المشاريع}}
BOD --- logistics{{مدير الوحدة اللوجستيّة}}
BOD --- information{{مدير وحدة المعلومات}}
end

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style information stroke:black

subgraph 2 [مسؤولو الفرق]
logistics --> l1(مسؤول مكتب الأنشطة)
logistics --> l2(مسؤول المكتب الإعلامي)

projects --> p1(مسؤول منصّة مشاريع إبتكار)
projects --> p3(مسؤول منصّة تكنوفست بالعربي)
projects --> p2(مسؤولوا المشاريع الأخرى)

scientific --> s1(مسؤولوا الأندية)

information --> i1(مسؤول مكتب العلاقات)
information --> i2(مسؤول مكتب الموارد البشريّة)
end
```










``` mermaid
flowchart LR

subgraph 0 [الأمناء]
BOT[أعضاء مجلس الأمناء]
end

BOT -..-> BOD{مدير مجلس الإدارة}
style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
style BOD stroke:black,stroke-width:2px

subgraph 1 [مجلس الإدارة]
BOD --> scientific>مدير الوحدة العلميّة]
BOD --> projects>مدير وحدة المشاريع]
BOD --> logistics>مدير الوحدة اللوجستيّة]
BOD --> relations>مدير مكتب العلاقات]
end

style scientific stroke:black
style projects stroke:black
style logistics stroke:black
style relations stroke:black

subgraph 2 [مسؤولو الفرق]
logistics --> l1(مسؤول مكتب الأنشطة)
logistics --> l2(مسؤول المكتب الإعلامي)

projects --> p1(مسؤول منصّة مشاريع إبتكار)
projects --> p3(مسؤول منصّة تكنوفست بالعربي)
projects --> p2(مسؤول نفق المناجم)

scientific --> s1(مسؤولوا الأندية)
end
```

































``` mermaid
flowchart LR

  subgraph 1 [الأمناء]
  BOT[مجلس الأمناء]
  end


  style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
  style BOD stroke:black,stroke-width:2px

  subgraph 2 [مجلس الإدارة]
  BOT -->BOD{رئيس مجلس الإدارة}
  BOD --> scientific(مدير الوحدة العلميّة)
  BOD --> projects(مدير وحدة المشاريع)
  BOD --> logistics(مدير الوحدة اللوجستيّة)
  BOD --> relations(مدير مكتب العلاقات)
  end

  style scientific stroke:black
  style projects stroke:black
  style logistics stroke:black
  style relations stroke:black

  subgraph 3 [مسؤولو الفرق]
  logistics --> l1(مسؤول مكتب الأنشطة)
  logistics --> l2(مسؤول المكتب الإعلامي)
  
  projects --> p1(مسؤول منصّة مشاريع إبتكار)
  projects --> p3(مسؤول منصّة تكنوفست بالعربي)
  projects --> p2(مسؤول نفق المناجم)
  
  scientific --> s1(مسؤولوا الأندية)
  end
```
























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






``` mermaid
flowchart LR

    X1 --> X2
    X1 --> A

    X2 --> X3
    X2 --> B
    X2 --> C
    X2 --> D
    X2 --> E
    X2 --> F

    X3 --> G
    X3 --> H



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



``` mermaid
flowchart LR
  X1>1] ----> X2>2]
  X2 ----> X3>3]

  X1 -.-> BOT

  X2 -.- BOD
  X2 -.- scientific & projects & logistics & relations
  
  X3 -.- l1 & l2 & p1 & p2 & p3 & s1



  subgraph 1 [الأمناء]
  BOT[مجلس الأمناء] -->BOD{مجلس الإدارة}
  style BOT fill:white,stroke:black,stroke-width:3px,stroke-dasharray: 5 5
  style BOD stroke:black,stroke-width:2px
  end

  subgraph 2 [مجلس الإدارة]
  BOD --> scientific(الوحدة العلميّة)
  BOD --> projects(وحدة المشاريع)
  BOD --> logistics(الوحدة اللوجستيّة)
  BOD --> relations(مكتب العلاقات)
  end

  style scientific stroke:black
  style projects stroke:black
  style logistics stroke:black
  style relations stroke:black

  subgraph 3 [مسؤولو المكاتب]
  logistics --> l1(مكتب الأنشطة)
  logistics --> l2(المكتب الإعلامي)
  
  projects --> p1(منصّة مشاريع إبتكار)
  projects --> p3(منصّة تكنوفست بالعربي)
  projects --> p2(نفق المناجم)
  
  scientific --> s1(الأندية)
  end
```










