---
layout: default
title: Features
nav_order: 2
has_children: true
---

# Features

```mermaid
flowchart LR
    A>Download App] -->|Subscribe| B(Create Goal)
    subgraph B1[Start a new Goal]
        direction LR
        B --> C{Which Category?}
        C --> D[Sobriety]
        C --> E[Weight Loss]
        C --> F[Learn an Instrument]
        F --> I[Create Plan]
        E --> I
        D --> I
    end
    subgraph B2[Find a Partner]
        direction LR
        G[Swipe Match]
        H[Invite Partner]
        H --> J[Share Plans]
        G --> J
    end
    subgraph B3[Build a Plan Together]
        direction LR
        K(Review Plans) -->|Collaborate| L[Save Plan]
        L -..-> M(Schedule)
        M -..-> P(Self-Practices)
        M -..-> N(Weekly Community Checkup)
        M -..-> O(Partner Practice Sessions)
        P ==> Q[Start]
        N ==> Q
        O ==> Q
    end
 ```

 ```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```