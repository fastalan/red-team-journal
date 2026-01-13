# Security Assessment Report

NOTE: Replace any placeholder text wrapped in [BRACKETS].

Methodology:
This assessment follows a structured, scope-driven approach inspired by OSSTMM v3 principles, emphasizing clear coverage, evidence-based findings, and explicit exclusions.

Client: [Client / Org]
Prepared by: Alan "fastalan" Walker
Date: [YYYY-MM-DD]
Engagement type: [Attack Surface Snapshot | Access/IAM Review | Web/API Pentest | Other]
Version: v[1.0]

---

## 1) Executive Summary
Objective: [What this assessment aimed to verify]
High-level outcome: [1–3 sentences: what’s exposed / what matters]

Top priorities (Fix First):
1. [Finding #1 title] — [impact in 1 line]
2. [Finding #2 title] — [impact in 1 line]
3. [Finding #3 title] — [impact in 1 line]

Overall posture (plain language): [Example: "Externally low exposure, but identity recovery creates elevated risk."]

---

## 2) Scope

### 2.1 In Scope Targets
| Target | Type | Environment | Notes |
|---|---|---|---|
| [example.com] | [Domain/App] | [Prod/Staging] | [...] |
| [api.example.com] | [API] | [Prod/Staging] | [...] |
| [X.X.X.X] | [Host/IP] | [Prod/Staging] | [...] |

### 2.2 Constraints / Rules of Engagement (ROE)
- Authorized testing only on explicitly listed targets.
- No denial-of-service testing, no brute-force, no social engineering unless explicitly approved in writing.
- Testing window: [dates/times/timezone]
- Points of contact (incident coordination): [name/contact]

---

## 3) Method & Coverage (What was tested)

Goal: make coverage transparent and repeatable.

### 3.1 Methods Used
- Discovery: [passive/active discovery summary]
- Validation: [manual verification approach]
- Evidence collection: [screenshots, logs, requests/responses, etc.]

### 3.2 Coverage Summary
| Area / Target Part | Tested | Notes / Depth |
|---|---|---|
| External ports/services | [Yes/No] | [...] |
| Web endpoints (unauth) | [Yes/No] | [...] |
| Authenticated roles | [Yes/No] | [roles tested / not tested] |
| Access control / authorization | [Yes/No] | [...] |
| IAM policies / roles | [Yes/No] | [...] |
| Recovery/MFA flows | [Yes/No] | [...] |
| Logging/monitoring checks | [Yes/No] | [...] |

---

## 4) Controls Observed (What worked)
| Control | Where observed | Effect |
|---|---|---|
| [MFA enforced] | [SSO/Admin] | [...] |
| [WAF/rate limiting] | [Edge] | [...] |
| [Least privilege] | [Cloud roles] | [...] |

---

## 5) Findings (Prioritized)
Each finding must be reproducible and evidence-backed.

### Finding F-01 — [Title]
Severity: [Critical/High/Medium/Low/Info]
Affected: [target(s)]
Impact: [what can happen in business terms]

Evidence:
- [EV-01: screenshot/log/request]
- [EV-02: request/response reference]
- [EV-03: command output reference]

Reproduction Steps:
1. [step 1]
2. [step 2]
3. [step 3]

Remediation Guidance:
- [specific fix / config change / control]
- [hardening / monitoring recommendation]

Retest Criteria:
- [how to confirm fixed (what should fail now)]

---

### Finding F-02 — [Title]
(Repeat same structure as F-01)

---

## 6) Not Tested (Explicit Exclusions)
This section prevents false confidence.

- [Example: No authenticated testing (no credentials provided)]
- [Example: No business-logic testing across multi-step workflows]
- [Example: No source code review]
- [Example: No DoS/load testing]
- [Example: No social engineering/phishing]
- [Example: No internal network/lateral movement testing]

---

## 7) Retest / Verification Plan
Included retest scope (if applicable): [Example: up to 10 findings or 2 hours within 14 days]
What will be verified: [list]
Evidence required from client: [change notes, updated configs, policy IDs]

---

## 8) Appendix

### 8.1 Asset Inventory (Observed)
| Asset | Type | Exposure | Notes |
|---|---|---|---|
| [...] | [...] | [...] | [...] |

### 8.2 Tooling (Optional)
- [Tools used (optional), versions if needed for reproducibility]

### 8.3 Evidence Index
| Evidence ID | Type | Location | Notes |
|---|---|---|---|
| EV-01 | [Screenshot] | [link/path] | [...] |
| EV-02 | [Log] | [link/path] | [...] |
| EV-03 | [HTTP capture] | [link/path] | [...] |
