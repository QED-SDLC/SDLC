---
index: true
---

## Build & Integrate
The Build & Integrate phase is where the solution is developed, configured, and assembled into a working system. It transforms approved designs and requirements into functional software components, while ensuring consistency, quality, and alignment with organisational standards.

This phase emphasises disciplined engineering practices, continuous integration, and early validation to reduce risk and ensure that the solution remains maintainable, secure, and scalable.

---

### Objectives
The objectives of Build & Integrate are to:

* Develop software components that meet defined requirements and design specifications
* Ensure consistent **code quality, security, and maintainability**
* Integrate components into a cohesive and functioning system
* Detect and resolve defects early through **continuous integration and testing**
* Maintain alignment with architectural and design decisions
* Produce reliable and deployable build artefacts

---

### Key Activities
#### Development and Configuration
* Develop application code, configurations, and infrastructure components
* Follow approved design specifications and architectural patterns
* Apply secure coding standards and best practices
* Ensure consistency across environments (e.g., dev, test)

---

#### Version Control and Branching Strategy
* All code and configuration must be stored in approved version control systems
* Use a defined branching strategy appropriate to the delivery model (e.g., trunk-based, GitFlow)
* Maintain clear version history and traceability of changes
* Ensure code is regularly committed and integrated

---

#### Continuous Integration (CI)
* Automatically build and integrate code changes frequently
* Run automated tests as part of the integration process
* Detect integration issues early and resolve them promptly
* Maintain a consistently buildable codebase

---

#### Code Quality and Peer Review
* Conduct peer reviews or pull request reviews for all significant changes
* Ensure adherence to coding standards and design principles
* Identify defects, security issues, and improvement opportunities early
* Use static code analysis tools where available

---

#### Integration of Components and Services
* Integrate internal modules, external services, and third-party components
* Validate interface contracts and data exchanges
* Address integration errors, latency, and failure handling
* Ensure compatibility across system components

---

#### Test Integration (Shift Left Testing)
* Develop and execute unit and integration tests alongside code
* Automate testing wherever feasible
* Ensure tests are maintained as part of the codebase
* Validate functionality continuously, not just at later stages

---

#### Environment and Configuration Management
* Use consistent and repeatable environment configurations
* Leverage Infrastructure as Code (IaC) where applicable
* Manage environment variables, secrets, and configurations securely
* Ensure environment parity to reduce deployment risk

---

#### Build Artefact Management
* Produce versioned, traceable build artefacts
* Store artefacts in approved repositories
* Ensure artefacts are immutable and reproducible
* Maintain linkage between artefacts, source code, and requirements

---

### Outputs and Deliverables
Outputs from this phase must be reliable, traceable, and ready for validation and deployment.

Typical outputs include:

* Source code and configuration files
* Automated test scripts (unit and integration)
* Build artefacts (e.g., binaries, containers, packages)
* CI pipeline configurations
* Updated technical documentation
* Code review and quality records

---

### Governance and Controls
The Build & Integrate phase must adhere to the following controls:

* **Version Control**: All changes must be tracked and auditable
* **Code Quality**: Code must meet defined quality and security standards
* **Traceability**: Code changes must link to requirements or backlog items
* **Automated Builds and Tests**: CI processes must be in place where feasible
* **Secure Practices**: Secrets, credentials, and sensitive data must be protected

**Control Outcome:**
The solution is **consistently built, integrated, and validated**, with high confidence in its quality and readiness for formal testing.

---

### Alignment with Design
Build activities must remain aligned with approved design decisions:

* Developers must understand and adhere to architectural patterns
* Any deviations from design must be:

  * Identified early
  * Assessed for impact
  * Reviewed and approved where necessary
* Design documentation should be updated to reflect significant changes

---

### Iterative Development (Agile and Product Models)
In iterative delivery models:

* Build and integration occur continuously within each iteration or sprint
* Features are developed in small, testable increments
* Integration happens frequently to reduce risk
* Feedback from testing and stakeholders informs ongoing development

---

### Proportionality and Risk-Based Application
The level of control and formality should be proportionate to:

* System criticality and risk
* Regulatory and compliance requirements
* Complexity of integrations
* Team size and distribution

Examples:

* High-risk systems require stricter controls, reviews, and automation
* Low-risk changes may follow lightweight but still controlled practices

---

### Anti-Patterns to Avoid
To maintain quality and delivery effectiveness, teams should avoid:

* Infrequent integration leading to “integration hell”
* Bypassing version control or making untracked changes
* Manual, error-prone build processes where automation is feasible
* Skipping code reviews or reducing them to formality
* Allowing technical debt to accumulate without visibility
* Hardcoding sensitive information (e.g., credentials, keys)

---

### Closing Statement

Strong engineering practices in Build & Integrate ensure that software is not only functional, but reliable, secure, and maintainable. This phase lays the foundation for successful testing, deployment, and long-term operation.
