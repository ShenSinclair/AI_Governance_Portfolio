# Reco AI Platform Governance Card

## Platform Information

| Field                | Details                                                                           |
| -------------------- | --------------------------------------------------------------------------------- |
| **Platform Name**    | Reco AI                                                                           |
| **Vendor**           | Reco                                                                              |
| **Business Owner**   | Sheniell Sinclair, AI Governance Lead. Information Security/ AI Governance Office                                           |
| **Technical Owner**  | Jonhathan Green, AI Security Engineering Lead                                   |
| **Platform Type**    | AI Governance and Security Platform                                               |
| **Assessment Date**  | June 2026                                                                         |
| **Version**          | 1.0                                                                               |
| **Review Frequency** | Annual or Upon Material Platform Change                                           |

---

## Platform Purpose

Reco AI is an enterprise AI governance and security platform that provides visibility into AI-enabled applications, AI agents, copilots, and SaaS integrations across the organization. The platform enables organizations to discover AI technologies, monitor AI adoption, identify governance and security risks, and support compliance and audit activities through centralized oversight and continuous monitoring.

The platform is intended for use by AI Governance, Information Security, Governance, Risk and Compliance (GRC), Privacy, Identity and Access Management (IAM), Internal Audit, and Executive Leadership teams.

---

## Intended Use

The platform may be used for:

* AI discovery and inventory management
* Monitoring AI-enabled SaaS applications and AI agents
* Shadow AI identification and monitoring
* AI governance and compliance oversight
* AI risk monitoring and reporting
* Identity and access governance
* Third-party/ Enterprise AI visibility
* Security monitoring and investigation
* Audit and compliance support
* Executive governance reporting

---

## Prohibited Use

The platform should not be used for:

* Autonomous governance decision-making without human review
* Employee performance evaluation or disciplinary actions based solely on platform outputs
* Regulatory or compliance determinations without appropriate review
* Security incident attribution without investigation and validation
* Sole-source risk acceptance decisions
* Collection or monitoring of information beyond approved organizational policies
* Processing sensitive data outside approved governance and privacy requirements
* Sharing confidential organizational information with unauthorized users or third parties
* Circumventing established AI governance or security policies

---

## Data Considerations

### Data Types Potentially Processed

* User identity and access information
* Account and entitlement metadata
* SaaS application metadata
* Configuration information
* Activity and audit logs
* AI application inventory data
* AI usage metadata
* Risk findings and governance records

### Restricted Data

The following data requires additional review or approval before use:
* Personally Identifiable Information (PII)
* Protected Health Information (PHI)
* Payment Card Industry (PCI) data
* Export-controlled information
* Regulated customer information
* Confidential intellectual property beyond approved governance activities

### Data Sensitivity Considerations

* Access permissions may expose organizational structure and privilege assignments.
* Activity metadata may be subject to privacy requirements.
* Integration configurations may reveal security architecture details.
* Inventory data may identify business-critical systems and AI usage patterns.

### Data Protection Expectations

* Encryption in transit and at rest
* Role-based access controls
* Data retention requirements
* Periodic access reviews
* Vendor data protection validation

### Governance Requirements

* Data classification must be completed before onboarding new integrations.
* Access shall follow Role-Based Access Control (RBAC) principles.
* Data retention shall align with organizational records management requirements.
* Audit logging shall be enabled for administrative and governance activities.
* Privacy and security reviews shall be completed for new data sources.

---

## Top Risks

| Risk Category           | Description                                                                            |
| ----------------------- | -------------------------------------------------------------------------------------- |
| Security Risk           | Unauthorized access resulting from misconfigured integrations or excessive permissions |
| Privacy Risk            | Collection and processing of identity or activity-related metadata                     |
| Compliance Risk         | Misalignment with regulatory, governance, or policy requirements                       |
| Third-Party Vendor Risk | Dependency on vendor security posture and operational resilience                       |
| Data Protection Risk    | Exposure of metadata, configuration data, or access information                        |
| Human Oversight Risk    | Overreliance on automated monitoring outputs without validation                        |
| Operational Risk        | Platform outages or integration failures impacting governance visibility               |
| Reputational Risk       | Governance failures impacting stakeholder confidence and trust                         |

