## Supported Versions

We are committed to providing security updates for the current major and immediately preceding major version of the PLUSE platform. We strongly encourage all users to run a supported version.

| Version | Status | Supported with Security Updates |
| :--- | :--- | :--- |
| **5.1.x (LTS)** | **Current Major Release** | :white_check_mark: |
| **5.0.x** | **End-of-Life** | :x: |
| **4.0.x** | **Previous Major Release** | :white_check_mark: |
| **< 4.0** | **End-of-Life** | :x: |

---

## Reporting a Vulnerability

Security is a top priority for PLUSE, especially given our role in mission-critical predictive maintenance. We appreciate the community's effort in disclosing vulnerabilities responsibly.

### How to Report

To report a security vulnerability in the PLUSE platform, please **DO NOT** open a public GitHub issue. Instead, please follow these steps:

1.  Draft a detailed report that clearly describes the vulnerability, including:
    * The **version(s)** of PLUSE affected.
    * The **type** of vulnerability (e.g., SQL Injection, XSS, Remote Code Execution).
    * A **proof-of-concept** or steps required to reproduce the issue.
    * The **impact** of the vulnerability on data confidentiality, integrity, or availability.
2.  Submit the report privately to the core development team via email at: **`security-pluse@iitk-phm.edu`** (Substitute with your actual security contact email).
3.  Please encrypt your email with our PGP key, which can be found [here](Link_to_PGP_Key). (Optional, but highly recommended).

### Response and Triage Process

1.  **Acknowledgement:** You should receive an initial acknowledgement of your report within **48 hours** (two business days).
2.  **Triage:** The PLUSE Security Team will triage the vulnerability to assess its severity and validity. We aim to provide a status update on the report's acceptance or decline within **5 business days** of acknowledgement.
3.  **Acceptance:** If the vulnerability is accepted:
    * We will work internally to develop a patch.
    * We will provide you with an expected timeline for the fix and the release of the security update.
    * We request that you **keep the vulnerability confidential** until we have released the official fix to allow our users time to update their systems.
4.  **Declined:** If the vulnerability is declined (e.g., if it is non-reproducible, low impact, or not considered a security bug):
    * We will provide a brief explanation for the decision.
    * If you believe the issue warrants further attention, you may discuss it further with the team via the same private channel.

### Severity and Timelines (Disclosure Policy)

We follow the standard CVSS (Common Vulnerability Scoring System) to determine the severity and prioritize remediation.

| Severity | Time to Remediation Target (After Acceptance) | Disclosure Protocol |
| :--- | :--- | :--- |
| **Critical** | **7 days** | Immediate release of patch and advisory. |
| **High** | **14 days** | Release of patch and advisory. |
| **Medium** | **30 days** | Remediation targeted for the next maintenance release. |
| **Low** | **90 days** | Remediation targeted for a future release. |

We are committed to public disclosure once a patch is available. We will credit the researcher who reported the vulnerability, unless they wish to remain anonymous.
