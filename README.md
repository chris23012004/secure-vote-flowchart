```mermaid
flowchart TD
    A[Start] --> B[User   Roles]
    B --> C[Voter]
    B --> D[Electoral Commission]

    C --> E[Connect Wallet]
    E --> F[Register]
    F --> G[Wait for Verification]
    G --> H[Vote]
    H --> I[View Results]

    D --> J[Access Admin Panel]
    J --> K[Manage Candidates]
    K --> L[Verify Voters]
    L --> M[Create Elections]
    M --> N[Control Elections]
    N --> O[Monitor Results]

    C --> P[Voting System]
    P --> Q[Real-time Results]
    P --> R[Transparent Process]

    S[Security Features] --> T[Wallet-based Authentication]
    S --> U[Anti-Double Voting]
    S --> V[Pausable Contract]
    S --> W[Input Validation]
    S --> X[Event Logging]

    Y[Deployment] --> Z[Local Development]
    Y --> AA[Testnet Deployment]
    Y --> AB[Production Deployment]

    AC[End]
