  # Hobby vs. Business: Tax Decision Tree


  
```mermaid
flowchart TD
    A[Start: Business Income] --> B{Is it a Qualified Trade or Business?}

    B -->|Yes| C{Is Taxpayer Eligible for QBI Deduction?}
    B -->|No| D[No QBI Deduction]

    C -->|Yes| E[Calculate QBI Deduction]
    C -->|No| D

    E --> F[Report Deduction on Form 1040]
```
