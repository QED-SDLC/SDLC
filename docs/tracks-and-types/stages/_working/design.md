---
index: true
---

## Design
The Design phase translates validated requirements and insights from Plan & Discover into a structured, implementable solution. It ensures that the solution is technically feasible, scalable, secure, and aligned with organisational standards before significant build effort begins.

Design is not a one-time activity—it may evolve iteratively, particularly in Agile and Product Operating Models. However, sufficient design must exist at all times to guide development and manage risk effectively.

---

### Objectives
The objectives of the Design phase are to:

* Define a **clear and implementable solution architecture**
* Translate requirements into **detailed functional and technical designs**
* Ensure alignment with **enterprise architecture, security, and data standards**
* Identify and address **design-level risks and constraints**
* Enable **efficient and consistent build and integration activities**
* Provide sufficient detail to support **testing, deployment, and operations**

---

### Key Activities
#### Solution Architecture Design
* Define high-level and detailed architecture (logical and physical views)
* Identify system components, services, and interactions
* Define deployment architecture (cloud, on-premise, hybrid)
* Ensure alignment with enterprise architecture principles and standards
* Evaluate and document architectural trade-offs

---

#### Application and Component Design
* Break down the solution into implementable components or services
* Define APIs, interfaces, and contracts between components
* Specify business logic and workflows
* Ensure modularity, reusability, and maintainability

---

#### Data Design
* Define data models, structures, and relationships
* Identify data sources, flows, and transformations
* Define data storage, retention, and lifecycle requirements
* Ensure alignment with data governance and classification policies

---

#### User Experience (UX) and Interface Design
* Design user journeys and interaction flows
* Develop wireframes, mock-ups, or UI specifications
* Ensure accessibility, usability, and consistency with design standards
* Validate designs with users where appropriate

---

#### Integration Design
* Identify integration points with internal and external systems
* Define integration patterns (e.g., APIs, messaging, batch)
* Specify data exchange formats and protocols
* Address latency, reliability, and error handling considerations

---

#### Security and Privacy Design
* Incorporate security controls into the solution design
* Define authentication, authorisation, and access controls
* Address data protection (encryption, masking, etc.)
* Conduct threat modelling and risk assessments
* Ensure compliance with regulatory and organisational requirements

---

#### Non-Functional Requirements (NFRs)
Design must address key non-functional requirements, including:

* Performance and scalability
* Availability and resilience
* Maintainability and supportability
* Observability (logging, monitoring, alerting)
* Disaster recovery and business continuity

---

#### Design Validation and Review
* Conduct design reviews with relevant stakeholders (architecture, security, operations)
* Validate that the design meets requirements and constraints
* Ensure risks and trade-offs are understood and documented
* Refine design based on feedback

---

### Outputs and Deliverables
Design outputs should be **fit-for-purpose** but must provide sufficient clarity to enable build and validation activities.

Typical outputs include:

* Solution architecture diagrams and descriptions
* Component and interface specifications
* Data models and data flow diagrams
* UX designs (wireframes, prototypes, or UI specs)
* Security design artefacts and risk assessments
* Non-functional requirements definition
* Updated backlog items or detailed functional specifications

---

### Governance and Controls
The Design phase must meet the following governance expectations:

* **Architecture Alignment**: Designs must align with enterprise standards or have approved exceptions
* **Security Assurance**: Security and privacy requirements must be demonstrably addressed
* **Traceability**: Design artefacts must link back to requirements and forward to build/test activities
* **Review and Approval**: Designs must undergo appropriate level of review based on risk and complexity
* **Risk Management**: Design risks must be identified, documented, and mitigated

**Control Outcome:**
The solution is **well-defined, feasible, and governable**, with risks understood before build begins.

---

### Iterative Design (Agile and Product Models)
In iterative delivery models:

* Design evolves continuously alongside development
* “Just enough design” is encouraged to enable progress without over-engineering
* Detailed design may occur just-in-time for upcoming work
* Ongoing refinement is expected as new information emerges

However:

* Core architectural decisions must be made early
* Technical integrity must be maintained over time
* Accumulated design decisions must remain coherent and documented

---

### Proportionality and Risk-Based Design
The level of design detail and formality should be proportionate to:

* System criticality and business impact
* Complexity of the solution
* Integration and data sensitivity
* Regulatory requirements

Examples:

* A high-risk, enterprise system requires formal architecture documentation and reviews
* A low-risk enhancement may require lightweight design captured in backlog items or diagrams

---

### Anti-Patterns to Avoid
To ensure effective design practices, teams should avoid:

* Proceeding to build without sufficient design clarity
* Over-engineering or designing beyond current needs
* Failing to consider non-functional requirements early
* Ignoring integration and operational considerations
* Treating design as a one-off activity rather than iterative
* Lack of documentation for key architectural decisions
