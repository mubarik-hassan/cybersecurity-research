# Phishing-Resistant MFA for Privileged Accounts

## A Standards-Based Assessment of Credential Choice, Recovery, and Rollout

**Author** Mubarik Hassan  
**Affiliation** Independent Cybersecurity Researcher  
**Research category** Independent Cybersecurity Research  
**Publication date** November 25, 2026 (2026-11-25)

## Overview

This review examines how phishing-resistant authentication changes access to administrative privileges. It compares manually entered one-time codes, synced WebAuthn credentials, and device-bound credentials.

## Research question and scope

What conditions must hold for a migration to phishing-resistant MFA to change how administrative access can be obtained or retained? The scope covers enterprise administrator accounts and the management surfaces they can reach.

## Key findings

- WebAuthn provides verifier binding at sign-in. Manually entered one-time codes lack session binding.
- Credential synchronization affects key custody and recovery. NIST excludes syncable authenticators from AAL3.
- Enrollment measures adoption. Effective enforcement depends on every route that can grant or retain administrative access. The paper proposes an assessment matrix covering primary sign-in, fallback, credential recovery, emergency access, and existing sessions.

## Methodology and limitations

This targeted standards review draws on primary publications from NIST, W3C, and CISA. The assessment matrix proposes acceptance criteria for controlled testing. The paper reports no deployment observations, interoperability results, or incident statistics.

## Publication files

- [Phishing-Resistant MFA for Privileged Accounts (PDF)](phishing-resistant-mfa.pdf)
- [Phishing-Resistant MFA for Privileged Accounts (Markdown)](phishing-resistant-mfa.md)
- [Bibliography](BIBLIOGRAPHY.md)
