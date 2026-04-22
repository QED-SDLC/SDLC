---
index: true
---

## Test & Validate
The Test & Validate phase ensures that the solution meets defined functional and non-functional requirements and is fit for purpose prior to release. It provides confidence that the system is reliable, secure, and aligned with business expectations.

Testing is not a single phase but a **continuous activity across the lifecycle**. This section defines the expectations for how validation is performed and evidenced before deployment.

---

### Objectives
The objectives of Test & Validate are to:

* Confirm that the solution meets **business and technical requirements**
* Identify and remediate **defects and issues** early
* Validate **non-functional requirements** such as performance, security, and resilience
* Ensure the solution is **fit for production use**
* Provide **evidence-based assurance** to support release decisions

---

### Key Activities
#### Test Strategy and Planning
* Define a test strategy appropriate to the solution’s risk, complexity, and delivery model
* Identify required test types, environments, tools, and responsibilities
* Establish entry and exit criteria for testing phases
* Align testing approach with overall delivery methodology

---

#### Functional Testing
* Validate that the system behaves according to defined requirements
* Execute test cases based on user stories, use cases, or specifications
* Confirm acceptance criteria are met
* Support user acceptance testing (UAT) where required

---

#### Integration and System Testing
* Validate interactions between components and external systems
* Ensure data flows and interfaces function correctly
* Identify defects arising from system integration

---

#### Non-Functional Testing (NFR Validation)
Testing must address relevant non-functional requirements, including:

* **Performance and Load**: Response times, throughput, scalability
* **Security**: Vulnerability scanning, penetration testing (as required)
* **Resilience and Availability**: Failover, recovery, and stability
* **Usability and Accessibility**: User experience and compliance standards

---

#### Test Automation
* Automate testing wherever feasible to improve consistency and speed
* Integrate automated tests into CI/CD pipelines
* Maintain automated test suites as part of the codebase
* Regularly review and update tests to ensure relevance

---

#### Defect Management
* Log, prioritise, and track defects through to resolution
* Classify defects based on severity and impact
* Ensure critical defects are resolved prior to release
* Analyse defect trends to identify systemic issues

---

#### User Acceptance Testing (UAT)
* Validate the solution with business stakeholders and end users
* Confirm the solution meets business needs and expectations
* Obtain formal or informal acceptance (depending on methodology)

---

#### Regression Testing
* Ensure that new changes do not negatively impact existing functionality
* Maintain regression test coverage appropriate to system risk
* Automate regression testing where possible

---

### Outputs and Deliverables
Testing outputs must provide clear evidence of quality and readiness.

Typical outputs include:

* Test strategy and test plans
* Test cases and automated test scripts
* Test execution results and reports
* Defect logs and resolution status
* Performance and security test results
* UAT outcomes and approvals (where required)
* Production readiness assessment

---

### Governance and Controls
The following controls must be met:

* **Traceability**: Test cases must map to requirements and acceptance criteria
* **Defined Entry/Exit Criteria**: Testing must meet agreed completion criteria
* **Defect Resolution**: Critical and high-severity defects must be addressed
* **Evidence-Based Assurance**: Test results must be documented and accessible
* **Segregation of Duties**: Where required, testing and approval must be independent from development

**Control Outcome:**
There is **objective evidence** that the solution meets requirements and is ready for release with acceptable risk.

---

### Definition of “Done” and Quality Gates
Each delivery must define a clear **Definition of Done**, which includes:

* Functional requirements met
* Automated tests executed successfully
* No outstanding critical or high defects (unless formally accepted)
* Non-functional requirements validated (as applicable)
* Documentation updated

Quality gates may be:

* Formal (e.g., test phase sign-off in Waterfall)
* Embedded (e.g., sprint acceptance in Agile)

Regardless of format, quality criteria must be **explicit and enforced**.

---

### Iterative Testing (Agile and Product Models)
In iterative models:

* Testing is continuous and integrated into development cycles
* Test cases are developed alongside requirements
* Validation occurs incrementally within each iteration
* Feedback is rapid and informs ongoing development

However:

* Test coverage must remain sufficient over time
* Regression risks must be actively managed
* Quality must not degrade due to delivery speed

---

### Proportionality and Risk-Based Testing
The depth and formality of testing should be proportionate to:

* Business criticality and user impact
* Complexity of the solution
* Security and regulatory requirements
* Integration scope

Examples:

* High-risk systems require comprehensive test coverage, including performance and security testing
* Low-risk changes may rely more heavily on automated and targeted testing

---

### Anti-Patterns to Avoid
To ensure effective validation, teams should avoid:

* Treating testing as a final phase rather than a continuous activity
* Inadequate test coverage or over-reliance on manual testing
* Releasing with unresolved critical defects without formal risk acceptance
* Lack of traceability between requirements and testing
* Skipping non-functional testing for critical systems
* Ignoring failed tests or weakening quality gates to meet deadlines

---

### Closing Statement

> Effective testing provides the confidence to release software safely and reliably. It ensures that quality is not assumed, but demonstrated through evidence.
