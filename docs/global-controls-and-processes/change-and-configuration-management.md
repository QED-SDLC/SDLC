---
index: true
---

## Change & Configuration Management
The Change & Configuration Management phase establishes control and oversight over all changes to software, infrastructure, and related configuration items (CIs). It ensures that changes are introduced in a **controlled, consistent, and traceable** manner while minimising risk to business operations.

This phase aligns closely with ITIL best practices but is tailored to support Waterfall, Agile, and Product Operating Models.

---

### Objectives
The objectives of Change & Configuration Management are to:

* Ensure all changes are **assessed, authorised, and traceable**
* Maintain a **complete and accurate configuration baseline** of systems and components
* Minimise the risk of unplanned outages or service disruption
* Provide **audit-ready records** for compliance and operational purposes
* Enable rapid recovery in case of incidents or failed changes

---

### Key Activities
#### Change Identification
* Identify all changes that affect systems, environments, or services
* Classify changes based on risk, complexity, and impact:

  * **Standard Changes**: Pre-approved, low-risk, repeatable
  * **Normal Changes**: Require assessment, approval, and scheduling
  * **Emergency Changes**: High-priority, expedited changes with retrospective review

---

#### Change Assessment
* Evaluate the impact, risk, and dependencies of each change
* Identify affected systems, services, and stakeholders
* Determine rollback or mitigation strategies
* Ensure compliance with security, privacy, and regulatory requirements

---

#### Change Approval and Scheduling
* Obtain formal authorisation based on change type and risk level
* Schedule changes to minimise business impact and ensure environment readiness
* Communicate planned changes to relevant teams and stakeholders
* Coordinate dependencies across multiple systems and teams

---

#### Change Implementation
* Implement changes following documented procedures
* Use automation wherever feasible to reduce manual errors
* Monitor implementation progress and system health
* Record actual changes made for auditability

---

#### Post-Implementation Review
* Validate that changes achieved the desired outcome
* Capture lessons learned and update procedures or documentation
* Review incidents, defects, or unexpected impacts caused by changes
* Close change records formally after validation

---

#### Configuration Management
* Maintain a Configuration Management Database (CMDB) or equivalent
* Track all configuration items (software, hardware, environments, documentation)
* Record relationships and dependencies between configuration items
* Ensure that CIs are updated in real-time following changes
* Support impact analysis, audits, and troubleshooting

---

### Outputs and Deliverables
Typical outputs include:

* Approved and logged change records
* Updated configuration item records and baseline documentation
* Post-implementation review reports
* Audit trails for compliance and governance
* Updated release and deployment logs

---

### Governance and Controls
Key governance requirements:

* **Change Traceability**: All changes must be linked to requirements, releases, and CIs
* **Approval**: Changes must follow defined authorisation levels based on risk
* **Segregation of Duties**: Where required, the person approving a change must be independent of the person implementing it
* **Auditability**: All change and configuration activities must be documented and reviewable
* **Rollback Readiness**: All changes must have clearly defined rollback procedures

**Control Outcome:**
Changes are **controlled, visible, and auditable**, reducing operational risk and supporting compliance.

---

### Alignment Across Delivery Models
* **Agile / Product Models**:

  * Changes may be frequent and incremental
  * Standard and automated changes are encouraged
  * Post-implementation review and traceability remain mandatory

* **Waterfall**:

  * Changes are managed through formal stage gates
  * Approvals and documentation are typically more structured
  * CMDB updates occur after each controlled release

---

### Proportionality and Risk-Based Approach
The level of control should match:

* Business impact and criticality
* Complexity of systems and integrations
* Regulatory and compliance requirements

Examples:

* Critical systems require full change assessment, approval, and rollback readiness
* Minor, low-risk updates can follow streamlined, automated processes

---

### Anti-Patterns to Avoid
To maintain effective Change & Configuration Management, teams should avoid:

* Implementing changes without formal assessment or approval
* Skipping documentation of configuration items and relationships
* Neglecting rollback or recovery plans
* Failing to communicate changes to impacted teams
* Accumulating untracked changes in production environments
