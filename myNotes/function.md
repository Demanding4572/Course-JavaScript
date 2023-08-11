graph TD

subgraph "Beginner"
  A[Basic Concepts]
  B[Data Types]
  C[Variables]
  D[Operators]
  E[Control Structures]
  F[Functions]
  G[Arrays]
  H[Objects]
  I[DOM Manipulation]
  J[Events]
end

subgraph "Intermediate"
  K[Closures]
  L[Scope]
  M[Prototypes]
  N[Asynchronous Programming]
  O[Promises]
  P[Ajax]
  Q[ES6+ Features]
  R[Module Systems]
  S[Transpilers (Babel)]
end

subgraph "Advanced"
  T[Design Patterns]
  U[Error Handling]
  V[Testing (Jest, Mocha)]
  W[Tooling (Webpack, ESLint)]
  X[Frameworks (React, Angular, Vue)]
  Y[State Management]
  Z[RESTful APIs]
  AA[GraphQL]
  AB[TypeScript]
end

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
G --> H
H --> I
I --> J

J --> K
K --> L
L --> M
M --> N
N --> O
O --> P
P --> Q
Q --> R
R --> S

S --> T
T --> U
U --> V
V --> W
W --> X
X --> Y
Y --> Z
Z --> AA
AA --> AB
