---
index: true
---

## Release & Deploy
The Release & Deploy phase governs how software is packaged, approved, and delivered into production environments. It ensures that deployments are **controlled, repeatable, and low risk**, while enabling teams to deliver value efficiently and frequently.

This phase integrates development practices (e.g., CI/CD) with organisational Change and Release Management processes to ensure that delivery speed does not compromise system stability, security, or compliance.

---

### Objectives
The objectives of Release & Deploy are to:

* Deliver tested and approved software into production environments
* Ensure deployments are **predictable, repeatable, and auditable**
* Minimise risk to business operations and end users
* Enable **rapid and reliable releases** through automation
* Ensure appropriate **communication, coordination, and readiness**

---

### Key Activities
#### Release Planning
* Define release scope, objectives, and contents
* Determine release type (e.g., major, minor, patch)
* Align release timing with business and operational requirements
* Coordinate dependencies across teams and systems

---

#### Deployment Preparation
* Package build artefacts for deployment
* Validate environment readiness (infrastructure, configurations, access)
* Confirm that all entry criteria for release are met
* Prepare deployment scripts and automation pipelines

---

#### Change Approval and Scheduling
* Raise and manage change records in accordance with Change Management processes
* Classify changes (standard, normal, emergency) based on risk
* Obtain required approvals prior to deployment
* Schedule deployments to minimise business disruption

---

#### Deployment Execution
* Execute deployments using automated pipelines where possible
* Follow standardised and documented deployment procedures
* Monitor deployment progress and system behaviour in real time
* Ensure coordination between technical and business stakeholders

---

#### Validation and Verification
* Perform post-deployment checks to confirm successful release
* Validate key functionality and system health
* Monitor for defects, incidents, or performance issues
* Confirm that the system is operating as expected

---

#### Rollback and Recovery Planning
* Define rollback procedures prior to deployment
* Ensure the ability to restore previous stable versions if required
* Test rollback mechanisms where appropriate
* Establish clear decision points for rollback execution

---

#### Communication and Release Notes
* Communicate release details to stakeholders and users
* Provide clear release notes outlining:

  * New features and enhancements
  * Bug fixes
  * Known issues or limitations
* Ensure support teams are informed and prepared

---

### Outputs and Deliverables
Release & Deploy must produce clear, auditable outputs:

* Approved change records
* Deployment plans and execution logs
* Release notes and communications
* Deployment automation configurations (CI/CD pipelines)
* Post-deployment validation results
* Rollback plans and evidence (where applicable)

---

### Governance and Controls
The following controls are mandatory:

* **Change Authorisation**: All production changes must be approved
* **Traceability**: Releases must link to requirements, code, and test results
* **Segregation of Duties**: Deployment approvals must be independent where required
* **Repeatability**: Deployments must follow consistent, documented processes
* **Auditability**: All release activities must be recorded and reviewable

**Control Outcome:**
Releases are **controlled, transparent, and low risk**, with full traceability and accountability.

---

### Automation and CI/CD Enablement
Automation is a key enabler of effective release and deployment:

* Use CI/CD pipelines to automate build, test, and deployment processes

* Reduce manual intervention to minimise errors

* Implement deployment strategies such as:

  * Blue/green deployments
  * Canary releases
  * Rolling deployments

* Integrate automated quality and security checks into pipelines

**Expectation:**
Where feasible, deployments should be **automated, repeatable, and triggered through controlled pipelines**.

---

### Alignment with Change Management
Release & Deploy must align with organisational Change Management practices:

* **Standard Changes**: Pre-approved, low-risk, repeatable deployments (often automated)
* **Normal Changes**: Require formal assessment and approval
* **Emergency Changes**: Expedited process with appropriate escalation and retrospective review

This ensures that governance is maintained without unnecessarily slowing delivery.

---

### Iterative and Continuous Delivery (Agile & Product Models)
In modern delivery models:

* Releases may occur frequently (e.g., multiple times per day)
* Deployment processes are highly automated
* Change approvals may be embedded into pipelines (for standard changes)
* Smaller, incremental releases reduce risk

However:

* Governance controls must still be met
* Traceability and auditability must be maintained
* Production stability remains a priority

---

### Proportionality and Risk-Based Release
Release processes should scale based on:

* Business impact of the change
* System criticality
* Complexity and integration scope
* Regulatory requirements

Examples:

* High-risk releases may require formal release windows and approvals
* Low-risk changes may be deployed via automated pipelines under standard change models

---

### Anti-Patterns to Avoid
To ensure effective release practices, teams should avoid:

* Manual, error-prone deployment processes where automation is feasible
* Deploying without rollback plans or recovery options
* Poor communication of releases to stakeholders and support teams
* Large, infrequent releases that increase risk
* Bypassing change management controls
* Lack of post-deployment validation

---

### Closing Statement

Effective release and deployment practices ensure that software delivery is not only fast, but safe, controlled, and aligned with business and operational needs.
