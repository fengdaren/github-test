# github-test
flowchart TD
    A[评分系统] --> B[装载规范度<br/>30分]
    A --> C[空间利用率<br/>40分]
    A --> D[操作安全性<br/>30分]
    B --> E[综合评分<br/>100分]
    C --> E
    D --> E
    
    %% 样式设置
    classDef default fill:#ffffff,stroke:#000000,stroke-width:2px,color:#000000
    classDef title fill:#f0f0f0,stroke:#000000,stroke-width:3px,color:#000000,font-weight:bold
    classDef score fill:#ffffff,stroke:#000000,stroke-width:2px,color:#000000,font-weight:bold
    
    class A title
    class B,C,D score
    class E title
