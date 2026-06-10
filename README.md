# Cyber Incident Response Plan (CIRP)

A NIST CSF-aligned incident response framework developed as the capstone deliverable for the **MassCyberCenter Cybersecurity Fellowship** (Spring 2025).

The project translates the NIST Cybersecurity Framework into an incident response plan covering severity classification, escalation procedures, team roles, communication protocols, and post-incident analysis.

## Deliverable

[`CIRP_Presentation.pdf`](./CIRP%20(1).pdf) — full presentation deck

## Contents

The plan is structured around six core components:

| Section | Purpose |
|---------|---------|
| Framework alignment | Why NIST CSF was chosen as the guiding standard |
| Incident severity & escalation levels | Four-tier severity matrix (Low → Critical) with impact × urgency scoring |
| Incident teams | Tiered team structure from L1 (SOC/CSIRT) through L4 (Legal & Compliance) |
| Communication protocol | Internal and external notification flows, with out-of-band backup |
| Responses by escalation level | L1–L4 response procedures covering containment, eradication, forensics, and crisis response |
| Post-incident analysis | Root cause, impact assessment, lessons learned, and follow-up actions |

## Framework references

- **NIST Cybersecurity Framework (CSF)** — primary alignment for risk-based incident response
- **Severity matrix model** — adapted from Invgate's impact-urgency framework
- **Incident lifecycle structure** — informed by NIST SP 800-61 (Computer Security Incident Handling Guide)

## What I would extend in a real production context

This deliverable was scoped for an academic fellowship audience. In a real organizational deployment, the plan would need to be extended with:

- Asset inventory integration to map severity classifications to specific business systems
- Regulatory mapping for the organization's specific industry (HIPAA, PCI DSS, etc.)
- Tooling-specific runbooks tied to the actual SIEM, EDR, and ticketing systems in use
- Tabletop exercise materials
- Quantitative metrics (MTTD, MTTR, containment time) tied to organizational SLAs

## About the fellowship

The MassCyberCenter Cybersecurity Fellowship is a competitive program for Massachusetts undergraduates focused on applied cybersecurity policy, framework alignment, and incident response planning. Fellows produce a capstone deliverable demonstrating mastery of a chosen security domain.
