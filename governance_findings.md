# NIST CSF 2.0 Governance Findings

## Purpose

This document summarizes the governance-related findings identified during the simulated NIST CSF 2.0 cybersecurity assessment for CloudNova Technologies.

The review focuses heavily on the **Govern** function and examines how cybersecurity responsibilities, risk ownership, policy management, third-party risk, and compliance oversight are managed.

---

## Finding 1: Cybersecurity Roles and Responsibilities

### Current State

Security responsibilities exist across IT, security, GRC, and management, but accountability is not fully documented.

### Risk

Unclear ownership may delay response, remediation, or decision-making during security incidents and compliance activities.

### Risk Level

**Medium**

### NIST CSF Function

**Govern**

### Gap

There is no formal cybersecurity responsibility matrix showing who is responsible, accountable, consulted, and informed for key security activities.

### Recommendation

Create a cybersecurity RACI matrix covering:

- Risk management
- Incident response
- Access control
- Vendor risk
- Vulnerability management
- Security monitoring
- Policy ownership
- Compliance activities

---

## Finding 2: Risk Ownership

### Current State

The organization maintains a cybersecurity risk register.

However, some High and Medium risks do not have clearly assigned owners.

### Risk

Risks may remain unresolved because no individual is accountable for treatment or acceptance.

### Risk Level

**High**

### NIST CSF Function

**Govern**

### Gap

Risk ownership is not consistently assigned.

### Recommendation

Assign a named owner to every High and Medium cybersecurity risk.

The owner should be responsible for:

- Reviewing the risk
- Selecting treatment
- Tracking remediation
- Monitoring residual risk
- Approving or escalating risk acceptance

---

## Finding 3: Risk Acceptance

### Current State

Cybersecurity risks are sometimes accepted informally.

### Risk

Management may lack visibility into accepted cybersecurity exposure.

### Risk Level

**Medium**

### NIST CSF Function

**Govern**

### Gap

There is no consistent formal risk acceptance process.

### Recommendation

Create a documented risk acceptance workflow requiring:

- Risk description
- Risk score
- Business justification
- Compensating controls
- Residual risk
- Risk owner
- Approval date
- Management approval
- Expiration or review date

---

## Finding 4: Third-Party Risk Governance

### Current State

Vendor security assessments are performed, but recurring reassessment is inconsistent.

### Risk

A vendor's security posture may deteriorate after initial approval.

### Risk Level

**High**

### NIST CSF Function

**Govern**

### Gap

High-risk vendors are not consistently reassessed.

### Recommendation

Implement a formal third-party risk management process that includes:

- Vendor risk classification
- Initial security assessment
- Annual reassessment for high-risk vendors
- Security questionnaire
- Contract security requirements
- Remediation tracking
- Risk ownership
- Approval documentation

---

## Finding 5: Cybersecurity Policy Review

### Current State

Cybersecurity policies exist.

However, evidence of annual review and approval is incomplete.

### Risk

Policies may become outdated and no longer reflect current technology, business operations, threats, or compliance obligations.

### Risk Level

**Medium**

### NIST CSF Function

**Govern**

### Gap

Policy review is not consistently documented.

### Recommendation

Establish an annual cybersecurity policy review cycle.

Each review should document:

- Policy owner
- Review date
- Changes made
- Approver
- Approval date
- Next review date

---

## Finding 6: Compliance Oversight

### Current State

Some regulatory and contractual security obligations are documented.

### Risk

Important compliance requirements may be overlooked if responsibilities are not centrally tracked.

### Risk Level

**Medium**

### NIST CSF Function

**Govern**

### Gap

The organization does not maintain a complete compliance obligations register.

### Recommendation

Create a compliance obligations register containing:

- Requirement
- Source
- Applicable business area
- Control owner
- Evidence required
- Review frequency
- Compliance status

---

## Finding 7: Access Review Governance

### Current State

Role-based access controls are implemented, but access reviews are inconsistent.

### Risk

Users may retain unnecessary or excessive access.

### Risk Level

**High**

### NIST CSF Function

**Protect**

### Gap

Access recertification is not consistently performed.

### Recommendation

Perform quarterly user access reviews.

Document:

- User
- Role
- Current permissions
- Reviewer
- Review decision
- Removed access
- Approval date

---

## Finding 8: Vulnerability Remediation Governance

### Current State

Vulnerability scanning is performed regularly.

Some vulnerabilities remain open beyond target remediation timelines.

### Risk

Known vulnerabilities may remain exploitable longer than acceptable.

### Risk Level

**High**

### NIST CSF Function

**Protect**

### Gap

Remediation timelines are not consistently enforced.

### Recommendation

Establish severity-based remediation targets:

- Critical: 7 days
- High: 30 days
- Medium: 60 days
- Low: 90 days

Exceptions should require documented risk acceptance.

---

## Finding 9: Detection Coverage Review

### Current State

Centralized logging and security detections are implemented.

### Risk

Important attack techniques may not be detected if monitoring coverage is not reviewed regularly.

### Risk Level

**Medium**

### NIST CSF Function

**Detect**

### Gap

Detection coverage is not formally reviewed on a recurring schedule.

### Recommendation

Perform quarterly detection coverage reviews.

Review:

- Critical log sources
- Detection rules
- Alert quality
- Coverage gaps
- Disabled detections
- New threat scenarios

---

## Finding 10: Incident Response Testing

### Current State

A documented incident response plan exists.

However, tabletop exercises are not performed consistently.

### Risk

Teams may respond slowly or inconsistently during a real cybersecurity incident.

### Risk Level

**High**

### NIST CSF Function

**Respond**

### Gap

Incident response procedures are not regularly validated.

### Recommendation

Conduct annual tabletop exercises and document:

- Participants
- Scenario
- Response actions
- Escalation decisions
- Communication process
- Lessons learned
- Corrective actions

---

## Finding 11: Backup Restoration Testing

### Current State

Regular backups are performed.

Restoration testing is inconsistent.

### Risk

Backups may fail when they are needed during ransomware, system failure, or disaster recovery.

### Risk Level

**Medium**

### NIST CSF Function

**Recover**

### Gap

There is insufficient evidence that backups can be restored successfully.

### Recommendation

Conduct quarterly backup restoration testing and document:

- System tested
- Backup selected
- Test date
- Recovery result
- Recovery time
- Problems identified
- Corrective actions

---

## Overall Findings Summary

| Finding | NIST CSF Function | Risk Level |
|---|---|---|
| Roles and Responsibilities | Govern | Medium |
| Risk Ownership | Govern | High |
| Risk Acceptance | Govern | Medium |
| Third-Party Risk Governance | Govern | High |
| Cybersecurity Policy Review | Govern | Medium |
| Compliance Oversight | Govern | Medium |
| Access Review Governance | Protect | High |
| Vulnerability Remediation | Protect | High |
| Detection Coverage Review | Detect | Medium |
| Incident Response Testing | Respond | High |
| Backup Restoration Testing | Recover | Medium |

---

## Conclusion

The assessment identified several governance weaknesses, particularly around ownership, vendor oversight, risk acceptance, and recurring review processes.

The highest-priority actions are to formalize risk ownership, strengthen third-party risk governance, improve access reviews, enforce vulnerability remediation timelines, and test incident response procedures.

Strengthening these areas will improve alignment with NIST CSF 2.0 and create clearer accountability across the cybersecurity program.
