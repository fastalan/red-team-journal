# Security Testing Engagement Charter

NOTE:
This document defines the intent, scope, and boundaries of the engagement.
It is not a findings report.
This charter may be shared with the client in full or in part.

---

## 1) Engagement Overview

Client: [Client / Org]  
Prepared by: Alan "fastalan" Walker  
Date: [YYYY-MM-DD]  
Engagement Type: [Attack Surface Snapshot | Access/IAM Review | Web/API Pentest]  
Duration / Timebox: [e.g. 1–2 days | 3–5 days | Fixed scope]  
Authorization Reference: [Contract / Email / Ticket ID]

---

## 2) Engagement Mission (Primary Charter)

**Mission Statement:**

[Plain-language description of why this testing is being performed.]

Examples:
- Identify externally observable weaknesses that could realistically support initial compromise.
- Assess whether identity, authorization, or recovery flows could enable privilege escalation or business impact.
- Provide a scoped security snapshot suitable for internal risk review or customer/vendor assurance.

This mission defines **what success looks like** for this engagement.

---

## 3) Systems and Areas of Interest

### In Scope (High-Level)
- Applications: [Web app, API, SaaS platform, etc.]
- Environments: [Production / Staging]
- Identity Components: [SSO, roles, access controls, recovery flows] (if applicable)
- External Assets: [Domains, IP ranges] (if applicable)

### Out of Scope (Explicit)
- Denial-of-service or load testing
- Social engineering or phishing
- Physical security testing
- Source code review
- Internal network testing (unless explicitly agreed)

Anything not listed as in scope is considered **out of scope**.
