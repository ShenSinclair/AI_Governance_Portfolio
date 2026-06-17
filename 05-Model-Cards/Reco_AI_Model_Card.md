# Reco AI Platform Governance Card

## Platform Information

| Field                | Details                                                                           |
| -------------------- | --------------------------------------------------------------------------------- |
| **Platform Name**    | Reco AI                                                                           |
| **Vendor**           | Reco                                                                              |
| **Business Owner**   | Sheniell Sinclair, AI Governance Lead                                             |
| **Technical Owner**  | Jonhathan Green, AI Platform Engineering Lead                                     |
| **Platform Type**    | AI Governance and Security Platform                                               |
| **Assessment Date**  | June 2026                                                                         |
| **Version**          | 1.0                                                                               |
| **Review Frequency** | Annual or Upon Material Platform Change                                           |

---

## Platform Purpose

Reco AI is an AI governance and security platform designed to provide visibility into organizational AI usage, AI-enabled SaaS applications, AI agents, copilots, and associated enterprise data flows. The platform supports AI discovery, inventory management, governance monitoring, access governance, risk identification, and compliance readiness activities.

---

## Intended Use

The platform may be used for:

* AI discovery and inventory management
* Shadow AI identification and monitoring
* AI governance and compliance oversight
* AI risk monitoring and reporting
* Identity and access governance
* Third-party AI visibility
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

---

## Data Considerations

### Data Types Potentially Processed

* User identity information
* Account and entitlement metadata
* SaaS application metadata
* Configuration information
* Activity and audit logs
* AI application inventory data
* AI usage metadata
* Risk findings and governance records

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
* Risk acceptance decisions
* Compliance determinations
* Security investigations
* AI inventory validation
* Escalation of high-risk findings
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

### Periodic Reviews

| Activity                | Frequency                        |
| ----------------------- | -------------------------------- |
| Access Reviews          | Quarterly                        |
| AI Inventory Validation | Quarterly                        |
| Vendor Review           | Annually                         |
| Governance Review       | Annually                         |
| Risk Assessment Review  | Annually or Upon Material Change |
| Privacy Review          | As Required                      |

---

## Approval Recommendation

### Current Assessment Status

**Governance Assessment Completed**

This platform governance card documents the intended purpose, governance considerations, risks, controls, and oversight requirements associated with Reco AI.

### Approval Prerequisites

Prior to production deployment, the following activities should be completed:

* Security Review
* Privacy Review
* Vendor Risk Assessment
* Legal Review (if applicable)
* AI Risk Assessment
* Control Assessment

### Approval Status

**Pending Completion of Required Governance Reviews**

---

## Governance Notes

*Reco AI serves as a governance-enabling technology intended to improve organizational visibility into AI adoption, AI-enabled applications, AI agents, and related risks. The platform should be implemented as part of a broader AI Governance framework that includes policies, standards, controls, oversight processes, and defined accountability structures.*

*Due to the rapidly evolving nature of AI technologies, platform capabilities, regulatory requirements, and organizational use cases, this governance card should be reviewed periodically and updated when material changes occur.*



