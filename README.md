# Organizational Chart

## Board of Directors
- **CEO (Chief Executive Officer)**
  - Overall leadership and strategic direction of the company.
  
- **CTO (Chief Technology Officer)**
  - Oversees technology strategy, product development, and engineering functions.
    - **Technical Project Manager**
      - Manages technology projects, ensuring alignment with strategic goals and timely delivery.

- **COO (Chief Operating Officer)**
  - Manages day-to-day operations and ensures operational efficiency.
    - **Operations Coordinator**
      - Supports daily operations, coordinates tasks across departments, and enhances workflow efficiency.

## Executive Team

### CEO Office
- **Executive Assistant**
  - Provides administrative support to the CEO, managing schedules and communications.
  
- **Legal Advisor**
  - Offers legal guidance and ensures compliance with regulations.

### Technical Leadership
- **VP of Product Development**
  - Oversees product lifecycle from concept to launch.
    - **Product Manager (UI/UX)**
      - Manages user experience design and user research.
        - UI/UX Designer
          - Designs user interfaces for products.
        - User Research Specialist
          - Conducts research to inform design decisions.
    
    - **Product Manager (CAD)**
      - Oversees hardware design and PCB development.
        - Hardware Design Engineer
          - Designs hardware components using CAD software.
        - PCB Design Engineer
          - Develops printed circuit board layouts.

- **VP of Engineering**
  - Leads engineering teams in developing innovative solutions.
    - **Hardware Engineering Manager**
      - Oversees hardware engineering efforts.
        - Mechanical Engineer
          - Designs mechanical systems for products.
        - Electronics Engineer
          - Develops electronic components and systems.
    
    - **Software Engineering Manager**
      - Leads software development for robotic systems.
        - Systems Software Engineer
          - Develops system-level software for robotics.
        - Application Software Engineer
          - Creates application-level software for user interaction.

### Operations and Finance
- **VP of Operations and Sales**
  - Manages operational activities and sales strategies.
    - **Operations Manager**
      - Oversees manufacturing processes and supply chain management.
        - Manufacturing Supervisor
          - Manages production teams and schedules.
        - Supply Chain Coordinator
          - Coordinates logistics and inventory management.

    - **Sales and Marketing Manager**
      - Develops sales strategies and oversees marketing initiatives.
        - Sales Representatives
          - Engages customers and drives sales efforts.
        - Marketing Specialist
          - Implements marketing campaigns to promote products.

- **VP of Finance and Administration**
  - Oversees financial operations and administrative functions.
    - **Accounting Manager**
      - Manages financial reporting, budgets, and compliance.
        - Accounts Payable/Receivable Specialist
          - Handles all incoming and outgoing payments.
        - Financial Analyst
          - Analyzes financial data to support decision-making.

    - **HR Manager**
      - Manages recruitment, employee relations, and HR strategy.
        - Recruitment Specialist
          - Handles talent acquisition processes.
        - Employee Relations Specialist
          - Manages employee engagement and conflict resolution.



```mermaid
graph TD;

    A[Board of Directors] --> B[CEO]
    A --> C[CTO]
    A --> D[COO]

    B --> E[Executive Assistant]
    B --> F[Legal Advisor]

    C --> G[VP of Product Development]
    C --> H[VP of Engineering]

    G --> I[Product Manager (UI/UX)]
    G --> J[Product Manager (CAD)]

    I --> K[UI/UX Designer]
    I --> L[User Research Specialist]

    J --> M[Hardware Design Engineer]
    J --> N[PCB Design Engineer]

    H --> O[Hardware Engineering Manager]
    H --> P[Software Engineering Manager]

    O --> Q[Mechanical Engineer]
    O --> R[Electronics Engineer]

    P --> S[Systems Software Engineer]
    P --> T[Application Software Engineer]

    D --> U[VP of Operations and Sales]
    D --> V[VP of Finance and Administration]

    U --> W[Operations Coordinator]
    U --> X[Sales Representatives]
    U --> Y[Marketing Specialist]

    V --> Z[Accounting Manager]
    V --> AA[HR Manager]

    Z --> AB[Accounts Payable/Receivable Specialist]
    Z --> AC[Financial Analyst]

    AA --> AD[Recruitment Specialist]
    AA --> AE[Employee Relations Specialist]
```