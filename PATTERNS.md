GovStack Service Patterns Mapping

This document maps the Maternal Digital Bridge lifecycle events to the standardized GovStack Reference Architecture.

1. Identification & Verification Pattern
Lifecycle Event: Initial clinic visit and pregnancy confirmation.
Building Block: Identification.
Implementation: Verification of the mother's Fayda (National ID) against the national registry to ensure a unique "Golden Record" for service delivery.
2. Registration & Enrollment Pattern
Lifecycle Event: Onboarding the mother into the Maternal Health Registry.
Building Block: Registration.
Implementation: Capturing clinical confirmation and linking it to the civil registry (birth notification readiness) using open standards like OpenCRVS.
3. Information Mediator (Interoperability) Pattern
Lifecycle Event: Eligibility cross-check between Ministry of Health and Ministry of Finance.
Building Block: Information Mediator.
Implementation: Secure data exchange (modeled on X-Road or OpenHIE) to trigger subsidy eligibility without manual administrative loops.
4. Payment & Disbursement Pattern
Lifecycle Event: Issuance of the digital subsidy and hardware kit.
Building Block: Payments.
Implementation: Utilizing an open payment switch (like Mojaloop) to facilitate Government-to-Person (G2P) transfers directly to the mother's Level 1 Digital Wallet.
5. Consent & Privacy (The Bauta Valve)
Lifecycle Event: All data exchange touchpoints.
Building Block: Consent.
Implementation: A privacy-preserving gatekeeper that ensures the mother maintains Data Stewardship while allowing for anonymized data licensing to fund the circular economy.
