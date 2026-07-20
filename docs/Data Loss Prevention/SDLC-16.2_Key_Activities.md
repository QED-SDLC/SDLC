---
index: true
---

#### **16.2.1 Data Classification**

* Identify sensitive data types (e.g., PII, financial, intellectual property, health data)
* Classify data according to confidentiality, sensitivity, and regulatory requirements
* Maintain a data inventory and map where data flows across systems and environments
* Identify a Data Owner or Data Steward (Section 4.2) as the accountable party for each data domain

---

#### **16.2.2 Secure Development Practices**

* Ensure developers follow secure coding standards to prevent data leaks
* Use static and dynamic analysis tools to detect data exposure risks
* Avoid storing sensitive data in unencrypted logs, source control, or test environments
* Implement masking or anonymisation for non-production environments
* Ensure encryption is applied to sensitive data at rest and in transit, in accordance with organisational standards

---

#### **16.2.3 Access Control and Permissions**

* Enforce least-privilege access to sensitive data
* Regularly review and audit access rights for development, testing, and production systems
* Use role-based access control (RBAC) or attribute-based access control (ABAC) mechanisms
* Ensure that access to production data is restricted, logged, and subject to appropriate approval

---

#### **16.2.4 Monitoring and Detection**

* Deploy DLP tooling to monitor for suspicious activity, including the unauthorised copying, transferring, or exfiltration of sensitive data
* Integrate DLP checks into CI/CD pipelines (Section 14) to detect policy violations before code is promoted to higher environments
* Track anomalous behaviour in repositories, networks, endpoints, and cloud services
* Ensure DLP alerts are routed to Security Operations for timely review and response
* Maintain audit logs of data access and handling activities to support investigations and compliance reporting

---

#### **16.2.5 Incident Response and Remediation**

* Define processes for responding to data loss events, breaches, or policy violations
* Include containment, root cause analysis, and corrective actions
* Report incidents according to regulatory and organisational requirements
* Update policies, controls, and training based on lessons learned

---

#### **16.2.6 Training and Awareness**

* Ensure developers, testers, and operational staff understand their responsibilities for handling sensitive data
* Provide targeted training on DLP policies, secure coding practices, and data handling requirements as part of onboarding and ongoing development
* Promote a culture of data responsibility — team members should feel empowered to raise concerns about data handling practices without fear

---

#### **16.2.7 Privacy and Security by Design**

DLP considerations must be embedded in Design activities (Section 6), consistent with Principle 2.2.

* Identify data flows and sensitivity requirements during solution design
* Conduct a Privacy Impact Assessment (PIA) where required
* Design data minimisation into solutions — collect and retain only what is necessary
* Ensure data retention and deletion requirements are addressed in the solution design
* Engage Security, Privacy, Enterprise Information Services & Architecture early in the design process, particularly for solutions processing sensitive or regulated data

---