---

## Required Controls

### Governance Controls

* AI inventory management process
* AI governance review procedures
* Risk assessment requirements
* Defined platform ownership

### Security Controls

* Least privilege access
* Multi-factor authentication
* Security monitoring and alerting
* Integration security reviews

### Privacy Controls

* Privacy Impact Assessment (PIA)
* Data minimization practices
* Data retention requirements
* Privacy compliance reviews

### Vendor Controls

* Vendor Risk Assessment
* Contract review
* Security due diligence
* Ongoing vendor monitoring

### Operational Controls

* Incident response procedures
* Change management processes
* Configuration management
* Business continuity planning

---

## Human Oversight Requirements

Human review is required for:

* Governance decisions
* Approval of new AI platform integrations
* Risk acceptance decisions
* Compliance determinations
* Investigation of security and compliance alerts
* AI inventory validation
* Approval of policy exceptions
* Escalation/ review of high-risk findings
* Executive reporting and risk communication

Platform outputs should be treated as decision-support information and should not replace human judgment, governance review, or established organizational approval processes.

---

## Monitoring Requirements

### Continuous Monitoring

* AI discovery activity
* New AI application detection
* AI agent creation and usage
* Integration changes
* Permission changes
* High-risk alerts
* Incident tracking and response
* Vendor performance monitoring
* Governance dashboard reviews
* Audit log reviews

### Periodic Reviews

| Activity                | Frequency                        |
| ----------------------- | -------------------------------- |
| Access Reviews          | Quarterly                        |
| AI Inventory Validation | Quarterly                        |
| Vendor Review           | Annually                         |
| Governance Review       | Annually                         |
| Risk Assessment Review  | Annually or Upon Material Change |
| Privacy Review          | As Required                      |
| Control Effectiveness Reviews | Annually or Upon Material Change |

---

## Approval Recommendation

### Approve with conditions

## Justification:
The Platform Assessment determined that Reco AI provides significant value by improving organizational visibility into AI technologies, supporting AI governance, strengthening identity governance, and enabling continuous monitoring of AI-enabled SaaS applications.

The Risk Assessment identified manageable security, privacy, compliance, operational, and third-party risks. While no critical risks were identified, successful deployment depends on the implementation of appropriate governance controls, security safeguards, privacy protections, and ongoing monitoring processes.

Approval is recommended contingent upon completion of the organization's required security, privacy, vendor risk, and governance reviews, as well as implementation of the required controls identified within the organization's AI Governance Framework.

**Governance Assessment Completed**

This platform governance card documents the intended purpose, governance considerations, risks, controls, and oversight requirements associated with Reco AI.

## Model Card Summary
| Category	                                   | Status  |
| -------------------------------------------- | ------  |
| Platform Purpose Defined	                   |   ✓    |
| Intended Use Documented	                     |   ✓    |
| Prohibited Use Defined	                     |   ✓    |
| Data Governance Requirements Established	   |   ✓    |
| Key Risks Identified	                       |   ✓    |
| Required Controls Defined	                   |   ✓    |
| Human Oversight Required	                   |   ✓    |
| Monitoring Requirements Established          | 	 ✓    |
| Governance Recommendation Documented	       |   ✓    |

### Governanace Lifecycle
| Lifecycle Phase | Governance Activity                                   |
| --------------- | ----------------------------------------------------- |
| Intake          | Business justification and platform registration      |
| Assessment      | Platform, risk, privacy, and vendor assessments       |
| Approval        | Governance committee review and authorization         |
| Deployment      | Controlled implementation with required controls      |
| Monitoring      | Continuous monitoring, logging, and periodic reviews  |
| Reassessment    | Annual review or upon material platform changes       |
| Retirement      | Decommission platform, revoke access, archive records |


---

## Governance Notes

*Reco AI serves as a governance-enabling technology intended to improve organizational visibility into AI adoption, AI-enabled applications, AI agents, and related risks. The platform should be implemented as part of a broader AI Governance framework that includes policies, standards, controls, oversight processes, and defined accountability structures.*

*Due to the rapidly evolving nature of AI technologies, platform capabilities, regulatory requirements, and organizational use cases, this governance card should be reviewed periodically and updated when material changes occur.*



